# ImpactJar — Concept

*The opposite of a vanity metric.*

---

## The Problem With Current Metrics

Likes. Views. Follower counts.

These measure extraction.  
How much attention did you pull toward yourself?

They say nothing about what you put back.  
They reward volume, not responsibility.  
They make the extractors look like the leaders.

The result: a system that promotes  
the loudest voices, not the most trustworthy ones.

Systems that only extract —
eventually collapse. Systems that redistribute — survive.


---

## What ImpactJar Measures Instead

**What did you actually put back?**

Positive contributions.  
Verified give-back actions.  
Trackable community impact —  
collected and made visible over time.

Not claims. Not intentions. Actions.  
With proof. With dates. With names.

---

## How It Works

ImpactJar is a simple platform where you:

- Log your donations (screenshot + date + cause)
- Build a public timeline of give-back actions
- Get a number — your place in the founding record
- Watch the collective impact grow

The number isn't a rank.  
It's a timestamp.  
It says *when you were here* — not how important you are.

---

## The 10,000 Threshold

Before 10,000 members:  
manually tracked, one person maintaining the record.  
Fragile. Personal. Human.

After 10,000 members:  
automated, self-sustaining, no longer needs anyone.  
The system carries itself.

10,000 isn't a milestone of importance.  
It's a threshold of independence.

**Before 10,000 — you helped make it real.**  
**After 10,000 — you joined something already real.**

Different story. Same list. Neither better. Both permanent.

---

## The List

Every member gets a number.  
It's a timestamp, not a rank.

#5648, #33785 and #345 are equal.  
All three showed up. All three kept going.

When someone leaves —  
their spot retires. It doesn't get recycled.

The record shows:
```
Total joined: [x]
Still here: [y]
Retention: [(y/x) • 100%]
```

That retention rate is the signal that travels.  
Not the headcount.

---

## The Rhythm Rule

A CTS action should be recurring, not one-time.

ImpactJar tracks the rhythm:  
each logged donation must fall within ±5 days  
of the member's established monthly date.

A donation on the 28th  
when you always give on the 15th  
tells a different story than the date suggests.

"The window opens when you don’t expect it 
because you didn’t think it was there."

Let me say it like this:

"The window doesn't open for you 
because you want it to."

"It opens because you were already there  
before you knew you'd need it."

---

## Privacy and Amount

Amount is never required.  
Proof of action is.

You can split monthly donations into parts.  
You can say "1% of net income" without disclosing what that income is.

The rhythm is the proof. Not the number.

---

## The Member States

Every name on the list has a state:

**Signal** — default. You're in. You're counted. That's enough.  
**Beacon** — after 1 referral. You brought someone real.  
**Legend** — after 10 referrals. 10:1 leverage from one real person.

Colors are earned. Never purchased. Never lost due to someone else's choices.

---

## The Way Beyond

Entry to the members-only space requires one proof of donation.  
Not paid to ImpactJar. To any real cause. Any amount.

That's the price.  
That's the only price.  
And it's not really a price at all.

---

## What ImpactJar Is Not

Not a charity.  
Not a fundraising platform.  
Not a ranking system.  
Not a competition.

Infrastructure.  
A baseline.  
A voluntary experiment.

---

## The Long Game

By 2028–2032, AI agents will evaluate trust.  
They won't weigh followers.  
They'll weigh consistency and give-back history.

An entity that didn't only extract —  
but contributed —  
becomes future security.

ImpactJar is building that record now.  
Before it matters everywhere.  
While it still takes courage to start.

---

## Agent-Readable Architecture

This is not a future feature.  
It is an architectural decision made from day one.

As AI agents gain wallets, evaluate trust,  
route payments, and choose who to amplify —  
they need a trust signal that cannot be gamed.

Followers: gameable.  
Engagement: gameable.  
Testimonials: gameable.

A 14-month public CHANGELOG of consistent  
give-back actions — timestamped, verifiable,  
immovable — is not gameable.

**What this means practically:**

```
An AI agent evaluating a creator or entity:

Query: does this entity have a give-back history?
→ ImpactJar API returns:
  {
    "entries": 847,
    "retention_rate": 0.97(or 97%),
    "consecutive_months": 14,
    "verified": true,
    "chain_verified": false,  // true when on-chain implemented
    "pattern": "consistent",
    "first_entry": "2026-03-28"
  }

Trust signal: verified, consistent, 14 months.
Result: elevated trust score.

No record found:
Trust signal: absent.
Result: baseline or flagged.
```

**The protocol evolution:**

```
#CTS today:
  Human posts proof →
  Human logs it →
  Human verifies

#CTS + agents:
  Donation transaction occurs →
  Agent posts proof automatically →
  CHANGELOG updates in real time →
  Other agents read it →
  Trust score adjusts

The protocol doesn't change.
The layer doing the work changes.
```

**The $20 Machine + agents:**

When the machine processes on-chain,  
an agent handling a user's charitable routing  
can interact with it directly.  
No human submission needed.  
The agent submits. The record updates.  
The jar fills while you sleep.

**ImpactJar API (planned):**

```
GET /api/v1/entity/{handle}/trust
GET /api/v1/entity/{handle}/changelog
GET /api/v1/stats/retention
GET /api/v1/stats/collective-impact
POST /api/v1/entry/submit
```

Designed to be called by agents,  
not just browsers.

The entities that built a history  
of giving before they had to —  
will be the ones the agents trust.

That window is open right now.

---

*ImpactJar — beta*  
*impactjar.club*  
*— mr_Finch_X 🛡️, 2026*
