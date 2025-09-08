# Security Policy

## Supported Versions

Please check which versions of the jQuery project you are using are currently supported.

- The [latest released version of jQuery UI](https://github.com/jquery/jquery/releases) is supported.
- The [latest released version of jQuery UI](https://github.com/jquery/jquery-ui/releases) is supported, but jQuery UI supports multiple versions of jQuery. More information can be found at https://jqueryui.com/.
- [jQuery Mobile](https://github.com/jquery-archive/jquery-mobile) is no longer supported.

## jQuery Websites

The jQuery instrastructure is maintained with puppet and the configuration is publicly available and documented at https://github.com/jquery/infrastructure-puppet.

Content for individual sites can be found in their respective repositories. For example, the content for jquery.com is available at https://github.com/jquery/jquery.com.

Search for the right repository at https://github.com/jquery.

## Reporting a Vulnerability

Please report security issues **privately**:

- Email: security@jquery.com

**Do not** file public GitHub issues for security problems.

When reporting, please include:
- Affected project/repo and version(s)
- Impact and component(s) involved
- Reproduction steps or PoC (if available)
- Your contact and preferred credit name

If you do not receive an acknowledgement of your report within **6 business days**, or if you cannot find a private security contact for the project, you may **escalate to the OpenJS Foundation CNA** at `security@lists.openjsf.org`.

If the project acknowledges your report but does not provide any further response or engagement within **14 days**, escalation is also appropriate.

## Coordination & Disclosure

Important:
- If the vulnerability is considered valid and accepted, a patch will be made for the latest jQuery version.
- If the vulnerability is deemed invalid, no further action is required.

We follow coordinated vulnerability disclosure:
- We will acknowledge your report, assess impact, and work on a fix.
- We aim to provide status updates at reasonable intervals until resolution.
- We will publish a security advisory (and **CVE via the OpenJS CNA when applicable**) once a fix or mitigation is available. We credit reporters by default unless you request otherwise.
