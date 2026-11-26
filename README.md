# Troubleshoot Default Gateway Issues (Packet Tracer)

## Overview
Troubleshooting lab on a two-network topology (192.168.10.0/24 and 192.168.11.0/24) connected through R1. The goal was to find and fix addressing and default gateway problems that blocked local and end-to-end connectivity.

## Skills Demonstrated
- Verifying IP address, subnet mask and default gateway with `ipconfig` and `show run`
- Isolating problems with ping tests (same network first, then remote)
- Applying the troubleshooting method: verify, isolate, fix, test, document

## Method
1. Completed the addressing table, including default gateways
2. Tested local connectivity (PC-to-PC, PC-to-switch, PC-to-router)
3. Fixed one issue at a time and re-tested after each fix
4. Tested end-to-end connectivity between the two networks

## Result
All local and end-to-end pings succeed (for example, PC1 to PC4).

## Files
- `lab-worksheet.docx`: completed documentation and test tables
- `*.pkt`: Packet Tracer file
