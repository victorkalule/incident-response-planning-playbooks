# Incident Response Lifecycle — Proposed Procedure

**Status:** Training plan; no actual incident or formal exercise results are documented in the source.

The source plan structures response work around six stages:

## 1. Preparation
- Maintain security policies, standards, and response procedures.
- Provide user security awareness training.
- Ensure availability of relevant monitoring, forensic, and backup capabilities.
- Prepare incident-specific response playbooks.

## 2. Detection and analysis
- Monitor SIEM, endpoint, and network events for signs of suspicious activity.
- Classify incidents by **severity** (low, medium, high, critical) and **type** (such as malware, phishing, insider threat, DoS/DDoS, or data breach).
- Collect appropriate evidence such as system/application/network logs and phishing email headers.
- Determine escalation needs and whether a wider response or outside support is required.

## 3. Containment
- Isolate affected endpoints and disable or lock compromised accounts when appropriate.
- Restrict known malicious communications with authorized network controls.
- Preserve investigative evidence before disruptive actions.
- Limit spread through temporary access restrictions, patching, and stronger network segmentation as appropriate.

## 4. Eradication
- Investigate the root cause and how defensive controls were bypassed.
- Remove malicious artifacts and persistence mechanisms under an approved plan.
- Apply required updates and controls to address the underlying exposure.

## 5. Recovery
- Rebuild or restore systems from validated, clean backup sources.
- Confirm system integrity and readiness before returning services to production.
- Increase monitoring for signs of reinfection or recurring malicious activity.

## 6. Post-incident analysis
- Construct an incident timeline and document impact, root cause, actions taken, and remaining gaps.
- Evaluate the effectiveness of response stages.
- Track lessons learned and changes to playbooks, controls, policies, and training.

## Proposed decision points

| Decision | Responsibility described in the source |
| --- | --- |
| Confirm severity and escalate | SOC analysts assess; Incident Commander is informed when escalation is needed |
| Decide broad response and containment | Incident Commander coordinates decisions with appropriate stakeholders |
| Authorize external notifications | Legal/Compliance review; Communications/PR issues approved public messages |
| Restore service | Technical teams validate remediation and readiness, with incident leadership oversight |

## Limitations

This file summarizes the **planned workflow**. The source does not document response time targets, an executed drill, ticket records, or operational testing. It should not be read as a validated production runbook.
