# Data Breach Response Policy

> priority point of contact: <sam@manifoldfinance.com}>

- [Data Breach Response Policy](#data-breach-response-policy)
  * [Responsible Disclosure](#responsible-disclosure)
  * [Sensitive Data](#sensitive-data)
    + [Expectations In the event of a Data Breach,](#expectations-in-the-event-of-a-data-breach-)
    + [Non-Data-Breach Vulnerabilities](#non-data-breach-vulnerabilities)

## Responsible Disclosure

Any parties who suspect a vulnerability or data breach
should send an encrypted email to:

sam bacha <sam@manifoldfinance.com>  <br>
operations <ops@manifoldfinance.com>

## Sensitive Data

The following is data that CommodityStream stores and considers
sensitive. If any such data becomes accessible to an unauthenticated /
unauthorized user, that will be considered a Data Breach:

Private repository contents (i.e. source code), whole or in "diff" form Private
user email addresses Any secrets or tokens which grant access to the above

> NOTE: Repository names, commit shas, Pull Request numbers, Pull Request
> descriptions, and GitHub user or organization names are not considered sensitive
> for the purposes of this response policy.

### Expectations In the event of a Data Breach,

All running services will be stopped to prevent further access Impacted users
will be notified by email within 24 hours, security@github.com will be notified
within 24 hours, along with any other vendors that may be affected.

### Non-Data-Breach Vulnerabilities

CommodityStream routinely monitors for patched vulnerabilities in the software
and infrastructure it depends on. Most such vulnerabilities are not at risk of
causing a Data Breach. In such cases, they will be patched without
user-notification or data-breach response activities. These are published
in our RSS Feed.
