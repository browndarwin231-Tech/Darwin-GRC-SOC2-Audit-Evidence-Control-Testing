# SOC 2 Audit Exceptions

## Purpose

This document records control exceptions identified during the simulated SOC 2 control testing engagement for CloudNova Technologies.

An audit exception occurs when a control is missing, incomplete, not operating consistently, or lacks sufficient supporting evidence.

---

## Exception Summary

| Exception ID | Control | Result | Risk Level |
|---|---|---|---|
| EX-001 | Quarterly User Access Review | Fail | High |
| EX-002 | Privileged Access Review | Fail | High |
| EX-003 | Incident Response Testing | Fail | High |
| EX-004 | Vulnerability Remediation | Partial | Medium |
| EX-005 | Backup Restoration Testing | Fail | Medium |
| EX-006 | Vendor Security Review | Partial | Medium |

---

## EX-001: Quarterly User Access Review

### Control

Quarterly User Access Review

### Condition

The organization performs access reviews, but one quarterly review did not include complete approval documentation.

### Criteria

User access should be reviewed on a recurring basis with evidence showing reviewer approval and remediation of inappropriate access.

### Risk

Unauthorized or unnecessary access may remain active if access reviews are not performed and documented consistently.

### Risk Level

**High**

### Recommendation

Establish a formal quarterly access review process that includes:

- User access listing
- Reviewer name
- Review date
- Approval status
- Access changes
- Removed permissions
- Evidence retention

---

## EX-002: Privileged Access Review

### Control

Privileged Access Review

### Condition

Administrator accounts exist, but recurring privileged-access review evidence is incomplete.

### Criteria

Privileged access should be periodically reviewed to confirm that elevated permissions remain appropriate.

### Risk

Excessive administrator access may increase the impact of account compromise or insider misuse.

### Risk Level

**High**

### Recommendation

Perform quarterly privileged-access reviews and retain documented evidence of:

- Privileged accounts
- Business justification
- Account owner
- Reviewer approval
- Removed permissions
- Exceptions

---

## EX-003: Incident Response Testing

### Control

Incident Response Testing

### Condition

The organization maintains an incident response plan, but no current tabletop exercise evidence was provided.

### Criteria

Incident response procedures should be tested periodically to validate readiness.

### Risk

The organization may respond slowly or inconsistently during a real cybersecurity incident.

### Risk Level

**High**

### Recommendation

Conduct an annual incident response tabletop exercise and document:

- Participants
- Scenario
- Response actions
- Escalation procedures
- Communication decisions
- Lessons learned
- Corrective actions

---

## EX-004: Vulnerability Remediation

### Control

Vulnerability Remediation

### Condition

Some high-severity vulnerabilities were remediated after the organization's target remediation timeline.

### Criteria

Security vulnerabilities should be remediated according to documented severity-based timelines.

### Risk

Delayed remediation may increase the likelihood that known vulnerabilities are exploited.

### Risk Level

**Medium**

### Recommendation

Establish and enforce remediation targets such as:

- Critical: 7 days
- High: 30 days
- Medium: 60 days
- Low: 90 days

Exceptions should require formal risk acceptance and documented approval.

---

## EX-005: Backup Restoration Testing

### Control

Backup Restoration Testing

### Condition

Backups are performed, but no recent quarterly restoration-testing evidence was available.

### Criteria

Organizations should periodically test backup restoration to confirm that systems and data can be successfully recovered.

### Risk

Backups may be unusable during ransomware, system failure, or disaster recovery.

### Risk Level

**Medium**

### Recommendation

Perform quarterly backup restoration tests and document:

- System tested
- Backup selected
- Test date
- Restoration result
- Recovery time
- Issues identified
- Corrective actions

---

## EX-006: Vendor Security Review

### Control

Vendor Security Review

### Condition

Vendor security assessments are performed, but formal approval evidence is incomplete.

### Criteria

Critical vendors should undergo documented security review and approval before onboarding.

### Risk

A vendor may be approved without sufficient evidence that security risks were reviewed and accepted.

### Risk Level

**Medium**

### Recommendation

Require documented vendor approval that includes:

- Vendor risk classification
- Security questionnaire
- Identified findings
- Risk owner
- Approval decision
- Required remediation
- Final approval date

---

## Overall Conclusion

The audit identified six control exceptions.

The highest-priority findings involve:

- User access governance
- Privileged access management
- Incident response preparedness

Medium-risk findings involve:

- Vulnerability remediation
- Backup restoration testing
- Vendor approval documentation

All exceptions should be tracked through remediation and validated before closure.
