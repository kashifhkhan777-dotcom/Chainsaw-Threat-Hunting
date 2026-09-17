# Chainsaw Threat Hunting Lab

## Overview
Used Chainsaw (by WithSecure) to hunt through a dataset of simulated attack EVTX logs (`EVTX-ATTACK-SAMPLES`). The tool used Sigma detection rules to identify malicious activity mapped to the MITRE ATT&CK framework.

## Commands Used
```cmd
.\chainsaw.exe hunt evtx_attack_samples\ --rule rules\ --mapping mappings\sigma-event-logs-all.yml > output.txt