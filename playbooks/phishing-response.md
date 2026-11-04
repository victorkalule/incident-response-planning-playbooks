# Phishing — Incident Response Playbook

**Status:** Training response procedure; no live phishing incident is claimed.

## 1. Identify and verify
- Review sender and reply-to information, headers, suspicious domains, unexpected attachments, and unusual requests.
- Use approved email security tools and threat intelligence to evaluate indicators without interacting with suspicious links or attachments directly.

## 2. Contain the threat
- Quarantine or remove confirmed malicious messages through authorized email administration processes.
- Block relevant senders, domains, or links when supported by evidence and policy.
- Notify the security response team through approved channels.

## 3. Investigate affected users and systems
- Determine which users received the message and whether any links were opened, attachments executed, or credentials entered.
- Check authentication, endpoint, and network evidence for signs of follow-on compromise.
- Preserve original message and header information securely.

## 4. Secure accounts and endpoints
- Where credential compromise is suspected or confirmed, reset affected credentials, revoke sessions, and review sign-in activity.
- Require or strengthen MFA as appropriate.
- Use approved endpoint containment and investigation procedures when malicious software might have executed.

## 5. Communicate, monitor, and learn
- Inform affected users of any required protective steps.
- Monitor for repeated campaigns, unusual logins, and later indicators of compromise.
- Record the timeline, impacted users, findings, and security improvements for incident closure.

*Adapted from the phishing playbook in the Capybara Unlimited training IRP. No original suspicious messages, inbox data, or user credentials are included.*
