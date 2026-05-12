# Indicators of Compromise (IOCs)
## Phishing Analysis – Global Merit Expert Loan Scam

| Type | Value | Notes |
|------|-------|-------|
| Sender IP | `102.69.139.111` | Origin IP of the email |
| Mail Server IP | `202.129.206.234` | Relay server — host4.ns.co.th |
| Sending Domain | `suksapan[.]or[.]th` | Legitimate Thai domain — likely compromised |
| Sender Address | `shore@suksapan[.]or[.]th` | Compromised account used to send scam |
| Reply-To Address | `globalmeritexperts@gmail[.]com` | Attacker-controlled inbox — all replies diverted here |
| Attacker Alias | `Mr Richard Owen` | Name used in scam email body |
| Attacker Organisation | `Global Merit Expert` | Fictitious loan company used as lure |
| Mail Server | `host4.ns[.]co[.]th` | Sending mail server (Exim 4.96) |
| SPF Result | `softfail` | Sending IP not authorised for domain |
| DKIM Result | `none` | Email not cryptographically signed |
| DMARC Result | `none` | No domain policy enforced |
| SCL Score | `5` | Microsoft spam confidence level — flagged as likely spam |
| X-SID Result | `FAIL` | Microsoft sender ID check failed |
| Threat Type | Advance Fee Fraud / 419 Scam | No URL — purely social engineering via email reply |
