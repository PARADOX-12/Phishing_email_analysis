# Phishing Indicators Reference Guide

## Quick Identification Checklist

### ✅ Authentication Red Flags
- [ ] SPF authentication failure
- [ ] Missing DKIM signature
- [ ] DMARC policy violation
- [ ] Suspicious sender IP address
- [ ] Mail server mismatch

### ✅ Sender Analysis
- [ ] Spoofed or similar domain (e.g., paypa1.com vs paypal.com)
- [ ] Generic or suspicious email addresses
- [ ] Mismatched reply-to addresses
- [ ] Unknown sender claiming to be known entity

### ✅ Content Red Flags
- [ ] Urgent or threatening language
- [ ] Generic greetings ("Dear Customer")
- [ ] Requests for sensitive information
- [ ] Grammar and spelling errors
- [ ] Poor formatting or design
- [ ] Unexpected attachments
- [ ] Suspicious links or URLs

### ✅ Social Engineering Tactics
- [ ] Creates false urgency
- [ ] Appeals to authority
- [ ] Exploits current events
- [ ] Offers too-good-to-be-true rewards
- [ ] Threatens negative consequences

## Analysis Tools Quick Links

**Free Header Analyzers:**
- MXToolbox: https://mxtoolbox.com/EmailHeaders.aspx
- Mailmodo: https://www.mailmodo.com/tools/email-header-analyzer/
- Google Messageheader: https://toolbox.googleapps.com/apps/messageheader/

**Sample Collections:**
- CanIPhish Examples: https://caniphish.com/phishing-email-examples
- GitHub Samples: https://github.com/autinerd/phishing-mail-examples

## Risk Assessment Matrix

| Indicator | Risk Level | Action Required |
|-----------|------------|-----------------|
| Authentication Failure | CRITICAL | Immediate blocking |
| Malicious Attachment | HIGH | Security team alert |
| Suspicious Links | HIGH | URL analysis |
| Social Engineering | MEDIUM | User education |
| Grammar Errors | LOW | Additional verification |


