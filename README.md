# Incident Response Plan & Playbooks

**Training assignment | Incident preparation, team responsibilities, and response procedures**

## About this project

I wrote an incident response plan for **Capybara Unlimited**, a fictional medium-sized company used in my cybersecurity training. The goal was to put together a process people could follow when something goes wrong, from the first alert through recovery and lessons learned.

I also developed playbooks for three common situations: malware, phishing, and denial-of-service attacks.

This repository contains a **plan I designed**, not a record of incidents I handled at a company or procedures I tested in production.

## The response process

The plan covers six stages:

1. **Preparation:** Policies, training, monitoring tools, backups, and incident playbooks.
2. **Detection and analysis:** Review alerts, gather evidence, classify the incident, and decide when to escalate.
3. **Containment:** Isolate affected systems, restrict compromised accounts, and prevent further spread.
4. **Eradication:** Remove malicious activity and address the underlying cause.
5. **Recovery:** Restore systems carefully and monitor for signs of reinfection.
6. **Lessons learned:** Document what happened and improve the process for next time.

[Read the response lifecycle](docs/response-lifecycle.md).

## Playbooks

| Playbook | What it covers |
| --- | --- |
| [Malware infection](playbooks/malware-infection.md) | Investigating suspicious files and behavior, preserving evidence, containment, and recovery |
| [Phishing](playbooks/phishing-response.md) | Reviewing suspicious email, identifying affected users, protecting accounts, and follow-up |
| [Denial of service](playbooks/denial-of-service.md) | Investigating unusual traffic, checking service impact, and choosing appropriate mitigations |

## Who does what

One part I spent time on was making responsibilities clear. The plan identifies an Incident Commander, SOC analysts, forensic investigators, IT administrators, Legal/Compliance, Communications, and employees. It also covers internal updates and how external notifications should be handled.

[Read the roles and communication plan](docs/roles-and-communications.md).

## Measuring and improving the process

I proposed tracking how long it takes to detect, contain, and recover from incidents, along with incident closure and completion of improvement actions.

[Read the proposed KPIs and review schedule](docs/kpis-and-maintenance.md).

The training document defines these measures, but it doesn't contain real performance data.

## What I learned

Good incident response needs more than technical tools. People need to know who is responsible for decisions, what evidence to preserve, when to communicate, and what has to be checked before systems go back online.

This project comes from my TripleTen training work. The source plan names several commercial security products as examples, but that does not mean I used or deployed every one of them in this exercise. Original course templates and sensitive information are not included.
