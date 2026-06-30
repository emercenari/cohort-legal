---
title: Privacy Policy
permalink: /privacy/
---

> ⚠️ **DRAFT — reviewed by Claude (AI), not by licensed legal counsel.** Have a licensed attorney (and, for EU/UK users, a privacy specialist) review before public launch. Items flagged *[confirm]* need a human decision or a fact you must supply.

# Cohort — Privacy Policy

**Effective date: June 30, 2026**

Cohort ("Cohort," "we," "us," or "our") is a relationship-management app that helps you remember and stay in touch with the people you care about. This Privacy Policy explains what we collect, how we use it, who we share it with, and the choices and rights you have.

Questions or requests: **emercenari@joinbuo.com**.

---

## 1. Who we are

Cohort is operated by **Bodhi Technologies, Inc.** ("controller" for GDPR purposes). The app is currently distributed for iOS. *[confirm: add a business mailing address — several laws (incl. CCPA) expect one.]*

## 2. Information we collect

We collect only what we need to make the product work.

**You give us directly:**
- **Account information** — your name and email address (or the private-relay email Apple provides if you sign in with Apple).
- **Contacts you add** — names, roles, companies, email addresses, phone numbers, birthdays, photos, notes, and any other details you enter about people in your network.
- **Notes and interactions** — notes you write, touchpoints you log, and sections/labels you create.
- **Messages you draft** — the prompts you give the in-app Concierge and the drafts it returns.

**From your device, only with your permission:**
- **Apple Contacts** — if you grant Contacts access, we read the contacts you choose to import so you can add people without retyping them. We do **not** read your photos, calendar, messages, or notes.
- **Push token** — if you enable notifications, we store a push token so we can send you reminders.

**Automatically:**
- **Basic technical data** — device platform and app version, and the timing of certain events (e.g., when a device last checked in), used to operate and debug the Service.

We do **not** collect precise geolocation, and we do **not** use advertising trackers (see Section 8).

## 3. Legal bases for processing (EU/UK users)

Where the GDPR or UK GDPR applies, we rely on these legal bases:
- **Performance of a contract** — to create your account and provide the Service you ask for (storing your contacts, generating drafts you request).
- **Legitimate interests** — to secure the Service, prevent abuse, debug, and improve reliability, balanced against your rights.
- **Consent** — for device permissions you grant (Contacts, Notifications) and for optional features; you can withdraw consent at any time (Section 9) without affecting prior processing.
- **Legal obligation** — to comply with applicable law.

## 4. Where your data lives

Your account and the data you enter (contacts, notes, interactions, sections, drafts, push tokens, preferences) are stored in our cloud database hosted by **Supabase, in the United States**. Data is protected by row-level security so that each account can access only its own data.

## 5. Artificial intelligence (AI) features

Cohort uses AI to help you draft messages.
- When you ask the Concierge to draft a message, we send **relevant context about the person you are messaging** — such as their name, role, company, your notes, and recent interactions — together with your prompt to **OpenAI** (model `gpt-4o-mini`) to generate the draft.
- Per OpenAI's API data-usage policy, data submitted through the API is **not used to train OpenAI's models** by default. We make no further guarantees about OpenAI's processing beyond that policy.
- We do **not** use AI to make decisions that produce legal or similarly significant effects about you. AI-generated drafts are suggestions; you decide what, if anything, to send.
- If you do not want your contact context sent to OpenAI, do not use the Concierge drafting feature.

## 6. Service providers / sub-processors we share data with

We do **not sell** your personal information, and we do **not share** it for advertising or cross-context behavioral advertising. We share data only with service providers ("sub-processors") that help us run Cohort, under contracts that limit their use of the data to providing services to us:

| Provider | Purpose | Data shared |
|---|---|---|
| **Supabase** (US) | Database, authentication, hosting | Your account and app data |
| **OpenAI** (US) | AI message drafting | Context about the contact you're messaging + your prompt |
| **Apple** (US) | Push notifications (APNs); App Store payments | Push token + notification content; subscription/purchase data handled by Apple |
| **Expo** (US) | Build and push-delivery infrastructure | Push token + delivery metadata |

We may also disclose data if required by law, to enforce our Terms, or to protect rights, safety, and security. We may update this list as our providers change; contact us for the current list.

## 7. How we use your data

- To provide and operate the app (store your contacts, compute relationship insights, render your network).
- To generate AI message drafts you request.
- To send notifications you've enabled.
- To secure the Service, debug problems, and prevent abuse.
- To comply with legal obligations.

