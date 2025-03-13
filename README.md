# Demo Blog Site
This site is purposly built to be bad to test your security tooling!

## What's in here?

- Hugo website running a basic website

### Vulnerabilites

##### Docker Image

- Alpline Linux 3.18 which contains numerous CVEs

##### Python App

- Requests containing CVEs (CVE-2018-18074, CVE-2023-32681 and CVE-2024-35195)

##### NodeJS App

- Express which contains transient dependencies:

  CVE-2024-29041 [High]

- Lodash: 

  CVE-2020-28500 [High]

  CVE-2020-8203 [Critical]

  CVE-2021-23337 [Critical]

  NSWG-ECO-516 [Critical]

### Personal Data

There are different types of PII that can be used to validate your security tool is able to perform data security.

- Credit cards:
  - Visa
  - Mastercard
  - Amex
- PII - Names and email addresses

### Secrets

- Mock AWS IAM keys

