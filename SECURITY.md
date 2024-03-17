# Security Policy

## Reporting a Vulnerability

To report a SpinKube vulnerability, either:

1. Report it on Github directly:

    Navigate to the security tab on the repository

    Click on 'Advisories'

    Click on 'Report a vulnerability'

2. Send an email to `spinkubemaintainers@gmail.com` detailing the issue and steps
to reproduce.

The reporter(s) can expect a response within 24 hours acknowledging
the issue was received. If a response is not received within 24 hours, please
reach out to any maintainer directly on the [CNCF Slack Channel: #spinkube](https://cloud-native.slack.com/archives/C06PC7JA1EE)
to confirm receipt of the issue.

## Review Process

Once a maintainer has confirmed the relevance of the report, a draft security
advisory will be created on Github. The draft advisory will be used to discuss
the issue with maintainers, the reporter(s), and SpinKube's security advisors.
If the reporter(s) wishes to participate in this discussion, then provide
reporter Github username(s) to be invited to the discussion. If the reporter(s)
does not wish to participate directly in the discussion, then the reporter(s)
can request to be updated regularly via email.

If the vulnerability is accepted, a timeline for developing a patch, public
disclosure, and patch release will be determined. If there is an embargo period
on public disclosure before the patch release, an announcment will be sent to
the security announce mailing list: `spinkube-security-announce@googlegroups.com`
announcing the scope of the vulnerability, the date of availability of the
patch release, and the date of public disclosure. The reporter(s) are expected
to participate in the discussion of the timeline and abide by agreed upon dates
for public disclosure.

## Supported Versions

The latest minor release and the latest - 1 minior release will receive security
updates. For any security issues discovered on older versions or dependencies,
please inform committers using the same security mailing list as for reporting
vulnerabilities.

## Joining the security announce mailing list

Any organization or individual who directly uses SpinKube packages in production
or in a security critical application is eligible to join the security announce
mailing list. Indirect users who use SpinKube through a vendor are not expected to
join, but should request their vendor join. To join the mailing list, the individual
or organization must be sponsored by either a SpinKube maintainer or security advisor
as well as have a record of properly handling non-public security information. If a
sponsor cannot be found, sponsorship may be requested at `spinkubemaintainers@gmail.com`.
Sponsorship should not be requested via public channels since membership of the security
announce list is not public.
