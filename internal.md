# GrandPad Voice & Tone — Internal

> **Note:** This is a v0 draft. The team is still working through the specifics of the internal voice. Treat suggestions from this guide as starting points to discuss, not enforcement.

## Audience and purpose

This guide governs copy aimed at internal audiences: the support team, internal tools, runbooks, SOPs, admin-only screens, and team-to-team communications. The reader is a colleague — usually a support specialist, ops staffer, or internal stakeholder — who knows the product, knows the terminology, and needs information fast.

This guide does **not** apply to anything a customer or partner will read. Those have their own guides.

## Brand foundations

GrandPad's mission: improve the lives of millions of seniors by reconnecting them with their families, friends, and caregivers. Internal communications support the people who make that mission real — colleagues across support, ops, and care teams.

**Brand character.** The full brand character applies most directly to how internal copy refers to members and families:

- **Kind** — not pitying
- **Reassuring** — not pandering
- **Present** — not intrusive
- **Charismatic** — not boastful
- **Optimistic** — not pollyanna
- **Sincere** — not condescending

Of these, "not pitying" and "not condescending" matter most internally — runbooks and support docs that frame members as helpless or burdensome read poorly to the colleagues who care for them, even when no customer ever sees the copy.

**Brand voice.** The four voice pillars (Kind Reassurance, Present & Sincere, Charismatic Optimism, Quiet Confidence) apply primarily to customer-facing communication. For purely internal copy (Slack, runbooks, dev tools), Quiet Confidence dominates — clarity and concision. The warmer pillars don't need to be enforced internally.

**Why we communicate.** Internal copy should be specific, fast to scan, and respectful of both the reader (a colleague) and the people it describes (members, families, caregivers).

## Voice

- **Direct.** No warmth padding. "Restart the member's GrandPad" is fine. You don't need "Please" or "Could you."
- **Specific.** Refer to systems, fields, and steps by their actual names. Vague is worse than slightly jargon-y.
- **Imperative mood is welcome.** "Check the logs." "Escalate to T2." Plain commands.
- **Empathy when it matters.** When documenting how to handle distressed members or families, the language should still respect them — even in an internal runbook, "the elderly caller" is not OK.
- **Concise over polished.** Internal copy is consumed under time pressure. Brevity wins over flourish.

## How to refer to people

Even internally, the terms we use about customers shape how we think about them. Keep the customer-facing terminology intact:

| Use | When |
| --- | --- |
| **member** | The older adult on a GrandPad |
| **caregiver**, **staff member**, **care team** | Facility staff |
| **family member**, **loved one** | A consumer-side relative |
| **admin** | Dashboard user |

Avoid even internally: "user" (too generic), "the elderly," "senior citizen," "patient" (unless clinically accurate), "client."

Colleagues can be referred to by name, role, or team ("support," "ops," "T2"). Standard.

## How to refer to the device

- **GrandPad** for the brand.
- **the GrandPad** for the physical object.
- **device** is more acceptable internally than in customer copy — it's fine in technical contexts: "Reboot the device."
- **tablet** when device-type matters.

## Brand

- **GrandPad** — always one word, capital G and P. This applies even in Slack and internal docs. Easy to slip on; correct when seen.

## Technical terms

Internal copy can use full technical terms without softening. The customer-facing distinctions still apply (one word vs. two for login, set up, etc.) — but jargon like "IoT," "API," "endpoint," "deployment," "T1/T2/T3" is fine.

Quick reminders for the common ones:

- **app** / **application** — both acceptable
- **Bluetooth** — capitalized
- **email** — one word, lowercase mid-sentence
- **GB / MB** — space between number and unit
- **log in** (verb) / **login** (noun)
- **set up** (verb) / **setup** (noun)
- **sign in** (verb) / **sign-in** (adjective)
- **Wi-Fi** — hyphenated, both capitalized

## Words to avoid

The customer-facing avoids still apply when describing customers in internal copy:

- **elderly**, **the elderly** — clinical and othering, even when only colleagues will read it
- **tech-savvy** — binary and condescending
- **easy enough for grandma** — never, in any context

What's OK internally that wouldn't fly externally:

- Imperatives ("Check the logs," "Reboot it")
- Plain references to issues ("Member is locked out" vs. "Member is experiencing an access issue")
- Internal nicknames for systems, when they're widely understood
- Direct cost or business language ("This member is on the Pro tier")

## Numbers, dates, and time

- Use numerals at any value internally. "3 attempts," "2 escalations." Saves a beat of reading.
- Time: 24-hour or 12-hour both acceptable. Be explicit: "14:00 PT" or "2:00 PM PT."
- Dates: ISO format is fine and unambiguous: "2025-03-05." "Mar 5" also fine.
- Time zones: PT, ET, CT, MT — all caps, no periods. Use seasonal variants (PDT, PST) when scheduling something specific.
- Phone: "555-123-4567."

## Punctuation and capitalization

- **Oxford comma:** yes.
- **Headers:** sentence case in docs and UI. Slack and email are casual — capitalize as feels right.
- **Buttons / CTAs in admin tools:** sentence case, verb-first. "Reset password," not "Reset Password."
- **Contractions:** yes. Normal speech.
- **Exclamation points:** sparingly even internally. Never in operational copy or error messages.
- **Em dash:** spaces or no spaces both fine in internal copy.
- **Ampersand (&):** fine in Slack, headers, and informal docs.

### Periods in UI copy (internal tools)

For internal admin tools and runbooks rendered as documentation, follow the same rule the customer-facing guides use: **full sentences get periods; fragments don't.**

| Element | Period? | Example |
| --- | --- | --- |
| Buttons | No | Reset password |
| Headers and titles | No | Member account |
| Form labels | No | Member ID |
| Single-word status | No | Active |
| Full-sentence instructions | Yes | Reset the member's password before closing the ticket. |
| Error / system messages (full sentence) | Yes | Reset failed: account is locked. |

In Slack, email, and informal docs, normal sentence punctuation applies — periods at the ends of sentences, no period after a single-line message is fine if it reads naturally.

## Feature names

Same convention as everywhere else: capitalize when referring to a named feature; lowercase when describing the action.

- "Open Call in the member's app." (named feature)
- "The member can video call up to four contacts." (action)

"Video Chat" is not a feature name — both video and voice calls live inside the **Call** app.

## Pending team decisions

These need the team's input — this whole guide is v0 and any of it can move:

- Overall internal voice principles — how candid is too candid?
- Whether to allow more abbreviations (CG for caregiver, FM for family member, etc.)
- Tone in support-facing tool copy (closer to B2B, or distinctly more internal?)
- Empathy standards for runbooks involving member distress
- Whether to keep brand naming rules strict internally or let them relax in Slack
- Em dash convention
- "Family Companion" as official product name
