# Denial-of-Service — Incident Response Playbook

**Status:** Training playbook design. No real attack, implemented rate limit, or service recovery is claimed.

## 1. Identify and characterize unusual traffic
- Review firewall, IDS/IPS, network flow, and service telemetry for traffic anomalies.
- Determine whether activity indicates a DoS/DDoS event rather than a normal usage spike.
- Characterize potential volumetric, protocol-level, or application-layer pressure.

## 2. Measure scope and business impact
- Compare traffic rates against available baselines.
- Determine affected services, including websites, APIs, DNS, and remote access.
- Evaluate resource pressure and the impact on important business functions.

## 3. Investigate patterns and affected infrastructure
- Analyze source patterns, unusual IP ranges, protocol distributions, and repeating request behavior.
- Recognize that a distributed attack may involve many sources rather than one origin.
- Check system health and downstream service dependencies.

## 4. Apply and observe authorized mitigations
- Coordinate with network and service owners before changes.
- Consider firewall/ACL filtering, SYN-related protections, HTTP rate limiting, or location-based filtering only when appropriate to the observed attack and organizational policy.
- Observe traffic patterns and service health to determine whether mitigations are helping without unduly disrupting legitimate users.
- Communicate verified business impact and restoration status to leadership.

## Source limitations

The source DoS playbook ends after its mitigation monitoring section. It does not document a completed attack exercise, recovery result, or post-incident report for a specific DoS event. This portfolio summary does not invent those outcomes.
