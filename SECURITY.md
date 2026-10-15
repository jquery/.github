# Security Policy

## Supported Versions

Please check which versions of the jQuery project you are using are currently supported.

- The [latest released version of jQuery](https://github.com/jquery/jquery/releases) is supported.
- The [latest released version of jQuery UI](https://github.com/jquery/jquery-ui/releases) is supported, but jQuery UI supports multiple versions of jQuery. More information can be found at https://jqueryui.com/.
- [jQuery Mobile](https://github.com/jquery-archive/jquery-mobile) is no longer supported.

Fixes are not backported to earlier versions. Commercial support for previous versions is available from third parties; see the [jQuery README](https://github.com/jquery/jquery#version-support).

## jQuery Websites

The jQuery infrastructure is maintained with puppet and the configuration is publicly available and documented at https://github.com/jquery/infrastructure-puppet.

Content for individual sites can be found in their respective repositories. For example, the content for jquery.com is available at https://github.com/jquery/jquery.com.

Search for the right repository at https://github.com/jquery.

## Reporting a Vulnerability

Please report security issues **privately**:

- Email: security@jquery.com

**Do not** file public GitHub issues for security problems.

Reports **must** include:
- The version(s) you tested, with the commit SHA if you tested a build from `main`
- The specific API involved, with the file and line in the project's source you believe is at fault
- A proof of concept that runs against an unmodified build of the version you name
- A description, in your own words, of what the library is doing that you consider unsafe and what the impact is
- Your contact and preferred credit name

Reports missing any of the above will be closed with a request for the missing information.

### Report quality and automated submissions

Most reports we receive are produced by automated tools or language models and do not describe a real vulnerability. Reviewing them costs maintainer time that would otherwise go to real issues.

You may use whatever tools you like to find and write up an issue, but you are responsible for every claim in your report. Reports that cite APIs, files, or lines that do not exist, that restate documented behavior as a vulnerability, or that name a vulnerability class without demonstrating a specific path through the library will be closed. We will ask follow-up questions and expect answers in your own words; if you cannot answer them, the report will remain closed. Repeat submissions of this kind may result in a ban from the project and withdrawal of any credit previously given.

This applies regardless of how the report reaches us: email, a GitHub security advisory, or escalation through the OpenJS Foundation CNA. See also [Unsolicited and Machine-Generated Contributions](CONTRIBUTING.md#unsolicited-and-machine-generated-contributions) in CONTRIBUTING.md.

If you receive no response (including a closure or a request for more information) within **6 business days**, or if you cannot find a private security contact for the project, you may **escalate to the OpenJS Foundation CNA** at `security@lists.openjsf.org`.

If the project acknowledges your report but does not provide any further response or engagement within **14 days**, escalation is also appropriate.

## Coordination & Disclosure

Important:
- If the vulnerability is considered valid and accepted, a patch will be made for the latest version of the affected project.
- If the vulnerability is deemed invalid, no further action is required.

We follow coordinated vulnerability disclosure:
- We will acknowledge your report, assess impact, and work on a fix.
- We aim to provide status updates at reasonable intervals until resolution.
- We will publish a security advisory (and **CVE via the OpenJS CNA when applicable**) once a fix or mitigation is available. We credit reporters by default unless you request otherwise.
