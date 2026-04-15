# Security Policy

## Reporting a Vulnerability

OSDRI maintains platforms that process **veteran identity data and disability claim information**. Security issues are taken seriously.

**If you discover a security issue, do NOT open a public issue.** Instead:

1. Email **sschultz@osdri.org** with subject line `SECURITY: <brief description>`
2. Include:
   - Description of the issue
   - Steps to reproduce
   - Impact (what data/systems could be affected)
   - Your contact info for follow-up
3. Allow up to **5 business days** for initial response

## PHI / PII Handling

**Never include actual veteran data, PHI, PII, or claim details in:**
- Public issues
- Pull request descriptions
- Commits (including commit messages)
- Screenshots in documentation
- Logs committed to the repo

Redact with placeholders: `[VETERAN_ID]`, `[CASE_ID]`, `[DOB]`, `[SSN_LAST4]`.

## Scope

In scope for disclosure:
- OSDRI-operated web applications and APIs
- OSDRI-published container images
- Dependency vulnerabilities affecting OSDRI code

Out of scope:
- Social engineering of OSDRI staff
- Physical attacks
- Third-party services we use (report to them directly)

## Acknowledgments

We credit responsible disclosures in release notes unless requested otherwise.
