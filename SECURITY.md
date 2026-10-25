# Security

Protect the Hub, project teams, and collaborators by keeping secrets out of this repository and its history.

**Never commit:**

- Passwords or private credentials
- API keys or access tokens
- Supabase service-role or other secret keys
- `.env`, `.env.local`, or other files containing local secrets
- Private keys, certificates, or confidential configuration

If a secret is exposed, treat it as compromised: notify the relevant credential owner and arrange revocation or rotation promptly. Removing a secret in a later commit does not remove it from repository history.

## Reporting a security issue

Do not report exploitable details in a public issue. Use the repository's private vulnerability-reporting feature if it is enabled. Otherwise, contact an authorized ACES Innovation Hub or repository administrator through an official private channel. Do not assume an unconfirmed contact address or share sensitive data with unrelated parties.

Please provide enough information to help reproduce and assess the issue, while avoiding unnecessary access to data or systems that are not yours.
