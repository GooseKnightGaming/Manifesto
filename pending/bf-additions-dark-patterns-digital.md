# BRITAIN FORWARD
## POLICY ADDITION — Digital Consumer Protection: Dark Patterns & Advertising Standards
### For Integration into Platform v11

---

# THE ISSUE — DARK PATTERNS IN DIGITAL ADVERTISING

A dark pattern is a deliberately deceptive interface design intended to trick users into actions they did not choose and would not have chosen if given a genuine option.

They are not accidents. They are deliberate engineering decisions made to inflate engagement, click-through rates, and in-app purchases by exploiting rather than persuading users.

Britain Forward will make the most harmful dark patterns illegal.

---

## DIGITAL ADVERTISING — SPECIFIC REQUIREMENTS

### The Problem

Digital advertising — particularly in free mobile games, free apps, and ad-supported websites — routinely uses the following deliberately deceptive techniques:

**1. The Fake Exit Button**
An X or close button is displayed that appears to close the advert but does not — it opens the advertised product, triggers a download, or navigates away from what the user was doing. The button is cosmetically an exit but functionally a click-through.

**2. The Invisible or Absent Exit Button**
The exit button is not displayed at all during a countdown period — which is legitimate — but then either:
- Never appears, trapping the user
- Appears for a fraction of a second and disappears before it can be pressed
- Is rendered in a colour so close to the background that it is effectively invisible

**3. The Undersized Exit Button**
The exit button is present and genuine but is rendered at a size so small — typically 4-8 pixels on mobile — that a normal human finger cannot reliably tap only the button without also tapping the advert. This is not an oversight. The average adult fingertip covers approximately 57 pixels. A button smaller than 44x44 pixels is below the threshold recommended by every major platform's own design guidelines. Deliberately using smaller sizes is engineered misclick.

**4. The Adjacency Trap**
The exit button is positioned immediately adjacent to the advert's call-to-action link, store button, or click-through target — such that a user attempting to close the advert has a high probability of accidentally activating the advert instead. Again, not an accident.

**5. The Delayed Appearance Exploiting Inattention**
The exit button appears after a countdown but disappears again within 1-2 seconds if not pressed — such that a user who glanced away during the countdown misses the exit window and must wait for another opportunity or cannot exit at all.

**6. The False Countdown**
The countdown timer resets or extends when certain in-advert interactions occur — meaning an advert advertised as "15 seconds" can run for significantly longer through triggered extensions the user did not consent to.

---

## THE LEGAL REQUIREMENTS

### Minimum Standards for Skippable Digital Adverts

All digital adverts served to users in Britain, on any platform, in any application, on any device, where the advert includes a skip or close mechanism, must comply with the following:

**1. Exit Button Appearance — Timing:**
- Where an advert includes a mandatory viewing period (e.g. a 5-second or 15-second non-skippable period), the exit button must appear immediately and fully upon expiry of that period
- The exit button must remain continuously visible and functional until the user either closes the advert or the advert ends naturally
- Disappearing exit buttons are prohibited

**2. Exit Button — Authenticity:**
- The exit button must perform exactly the action it represents — closing the advert and returning the user to their previous activity
- An exit button that navigates the user to a store, opens a browser, initiates a download, or performs any action other than closing the advert is prohibited
- Cosmetic exit buttons with non-exit functionality are classified as fraudulent interface design

**3. Exit Button — Size:**
- Minimum interactive target size: 44x44 pixels (CSS pixels at standard density) on all touchscreen devices — consistent with Apple's Human Interface Guidelines, Google's Material Design Guidelines, and WCAG 2.1 accessibility standards
- The minimum size applies to the interactive touch target, not just the visible icon — a small icon surrounded by adequate invisible touch area is compliant; a small icon with no surrounding touch area is not
- Buttons below this minimum are prohibited in adverts served to users in Britain

**4. Exit Button — Positioning:**
- The exit button must be positioned with a minimum clearance of 20 pixels from any clickable advert element (call-to-action button, image link, store button)
- The exit button must be visually distinct from advert content — it must not be camouflaged, hidden in decorative elements, or rendered in colours that make it non-apparent against the background

**5. Countdown Timers — Accuracy:**
- Where a countdown timer is displayed, it must accurately represent the remaining non-skippable period
- Countdown timers that reset, extend, or pause as a result of user interaction with the advert (other than the user deliberately choosing to engage) are prohibited unless the user is clearly informed before the countdown begins that this will occur

**6. No Additional Barriers After Skip:**
- Once a user activates the exit button on a skippable advert, they must be returned to their previous activity within one second
- "Are you sure you want to skip?" prompts, additional countdown screens, or any other mechanism that delays the skip are prohibited

---

## ENFORCEMENT

**Who is liable:**

*Primary liability: the advertiser.* The company paying for the advert is responsible for ensuring the creative meets legal standards before it is served.

*Secondary liability: the platform.* App stores, games publishers, advertising networks, and platforms that serve adverts are responsible for:
- Having terms of service that require compliance with these standards
- Having technical mechanisms to prevent non-compliant adverts from being served
- Being liable where they knowingly serve non-compliant adverts or fail to act on reported violations

