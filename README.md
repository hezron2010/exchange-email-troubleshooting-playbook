# Exchange Email Troubleshooting Playbook

## Overview
This repository serves as a practical troubleshooting guide for diagnosing and resolving common Microsoft Exchange Online email issues in a remote and enterprise IT support environment.

It is designed for IT Support Specialists responsible for maintaining reliable email services, minimizing downtime, and supporting non-technical users.

---

## Common Email Issues Covered
- Users unable to send or receive emails
- Delayed email delivery
- Mailbox access issues
- Incorrect mail routing
- Spam and phishing filtering problems
- Outlook client connectivity issues

---

## Troubleshooting Approach
This playbook follows a structured, repeatable methodology:

1. Issue identification and user verification
2. Scope assessment (single user vs multiple users)
3. Configuration review
4. Log and message trace analysis
5. Resolution and validation
6. Documentation and prevention

---

## Diagnostic Checklist

### User-Level Checks
- Verify account status in Microsoft 365 Admin Center
- Confirm mailbox license assignment
- Validate user credentials and MFA status
- Check mailbox storage limits

---

### Exchange Online Checks
- Mail flow rules (transport rules)
- Message trace results
- Spam and malware policies
- Connectors and accepted domains

---

### Client-Side Checks
- Outlook profile configuration
- Cached mode status
- OST/PST file health
- Network connectivity

---

## Common Scenarios & Resolutions

### Issue: User Cannot Receive Emails
**Possible Causes**
- Mailbox not provisioned
- License removed or expired
- Mail flow rule blocking messages

**Resolution Steps**
- Assign correct license
- Verify mailbox status
- Run message trace
- Test with internal and external senders

---

### Issue: Emails Going to Spam
**Possible Causes**
- Aggressive spam policy
- Incorrect SPF/DKIM/DMARC configuration

**Resolution Steps**
- Review anti-spam policies
- Whitelist trusted senders
- Validate domain DNS records

---

### Issue: Outlook Not Connecting
**Possible Causes**
- Corrupt Outlook profile
- Network issues
- Service outage

**Resolution Steps**
- Recreate Outlook profile
- Test web access (OWA)
- Check Microsoft 365 service health

---

## Escalation Criteria
Escalate issues when:
- Multiple users are affected
- Mail flow disruption impacts business operations
- Security incidents are suspected
- Configuration changes require approval

---

## Best Practices
- Regularly review mail flow rules
- Monitor message trace logs
- Educate users on phishing awareness
- Maintain updated documentation

---

## Tools Used
- Microsoft 365 Admin Center
- Exchange Admin Center
- Message Trace
- Microsoft Service Health Dashboard

---

## Audience
- IT Support Specialists
- Service Desk Analysts
- System Administrators
- Microsoft 365 Administrators

---

## Author
**Hezron Mutua Peter**  
IT Support Specialist – Microsoft 365 & Remote Workforce Support  

📄 Resume: *Hezron Mutua Peter – IT Support Specialist.pdf*
