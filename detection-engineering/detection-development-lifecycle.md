# Detection Development Lifecycle (DDL)

## Phases

### Phase 1: Identify
- Review threat intelligence for new TTPs
- Analyze MITRE ATT&CK gap analysis
- Process purple/red team findings
- Evaluate incident lessons learned

### Phase 2: Research
- Study technique details (ATT&CK, papers)
- Identify required data sources and log fields
- Review existing community detections (Sigma, Elastic)
- Understand normal vs. malicious patterns

### Phase 3: Develop
- Write detection rule (Sigma preferred for portability)
- Include metadata: author, date, references, tags
- Document false positive scenarios
- Map to MITRE ATT&CK techniques

### Phase 4: Test
- Validate with Atomic Red Team
- Test against historical incident data
- Measure false positive rate
- Verify field extraction and parsing

### Phase 5: Tune
- Whitelist known-good processes
- Adjust thresholds based on baseline
- Optimize search performance
- Document tuning decisions

### Phase 6: Deploy
- Push to production SIEM
- Configure alerting and response
- Set severity and urgency
- Enable in appropriate detection tier

### Phase 7: Maintain
- Review effectiveness monthly
- Update for technique evolution
- Remove deprecated rules
- Track detection metrics (TP, FP, MTTD)

## Quality Checklist

- [ ] Full metadata (author, date, severity, references)
- [ ] MITRE ATT&CK techniques mapped
- [ ] False positives documented
- [ ] Tested against attack simulation
- [ ] Performance benchmarked (< 60s)
- [ ] Tuning guide provided
- [ ] Peer reviewed