*No liability passes to the user.* A user who is deceived into clicking an advert through a dark pattern has not consented to the resulting action — any purchase, download, or subscription initiated through a deceptive click has no legal force and must be cancellable without penalty.

**Reporting mechanism:**
- In-app/in-browser reporting of non-compliant adverts — one-tap reporting built into compliant platforms
- Reports go to the Information Commissioner's Office (ICO) which gains new enforcement powers in this area
- Anonymous reporting permitted — platforms cannot retaliate against users who report violations

**Penalties:**
- First violation (per advert creative): formal warning and mandatory correction within 14 days
- Continued violation: fine per day the non-compliant advert continues to be served in Britain
- Systematic violation (pattern of deliberate non-compliance): substantial fine calculated as percentage of UK advertising revenue; named and shamed in ICO annual report
- Knowingly serving adverts with fraudulent exit buttons: treated as a consumer fraud matter, not just a technical violation — higher penalty tier

**ICO powers:**
- Power to require platforms to remove non-compliant adverts within 24 hours of a substantiated complaint
- Power to require advertising networks to delist advertisers with systematic violations
- Power to require app stores to remove apps that persistently host non-compliant adverts after warnings

---

## THE BROADER DARK PATTERNS LAW

The digital advertising rules above are the most immediately visible instance of a broader problem. Britain Forward will introduce a **Digital Dark Patterns Act** covering:

**In-App Purchases and Subscriptions:**
- Subscription sign-ups must be as easy to cancel as to initiate — same number of steps, same prominence, same ease
- "Free trial" sign-ups that require payment details must send a reminder before the trial ends and before the first charge
- In-app purchases in games rated for children or targeting children: additional restrictions; no pressure mechanics (countdown timers on purchases, "limited offer" false scarcity, social pressure — "your friends have this")

**Cookie and Privacy Consent:**
- "Accept all" and "Reject all" options must be presented with equal visual prominence — no dark background on reject, no multiple-step process to refuse when acceptance is one click
- Pre-ticked consent boxes: prohibited
- Consent walls (you cannot use this service unless you consent to tracking): prohibited for services where there is no genuine free alternative

**Confirmshaming:**
- Manipulative labelling of the "decline" option (e.g. "No thanks, I don't want to save money") designed to shame users into accepting — prohibited in commercial contexts

**Roach Motels:**
- Services that are easy to sign up for but deliberately difficult to cancel — non-obvious cancellation paths, phone-call-only cancellation where sign-up was online, multiple confirmation screens for cancellation — prohibited; cancellation must be as easy as sign-up

**Hidden Costs:**
- Prices shown during a purchase flow must include all mandatory costs — no adding fees, delivery charges, or service charges at the final step that were not visible at the start

**The principle throughout:** An interface design is a dark pattern if its effect is to cause users to take actions they would not have taken if given a clear, unobstructed, honest choice. Intent to deceive does not need to be proven — the effect is sufficient.

---

## WHERE THIS FITS IN THE PLATFORM

| Section | Addition |
|---|---|
| Pillar Two — 2.9 British Industry & Standards | Digital consumer protection; Dark Patterns Act |
| Pillar One — 1.8 Plain Language | Connection: dark patterns in consumer interfaces are the commercial equivalent of obfuscatory language in government communications — the same principle (honest, clear communication that serves the recipient rather than the sender) applies to both |
| New — Digital Rights section | Consider adding a standalone Digital Rights section to Pillar Two or Pillar Three, covering: dark patterns; data rights; algorithmic transparency; right to disconnect; broadband as public infrastructure (already in platform) |

---

## EVIDENCE BASE

The EU's Digital Services Act (2022) and Digital Markets Act (2022) include provisions against dark patterns. The UK's own Competition and Markets Authority has published guidance on harmful online choice architecture. The Behavioural Insights Team has documented the measurable effect of dark patterns on user decision-making.

This is not a fringe concern. The ICO's own research has found the majority of cookie consent mechanisms in Britain are non-compliant with existing GDPR requirements. The gap is not legislation — it is enforcement resource and political will.

Britain Forward provides both.

---

## PLAIN ENGLISH SUMMARY

*What this means for anyone who uses a phone or tablet:*

When you watch an advert in a free app:
- When the countdown ends, the X button must appear immediately and actually work
- The X button must be big enough to tap without accidentally opening the advert
- The X button must not be hidden, disguised, or placed right next to the advert link
- If you tap X, you go back to your game or app — not to a shop

If an app doesn't follow these rules, you can report it. The company behind the advert gets fined. The app can be removed from app stores if it keeps breaking the rules.

*Because your time and your attention belong to you — not to an advertiser.*

---

*Ready for integration into Platform v11.*
*The Digital Dark Patterns Act is a natural extension of the existing consumer standards policy.*
*Connects to: Plain Language Standard (same underlying principle); Right to Repair (same consumer rights philosophy); Digital Infrastructure (same digital policy space).*
