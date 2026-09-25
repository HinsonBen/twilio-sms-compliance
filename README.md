# Trader CoPilot SMS Compliance Site

Public compliance pages for the **Trader CoPilot** Twilio A2P 10DLC SMS campaign, published with GitHub Pages.

Effective date: September 25, 2026

## Published pages

| Page | URL |
| --- | --- |
| Home | https://hinsonben.github.io/twilio-sms-compliance/ |
| Privacy Policy | https://hinsonben.github.io/twilio-sms-compliance/privacy.html |
| Terms & Conditions | https://hinsonben.github.io/twilio-sms-compliance/terms.html |
| SMS Authorization | https://hinsonben.github.io/twilio-sms-compliance/sms-opt-in.html |

## SMS program summary

- **Brand / application:** Trader CoPilot
- **Use case:** Operational desk alerts only. SMS is not used for marketing, customer solicitation, order placement, or transactions.
- **Recipient:** The Trader CoPilot account owner/operator is the only intended recipient.
- **Authorization:** The account owner/operator explicitly authorizes their personal mobile number by configuring it as the authorized SMS recipient in the Trader CoPilot application. The application sends SMS only to that configured number. There is no public sign-up.
- **Message frequency:** Varies. Messages are sent only when an operational alert is triggered.
- **Cost:** Message and data rates may apply.
- **Opt out:** Reply `STOP`.
- **Help:** Reply `HELP` or email hinsonben@gmail.com.
- **Privacy:** Mobile numbers and SMS opt-in/consent information are not sold, rented, or shared with third parties or affiliates for their own marketing purposes.

## Files

- `index.html` — program overview
- `privacy.html` — Privacy Policy
- `terms.html` — Terms & Conditions
- `sms-opt-in.html` — how the account owner/operator authorizes SMS
- `images/sms-recipient-settings.png` — screenshot of the in-app consent screen (no number entered)

## Twilio campaign registration

- **Privacy Policy URL:** https://hinsonben.github.io/twilio-sms-compliance/privacy.html
- **Terms & Conditions URL:** https://hinsonben.github.io/twilio-sms-compliance/terms.html
- **Opt-in / consent documentation:** https://hinsonben.github.io/twilio-sms-compliance/sms-opt-in.html

- **Consent screen screenshot:** https://hinsonben.github.io/twilio-sms-compliance/images/sms-recipient-settings.png

### Message Flow / Call to Action

The in-app consent screen is not publicly reachable, so the Message Flow points reviewers to the hosted screenshot:

> Trader CoPilot sends operational desk alerts to one recipient only: the account owner/operator of the Trader CoPilot desk application. There is no public sign-up, web form, or keyword opt-in. The owner opts in inside the application: on Settings > Twilio SMS, they enter their own personal mobile number in the "Authorized SMS recipient" field and save it. The consent text shown directly beneath the field reads: "By saving it, you authorize Trader CoPilot to text operational desk alerts to this number. Msg frequency varies. Msg & data rates may apply. Reply STOP to opt out, HELP for help." followed by the Terms and Privacy Policy URLs. The application sends SMS only to that saved number. Because the settings screen is private, a screenshot of the consent screen is hosted at https://hinsonben.github.io/twilio-sms-compliance/sms-opt-in.html (image: https://hinsonben.github.io/twilio-sms-compliance/images/sms-recipient-settings.png). Messages are operational alerts only; no marketing, and text replies cannot place, approve, or cancel trades. Terms: https://hinsonben.github.io/twilio-sms-compliance/terms.html. Privacy Policy (mobile numbers and SMS opt-in data are not sold, rented, or shared with third parties or affiliates for marketing): https://hinsonben.github.io/twilio-sms-compliance/privacy.html

### Sample messages

These match the text the application sends.

Operational alert:

```
Trader CoPilot: EXCEPTIONAL BUY
XYZ $3.42
Setup: +18% momentum
Volume: 4.2x avg
Risk: $7.50
Shares: 20
Stop: $3.06
Target: $3.78

Approve or cancel in Slack. Text replies cannot place trades.
Reply STOP to opt out.
```

HELP reply:

```
Trader CoPilot desk alerts for the account owner. Msg frequency varies. Msg & data rates may apply. Reply STOP to opt out. Help: hinsonben@gmail.com. Texts can request reports: positions, account, activity, journal, plans, schedule, health, opportunities, analyze. Trading and shutdown commands are Slack-only.
```

Do not publish a real personal mobile number or other sensitive information on these pages.
