# Windows Security Log Analysis

## Objective
Practice reviewing Windows-style authentication events and separating observations from assumptions.

## Scenario
A fictional workstation has several failed logons followed by a successful logon. The data below is simulated and does not come from a real Windows host.

## Files
- `data/windows_events.csv` — simplified Windows-style event records.
- `analysis.md` — example analysis and next steps.

## What to look for
- Repeated failed logons (illustrative Event ID 4625).
- A successful logon after repeated failures (illustrative Event ID 4624).
- Whether the account, source, logon type, host, and time window make sense.

## Important limitation
The event IDs and fields are simplified for training. A real investigation should preserve original event fields and correlate with endpoint, VPN, identity-provider, and network logs.
