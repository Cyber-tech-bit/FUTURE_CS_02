# Phishing Email Detection & Awareness System

![Safe vs Suspicious vs Phishing Email Comparison](screenshots/phishing_email_examples.png)

## Future Interns Cyber Security Internship

**Prepared by:** Keerit Kapoor
**Task:** Task 2 – Phishing Email Detection & Awareness System
**Date:** 20 June 2026

---

## Project Overview

This project demonstrates how to identify and classify email-based threats by comparing simulated examples of:

* Safe emails
* Suspicious emails
* Phishing emails

The aim is to improve user awareness of common phishing indicators, reduce the risk of credential theft, and encourage safe email-handling habits.

> **Important:** All email examples in this project are simulated for educational purposes. No real accounts, active links, passwords, or personal credentials were used.

---

## Objective

* Identify common phishing indicators in emails.
* Classify emails as Safe, Suspicious, or Phishing.
* Explain risks in simple, user-friendly language.
* Provide practical prevention and awareness guidance.

---

## Email Classification Summary

| Email Type                   | Classification | Main Indicators                                              |
| ---------------------------- | -------------- | ------------------------------------------------------------ |
| NorthStar order confirmation | Safe           | Clear sender domain, personalised message, no urgent request |
| Account verification message | Suspicious     | Lookalike domain, generic greeting, urgency                  |
| Payment warning message      | Phishing       | Fake domain, threatening language, suspicious payment link   |

---

## Key Phishing Indicators

### 1. Sender Address

Always check the complete sender address, not only the display name.

Example:

```text
orders@northstar.example
```

This is a simulated official-looking sender domain.

A suspicious sender may use a lookalike domain such as:

```text
support@northstar-security.example
```

---

### 2. Urgent or Threatening Language

Phishing emails often create panic using phrases such as:

* “Action required immediately”
* “Your account will be suspended”
* “Update your payment details now”
* “Verify within 24 hours”

Legitimate organisations usually provide clear information without pressuring users into immediate action.

---

### 3. Suspicious Links

Before opening a link:

* Hover over it to inspect the destination.
* Check whether the domain matches the organisation.
* Do not enter passwords, card details, or one-time codes through unexpected email links.
* Open the official website manually instead.

---

### 4. Generic Greetings

Messages beginning with:

```text
Dear Customer
```

or

```text
Dear User
```

may deserve extra caution, especially when combined with urgency, unknown senders, or payment requests.

---

## Evidence

### Simulated Email Comparison

![Simulated phishing email comparison](screenshots/phishing_email_examples.png)

The evidence image compares three simulated emails and explains why each was classified as Safe, Suspicious, or Phishing.

---

## Awareness and Prevention Guidelines

* Verify the complete sender email address.
* Do not trust urgent or threatening messages automatically.
* Hover over links before clicking.
* Never share passwords, OTPs, or payment details by email.
* Use multi-factor authentication where available.
* Access sensitive accounts through official apps, bookmarks, or manually typed URLs.
* Report suspicious emails to your organisation or email provider.

---

## Repository Structure

```text
FUTURE_CS_02/
│
├── README.md
│
└── screenshots/
    └── phishing_email_examples.png
```

---

## Skills Demonstrated

* Phishing email identification
* Sender-domain analysis
* Link-safety awareness
* Threat classification
* Cybersecurity awareness communication
* GitHub documentation

---

## Disclaimer

This repository was created for educational and internship-portfolio purposes only. All email examples, domains, messages, and links are fictional simulations created to demonstrate phishing-awareness techniques.
