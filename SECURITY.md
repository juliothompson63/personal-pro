# Security Policy

## Supported version

Security reports are currently accepted for the latest code on the `main` branch.

## Reporting a vulnerability

Please do not publish credentials, personal data, or exploit details in a public issue. Contact the repository owner privately through the contact options shown on the GitHub profile and include:

- A description of the affected area.
- Steps to reproduce, if safe.
- Potential impact.
- A suggested mitigation, if known.

Please allow time for investigation before public disclosure.

## Data and credentials

- Never commit `.env.local`, API keys, Supabase service-role keys, or access tokens.
- Use synthetic data in demonstrations and screenshots.
- Review Supabase Row Level Security policies before deploying with real users.
