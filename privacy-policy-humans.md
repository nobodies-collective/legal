# Humans Platform — Privacy Notice

> **Intended font:** Space Grotesk (body), RocknRoll One (headings) — Mexzungu Standard
> **Status:** DRAFT — v1
> **Date:** 2026-03-31
> **Platform:** humans.nobodies.team
> **Data controller:** Nobodies Collective Association, CIF G26726299
> **Contact:** privacy@nobodies.team

---

## Why does this exist separately from the NCA Privacy Policy?

Because the humans platform collects data that goes beyond what the general NCA Privacy Policy covers. When you create an account, sign up for shifts, apply for membership tiers, or manage a camp — that all lives on this platform. This notice explains exactly what the platform does with your data.

This document works alongside the **NCA Privacy Policy** (the general one covering all NCA activities). If you're looking for how NCA handles ticket sales, artist waivers, or association governance broadly, that's the general policy. This one is specifically about what happens when you use humans.nobodies.team.

---

## What happens when I create an account?

You sign in with your Google account. We receive your name and email address from Google — that's it. Google doesn't give us your password, and we don't ask for one.

Once you're in, you complete a profile. Here's what we collect and why:

**Your profile basics** — name, birthday (month and day only — we don't ask for the year), and a profile picture if you choose to upload one. We use these to personalise your experience and help other humans recognise you.

**Contact fields** — phone, Signal, Telegram, WhatsApp, Discord, or custom fields. These are entirely optional, and you control who sees each one:

- *Board only* — just the Board
- *Coordinators and Board* — team coordinators plus the Board
- *My teams* — humans who share a team with you
- *All active profiles* — everyone with an active account

You set the visibility per field. You can change it anytime.

**Your email addresses** — your login email, any verified additional emails, and which one you want notifications sent to. If you're provisioned a @nobodies.team workspace account, that becomes your Google services email.

---

## What do you know about me as a volunteer?

When you complete your profile and consent to the required legal documents, a Consent Coordinator reviews your consent to make sure everything's in order. Once cleared, you're added to the Volunteers team and you get full access.

For each event, you may fill out a **volunteer event profile** with:
- Skills and experience you want to share
- Dietary requirements
- **Medical information** relevant to your participation

That medical data is special. Under GDPR, it's "special category data" (Article 9) and we only process it because you've given explicit consent. It's used solely to keep you safe at the event. Only authorised coordinators and the Board can see it. It's deleted after the event unless you tell us to keep it for future events.

---

## What about shift signups and availability?

If you sign up for volunteer shifts, we record which shifts you chose, your confirmation status, and your general availability for each event period (build, event, strike). Coordinators use this to plan staffing. It's straightforward contract performance — you volunteered, we need to organise the work.

---

## What if I apply for Colaborador or Asociado?

Colaborador and Asociado are governance tiers that require a Board vote. When you apply, we collect:
- Your motivation statement (up to 4,000 characters)
- Optional additional information
- The language you submitted in

Board members vote individually on your application. Here's the important bit: **individual votes are deleted after the decision is finalised.** Only the collective decision note, the meeting date, and the outcome (approved/rejected) are retained. This is deliberate data minimisation — we don't keep a permanent record of who voted which way.

If approved, your tier has a 2-year term (expiring December 31 of the next odd year). We'll remind you 90 days before expiry.

---

## How does consent tracking work?

Every legal document you sign on the platform creates an immutable consent record. That record captures:
- When you consented (timestamp)
- Your IP address
- Your browser/device (user agent)
- A cryptographic hash of the exact document content you agreed to
- Confirmation that you actively checked the consent box

These records **cannot be modified or deleted** — not by us, not by anyone. Database triggers physically prevent it. This protects both you and us: you have proof of exactly what you agreed to, and we have proof that you agreed.

When a legal document is updated and requires re-consent, you'll be notified by email. Each document has its own grace period (default 7 days) to review and re-sign. Your original consent stays in the audit trail — it's never overwritten.

---

## Will you send me emails I didn't ask for?

You control this. The platform has four communication categories, and you manage them at `/Profile/Notifications`:

**System messages** — account notifications, consent reminders, security alerts. Always on. You can't turn these off because they're necessary to run your account. We keep them minimal.

**Event operations** — shift changes, schedule updates, team additions, coordinator digests. On by default. You can turn them off, but you might miss your shift getting moved.

**Community updates** — community news, facilitated messages from coordinators. **Off by default.** You opt in if you want them.

**Marketing** — campaign codes, promotions. **Off by default.** You opt in if you want them. Every marketing email has an unsubscribe link. You can also unsubscribe with one click directly from your email client (we support RFC 8058) — no login required.

We will never pre-tick a marketing box for you. We will never send promotional content through System or Event Operations channels.

---

## What about camps?

If you register or lead a camp, we collect:
- Camp name, description, vibes, and community info
- Contact details for the camp lead
- Placement preferences (sound zone, electrical grid, space size)
- Season-specific info (kids policy, adult playspace policy, performance space)
- Images you upload

Camp leads are identified by name. Historical camp names are tracked if a camp is renamed.

---

## Do you connect my account to external services?

Yes, in specific ways:

**Google Workspace** — if you're provisioned a @nobodies.team account, the platform manages your access to Shared Drive folders and Google Groups based on your team memberships. When you join or leave a team, your Drive and Groups access is synced automatically. Only Shared Drive resources are managed — we never touch your personal Google Drive.

**Ticket vendor** — if you purchased a ticket through our ticketing provider, your order is synced to the platform and matched to your account by email address. This links your ticket to your profile so coordinators know you have valid access. Stripe payment metadata (payment method, fees) is imported for financial reporting but your card details never touch our system.

**GitHub** — legal documents are synced from a GitHub repository. This is a system integration, not a personal data flow. Your account data never goes to GitHub.

---

## Who else sees my data?

- **Google** — OAuth authentication and Workspace provisioning (Drive, Groups)
- **Your ticketing provider** — we import order data; nothing flows back
- **Stripe** — payment processing for tickets (via the ticketing vendor, not directly)
- **Your email provider** — we send transactional emails via SMTP

We don't sell your data. We don't share it with advertisers. We don't use tracking analytics — the platform runs on essential cookies only (authentication and security).

---

## How long do you keep my data?

| Data | Retention |
|------|-----------|
| Profile, contact fields | As long as your account is active + 30 days after deletion |
| Consent records | Permanently (immutable audit trail) |
| Volunteer event profiles (including medical) | Deleted after the event unless you request otherwise |
| Shift signups and availability | Duration of the event + 1 year |
| Tier applications (approved/rejected) | Duration of membership + legal retention period |
| Board votes | **Deleted on decision finalisation** |
| Camp data | As long as the camp exists + 1 year after deactivation |
| Ticket order data | 5 years (Spanish tax law) |
| Audit logs | 5 years |
| Feedback reports | Until resolved + 1 year |
| Communication preferences | As long as your account is active |
| Email outbox messages | Cleaned up by scheduled job after delivery |

---

## What can I do about my data?

Everything GDPR gives you:

- **See it** — your profile page shows your data. For a full export, email privacy@nobodies.team.
- **Fix it** — edit your profile, contact fields, and preferences anytime.
- **Delete it** — request account deletion. We'll revoke your memberships, remove your personal data, and retain only what the law requires (consent records, tax-relevant ticket data). Deletion is logged as an audit event.
- **Restrict it** — ask us to pause processing while we sort out a dispute.
- **Take it with you** — request a machine-readable export of your data.
- **Object** — push back on any processing based on legitimate interest.
- **Change your mind** — withdraw consent anytime without affecting anything we did before.

**How:** Email **privacy@nobodies.team**, or use the platform's built-in profile management. We respond within 30 days.

**Not satisfied?** Complain to the Agencia Española de Protección de Datos (AEPD) at [www.aepd.es](https://www.aepd.es).

---

## Do you use cookies?

Only essential ones — authentication and security. No tracking. No analytics cookies. No third-party cookies. When you visit the site, you'll see a cookie notice confirming this.

---

## Who's responsible?

**Data controller:**
Nobodies Collective Association
CIF: G26726299
Glorieta de Bilbao 1, 3.° Derecha, 28004 Madrid, Spain

**Data protection contact:** privacy@nobodies.team

**Platform maintainer:** Peter Drier (Treasurer, NCA Board)

---

## Important Note

This Privacy Notice is part of the **Elsewhere Participation Framework**, which includes:

1. Ticket Terms & Conditions
2. Refund Policy
3. Participant Agreement
4. Public Health & Safety Policy
5. Code of Conduct
6. Ticketing Privacy Notice
7. Media & Image Policy
8. Artist Installation & Grant Agreement
9. NCA Privacy Policy (General)
10. **This document — Humans Platform Privacy Notice**

All documents are available on the event website and on request from the Association.
