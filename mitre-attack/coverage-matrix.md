# MITRE ATT&CK Detection Coverage Matrix

## Coverage Summary

| Metric | Value |
|---|---|
| Total Techniques (v14) | 201 |
| Techniques with Detection | 85+ |
| Coverage Percentage | ~42% |
| Priority Gap Areas | Discovery, Collection, Resource Development |

## Coverage by Tactic

| Tactic | Techniques Covered | Coverage |
|---|---|---|
| Initial Access (TA0001) | T1566, T1190, T1078, T1133 | High |
| Execution (TA0002) | T1059, T1204, T1047 | High |
| Persistence (TA0003) | T1053, T1547, T1505 | High |
| Privilege Escalation (TA0004) | T1548, T1068, T1134 | Medium |
| Defense Evasion (TA0005) | T1027, T1562, T1070 | Medium |
| Credential Access (TA0006) | T1003, T1558, T1110 | High |
| Discovery (TA0007) | T1087, T1082, T1083 | Medium |
| Lateral Movement (TA0008) | T1021, T1550, T1570 | High |
| Collection (TA0009) | T1560, T1114 | Medium |
| Exfiltration (TA0010) | T1048, T1567 | Medium |
| Command & Control (TA0011) | T1071, T1573, T1572 | High |
| Impact (TA0040) | T1486, T1490, T1489 | High |

## Priority Gaps for Development

1. T1087 - Account Discovery
2. T1560 - Archive Collected Data
3. T1567 - Exfiltration to Cloud Storage
4. T1574 - Hijack Execution Flow
5. T1055 - Process Injection
