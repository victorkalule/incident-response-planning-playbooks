# Roles, Escalation & Communications

**Status:** Proposed responsibilities for the training organization.

## Response roles

| Role | Responsibilities described in the source plan |
| --- | --- |
| Incident Commander | Coordinates response; oversees major containment, eradication, and public-communication decisions; ensures documentation |
| SOC analysts | Monitor SIEM/EDR, triage alerts, assign incident severity, and escalate findings |
| Forensic specialists | Preserve and analyze logs, disks, memory, and other evidence; support root cause assessment |
| IT administrators | Carry out isolation, account restrictions, patching, restoration, and hardening |
| Legal and Compliance | Evaluate obligations, notifications, and regulatory requirements; review public messages |
| Communications / PR | Prepare approved stakeholder and public statements |
| Employees and contractors | Report suspicious events and follow authorized security guidance; avoid unauthorized sharing of incident details |

## Internal communication

- Incident leadership informs executives and relevant department leads based on severity and business impact.
- Use approved organizational channels for sharing necessary information.
- Maintain a communication log recording **who** was informed, **when**, and **what** was communicated.
- Restrict sensitive investigative details to those who need them for response.

## External communication

The source plan instructs the team to assess whether customers, partners, regulators, or other external parties require notification under applicable law, contracts, or policy. Legal/Compliance reviews the requirements and messaging. Public statements are issued only through approved Communications/PR personnel.

**No specific notification deadline is established in the source document.** Legal requirements must be determined for the real incident, data type, and jurisdiction.

## Recommended documentation fields

The source plan calls for timelines, findings, impact, actions taken, root cause, and lessons learned. A future incident record could organize those items as:

- Incident ID and severity
- Discovery and escalation timestamps
- Affected assets, accounts, and services
- Evidence sources and investigative observations
- Containment and restoration actions
- Notifications and approvals
- Root cause, remediation, and follow-up owners

The field list is a **proposed portfolio-friendly structure**, not an executed incident ticket from the training source.
