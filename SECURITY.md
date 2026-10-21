# Security Policy

This is the Security Policy for Voyager, in which we will go over full detail of security related things, like reporting vulnerabilities, version support plans and more. Let's start!

## Version Support Plans

Plan 2.0, as on 21st of October, 2026, is to have a channel release format. Voyager undergoes 3 release channels similar to Chrome for updates: Canary, Beta, Stable. Each channel undergoes a different update cycle and frequency, with varying orders of stability. This branch (Canary) is the most experimental and unstable branch. Developers post updates and features most frequently here, but it is not stable and will have issues. By using Voyager Canary builds, as per the same licensing clause via GNU AGPL v3, the publisher holds no liability and provides no warranty upon using this build. Canary is only for those who want to check out experimental features and want to submit changes to Voyager. Canary is the only build of Voyager that will merge active pull requests. This is the only version where raised PRs can be merged by developers as well. Canary versions are deprecated as soon as the next build comes out.

## Vulnerability discovery and fixing

**Please do not report security vunerabilities on GitHub on public issues**

Instead, report vulnerabilities from the GitHub security panel where by going into advisories, you can report a vulnerability.
If you want to send a vulnerability anonymously, send an email to our team to report the issue. If possible, encrypt the message with our sensitive information key and send it to us.
You will receive a response from our team within 24 hours. If for some reason you do not receive a response, please follow-up via email and we will check your reported issue.

If you are sending issues via email, please type it in the following format. GitHub reports will have the following format built-in.

- Type of issue (eg:- downtime, buffer overflow, SQL injection, cross-site scripting)
- Level of issue (level 1 to level 4, with level 1 being low harm, and level 4 being server shutdown to fix issue.)
- Location of bugged code and full path(s) of source files related to demonstration of issue
- Special configurations related to issue
- Step-by-step instructions to replicate the issue
- Exploit code (if possible)
- Impact of issue (also explaining how a hacker with malicious intent might use the exploit.)

All of this information will help us to prioritize your issue.

## Preferred Language

It is recommended that you use English to transcribe the issue. However it is not mandatory.