## 8. Cookies, tracking, and mobile identifiers

Cohort is a mobile app and uses **no advertising SDKs, no analytics cookies, and no cross-app tracking**. We do **not** access the iOS Advertising Identifier (IDFA) and do **not** present an App Tracking Transparency (ATT) prompt because we do not track you across apps or websites. We do not sell or share data for targeted advertising.

## 9. Your rights and choices

Every user, regardless of location, can:
- **Access / export** — export all your data as a JSON file from **Settings → Privacy & data → Export your cohort**.
- **Delete** — delete all your data from **Settings → Privacy & data → Delete all data** (permanent).
- **Manage permissions** — revoke Contacts or Notifications access anytime in iOS Settings.
- **Opt out of AI** — simply don't use the Concierge drafting feature.

**EU/UK users (GDPR/UK GDPR)** also have the rights to: **access**; **rectification** (correction); **erasure** ("right to be forgotten"); **restriction** of processing; **data portability**; **objection** to processing based on legitimate interests; **not to be subject to solely automated decisions** producing legal or similarly significant effects (we don't make such decisions); and to **withdraw consent**. You may also **lodge a complaint with your local data-protection authority**.

To exercise any right, use the in-app tools above or email **emercenari@joinbuo.com**. We will respond within the time required by law (generally within 30 days for GDPR, 45 days for CCPA, extendable as permitted). We will not discriminate against you for exercising your rights.

## 10. California privacy rights (CCPA/CPRA)

If you are a California resident, you have the rights to **know/access**, **delete**, **correct**, and **opt out of the sale or sharing** of your personal information, and to **limit the use of sensitive personal information**.

- **We do not sell or share personal information** (as those terms are defined under the CCPA/CPRA) and have not done so in the preceding 12 months. There is therefore nothing to opt out of, but you may still contact us.
- **Categories of personal information we collect:** identifiers (name, email), customer records (contacts/notes you enter), and internet/device activity (app/diagnostic data). Some information you enter (e.g., notes) could constitute **sensitive personal information**; we use it only to provide the Service and **not** to infer characteristics about you.
- **Sources & purposes** are described in Sections 2, 6, and 7.
- You may exercise these rights via the in-app tools or **emercenari@joinbuo.com**, and you may use an **authorized agent**. We will verify requests using your account.

## 11. Data retention

We keep your data for as long as your account is active. When you delete your data or account in-app, it is removed from our **active systems immediately** (account deletion cascades across all of your records). Residual copies in encrypted backups are purged on a rolling cycle, generally **within 30 days** *[confirm against your actual Supabase backup retention]*. We may retain limited records longer where required by law or to resolve disputes and enforce agreements.

## 12. Security

We use row-level security, encrypted transport (HTTPS/TLS), and provider-managed encryption at rest. On your device, authentication tokens are stored in the iOS **Keychain**. No system is perfectly secure, but we work to protect your data and limit access to it.

## 13. Data breach notification

If we become aware of a breach affecting your personal data, we will notify affected users and regulators **as required by applicable law and without undue delay** (for example, within 72 hours of becoming aware where GDPR applies, and as required by U.S. state breach-notification laws).

## 14. Children

Cohort is **not directed to children** and is intended for users **18 and older**. We do not knowingly collect personal information from children under 13 (or under the minimum age in your jurisdiction). If we learn we have collected such information, we will delete it. A parent or guardian who believes a child has provided us data may contact **emercenari@joinbuo.com**.

## 15. International data transfers

We process data in the **United States**. If you access Cohort from the EU/UK or elsewhere, your data is transferred to and processed in the US. Where required, such transfers rely on appropriate safeguards, including the **Standard Contractual Clauses (SCCs)** (and the UK Addendum) with our service providers. By using the Service, you understand your data will be processed in the US, which may have different data-protection laws than your country. *[confirm SCCs are in place with each sub-processor.]*

## 16. Changes to this policy

We may update this policy. We will revise the "Effective date" above and, for material changes, provide in-app or email notice. Continued use after an update means you accept the revised policy.

## 17. Contact

Privacy questions or requests: **emercenari@joinbuo.com**. EU/UK users may also contact their local data-protection authority. *[confirm: appoint an EU/UK representative only if Article 27 applies to you — generally not required for small, occasional processing.]*

---

*Maintained at the Cohort legal repository and linked from within the app. DRAFT — reviewed by Claude (AI); have licensed counsel review before public launch.*
