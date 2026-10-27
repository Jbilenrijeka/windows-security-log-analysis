# Example analysis

## Observations
1. Three failed logons for `j.smith` occurred within 11 seconds from `10.20.5.44`.
2. A successful logon from the same source followed seven seconds after the last recorded failure.
3. The sample also includes a successful logon from another internal address.

## Assessment
This is a **suspicious pattern that warrants investigation**, not proof of account compromise. The sample is too small to establish whether the source is expected or whether the successful logon was legitimate.

## Recommended next steps
- Verify whether `10.20.5.44` is an expected device or service.
- Review surrounding authentication events for the account and source.
- Check MFA, VPN, endpoint, and identity-provider records if available.
- Contact the account owner or follow the organization's verification process.
- Escalate or contain only according to validated evidence and policy.

## Confidence
Low to moderate for the need to investigate; insufficient evidence to confirm compromise.
