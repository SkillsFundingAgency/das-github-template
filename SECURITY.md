# Security notice

This is the security notice for all Department for Education (DfE) repositories. It explains how vulnerabilities should be reported to DfE. At DfE, we have cyber security and information assurance teams, as well as security-conscious people within the programmes and services, that assess and triage all reported vulnerabilities.

## Reporting a vulnerability

DfE is an advocate of responsible vulnerability disclosure. If you’ve found a vulnerability, we would like to know so we can fix it.
If you believe you have found a vulnerability, submit your report to us through [HackerOne](https://hackerone.com/41ff5198-0e21-4656-9f54-03cce570d7ff/embedded_submissions/new).

Up to date contact information for DfE can be found in our [central security.txt file](https://vdp.security.education.gov.uk/.well-known/security.txt).

In your report please include details of:

* the website, page or repository where the vulnerability can be found
* a brief description of the vulnerability
* optionally, the type of vulnerability and any related [OWASP category](https://owasp.org/www-community/vulnerabilities/)
* steps to reproduce - these should be a non-destructive proof of concept

Including steps to reproduce the vulnerability helps to triage the report quickly and accurately, and reduces the likelihood of duplicate reports, or malicious exploitation of some vulnerabilities such as sub-domain takeovers

## Scope

The following are **not** in scope:

* volumetric vulnerabilities - for example, overwhelming a service with a high volume of requests
* reports indicating that our services do not fully align with ‘best practice’, for example, missing security headers

If you are not sure, you can still contact us by email at [vulnerability.management@education.gov.uk](mailto:vulnerability.management@education.gov.uk).

## Bug bounty

DfE does not offer a paid bug bounty programme.  We will make efforts to show appreciation to people who take the time and effort to disclose vulnerabilities responsibly in our [thanks.txt](https://vdp.security.education.gov.uk/thanks.txt).

## What to expect

Priority for remediation is assessed by looking at the impact, severity and exploit complexity. Vulnerability reports might take some time to triage or address. 

You are welcome to enquire on the status but avoid doing so more than once every 2 weeks. This allows our teams to focus on fixing the vulnerability.

We will tell you when the reported vulnerability is fixed and may ask you to confirm that the solution has worked for you by retesting the issue after a fix has been deployed.

Once your vulnerability has been resolved, you can ask us to disclose your report. Disclosing helps us unify and improve guidance to affected users, so coordinating and including DfE in any of your information releases can be helpful.

If we can confirm and resolve the vulnerability, we’ll offer to include you on [our thanks and acknowledgement page](https://vdp.security.education.gov.uk/thanks.txt). We’ll ask you to confirm the details you want to include before anything is published.

## Code of Conduct

DfE has a contributors [code of conduct](https://github.com/dfe-digital/.github/blob/master/CODE_OF_CONDUCT.md)

---

### Further reading and inspiration about responsible disclosure and `SECURITY.md`
* [Department for Education vulnerability disclosure policy](https://www.gov.uk/guidance/report-a-vulnerability-on-a-department-for-education-system)
* [NCSC vulnerability reporting](https://www.ncsc.gov.uk/information/vulnerability-reporting)
