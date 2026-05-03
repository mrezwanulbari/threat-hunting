# YARA Rules Collection

Signatures for identifying malware, hacking tools, and suspicious documents.

## Categories

| Directory | Description |
|---|---|
| `malware/` | Cobalt Strike, Mimikatz, web shells, ransomware |
| `tools/` | Offensive tool indicators |
| `documents/` | Malicious document indicators |

## Usage

```bash
# Scan a file
yara -r malware/cobalt-strike-beacon.yar /path/to/suspect/file

# Scan a directory recursively
yara -r -w malware/ /path/to/directory/

# Scan process memory
yara -r malware/mimikatz-indicators.yar --pid <PID>
```
