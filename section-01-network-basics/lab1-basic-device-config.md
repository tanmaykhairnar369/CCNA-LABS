# Lab 1: Basic Device Configuration

## Objective
- Configure basic device settings on a Cisco router and switch.

## Steps
1. Set hostname.
2. Configure console password.
3. Configure enable secret password.
4. Save configuration.

## Commands Used
```bash 
Router> enable
Router# configure terminal
Router(config)# hostname R1
Router(config)# line console 0
Router(config-line)# password cisco
Router(config-line)# login
Router(config)# enable secret class
Router(config)# end
Router# write memory
```
## Key Learnings
- Difference between `enable password` and `enable secret`.
- Importance of securing console access.
- How to save configurations (`write memory` / `copy run start`).
