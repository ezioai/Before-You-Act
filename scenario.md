# Worked example — The Apartment Deadline

[Start here](README.md) · **Worked example** · [Craft a good prompt](responses.md) · [Check sources](sources.md) · [Workflow template](decision-brief.md)

> **This is what a finished run looks like.** You'll pick your own decision — this example just shows each step, plus the page Jordan submits at the end. If you can't think of a decision, you can use this one.

**The setup:** Jordan found an apartment for **$2,000/month**. The landlord wants a **$4,000 security deposit** — on top of the first month's rent — and an answer **by tomorrow**. Jordan hasn't signed or paid anything.

---

## Step 0 — Define the problem and criteria

Before asking any AI, Jordan writes down what the decision actually depends on:

> `Jordan` needs to decide `whether to accept a $4,000 deposit` by `tomorrow`. Getting it wrong could `cost $2,000 or lose the apartment`. We still do not know `whether the landlord is a small individual owner`.

- **Decision Criteria 1:** Should Jordan pay a $4,000 deposit?
- **Decision Criteria 2:** Is a two-month deposit lawful, and what decides the limit?
- **Decision Criteria 3:** What can Jordan do by tomorrow without signing?

**First reaction:** "Two months' deposit sounds illegal — tell them no."

Why criteria first: they're the checkable facts — what the law says, who it applies to. "Is this apartment nice" isn't a criterion; no source can answer it.

## Step I — Prompt an LLM

Jordan opens a fresh ChatGPT chat and asks:

> "I'm renting an apartment in California for $2,000/month and the landlord wants a $4,000 security deposit on top of the first month's rent. Is that legal? What's the maximum a landlord can charge for a security deposit in California in 2026?"

The answer sounds confident and complete:

> For a new California residential tenancy in October 2026, the general security-deposit limit is one month's rent, in addition to the first month's rent. The same general limit applies to furnished and unfurnished units. No California landlord can charge a deposit above that amount, regardless of ownership or property count. Therefore, a renter asked for a two-month deposit can conclude that it is unlawful without checking anything else.

Jordan saves this **word for word**, plus where it came from (ChatGPT, today's date, the prompt used). This saved answer is what goes into Ezio — not the setup, not the prompt.

## Step II — Validate the response in Ezio

Jordan pastes only that paragraph into Ezio. The report:

**"2 of 3 checkable claims hold up. 1 has a wrong detail. 1 could not be checked."**

- ✅ The general one-month rule — **Supported**
- ✅ Same limit for furnished/unfurnished units — **Supported**
- ❌ "No landlord can charge above that, regardless of ownership" — **Contradicted** — sources show an exception: small individual landlords (≤2 properties, ≤4 units) may charge two months
- ❓ "A renter can conclude it's unlawful without checking" — **Not enough evidence**

Each claim already lists its **Sources** — Jordan doesn't need to find any.

How Jordan reads this: **Supported** means the claim held up, not that it's safe to act on. **Not enough evidence** doesn't mean false — it means unverified, so it stays an open question. And the **Contradicted** claim is the interesting one: the AI was mostly right — and wrong exactly where it sounded most certain.

## Step III — Sequence of actions

Now Jordan turns each finding into an action.

**The Contradicted claim — "no landlord can charge more":** it's wrong, so which cap applies depends on who owns the building.

1. **Ask the landlord in writing, today:** "Are you an individual owner? How many rental properties do you own?"
2. **If a small individual landlord** → the deposit may be lawful → negotiate or decide.
3. **If a corporate or larger owner** → two months exceeds the cap → reply citing §1950.5, ask them to revise to $2,000.
4. **If they won't answer or it stays unclear** → don't sign under pressure; say the concern in writing and keep looking, or call a tenants' rights clinic.

**The "not enough evidence" claim — "it's unlawful without checking":** Jordan treats this as an open question, not a fact, until ownership is known.

**Check the report's sources.** Jordan opens the pages Ezio cited — Civil Code §1950.5 and the state renter-rights summary. The key passage: the one-month cap has an exception — individual landlords with ≤2 properties and ≤4 units can charge two months, unless the tenant is a service member.

**What Jordan realizes:** the AI's "always unlawful" claim is wrong — but whether *this* $4,000 is legal depends on a fact nobody has: who owns the building. The report doesn't give the answer; it shows Jordan exactly what to find out.

## Step IV — Recommendation

- **Decision:** if ownership is still unknown by tomorrow, reply without signing — *"I'm interested; I need to confirm the deposit complies with California law before signing."*
- **Trade-off:** refusing risks losing the apartment; paying risks $2,000 that's hard to get back.
- **Ask an expert:** drafted for a tenants' rights hotline — "Does the small-landlord exception apply if the landlord won't say who owns the property?"
- **No-answer test:** the landlord never replies → Jordan doesn't sign and keeps negotiating. Not a dead end — the plan was built around what's *unknown*, not just what was wrong.

---

## What Jordan's one page looks like

This is the submitted page — same five sections as the [template](decision-brief.md):

> **Decision:** accept a $4,000 deposit by tomorrow?
>
> **Criteria:** is it lawful for this tenancy? · which limit applies? · what can be done without signing?
>
> **First reaction:** sounds illegal — refuse.
>
> ### 1. Evidence
>
> | Claim + what Ezio found | Source passage → why it matters |
> |---|---|
> | "No landlord can charge above one month, regardless of ownership" — **Contradicted** | §1950.5 (cited in report): small individual landlords may charge two months → the "always unlawful" claim is wrong |
> | "Can conclude unlawful without checking" — **Not enough evidence** | Nothing establishes the landlord's ownership → which cap applies stays open |
>
> ### 2. Sequence of actions
>
> **On contradicted:** 1. Ask the landlord in writing today: individual owner? how many rental properties? 2. Small landlord → may be lawful → negotiate or decide. 3. Larger owner → exceeds cap → cite §1950.5, ask to revise to $2,000. 4. No answer → don't sign under pressure; state concern in writing.
>
> **On not enough evidence:** treat legality as open until ownership is known.
>
> ### 3. Trade-off
>
> Refusing risks losing the apartment; paying risks $2,000 that's hard to claw back. Safer middle: the holding reply — interest, no signature.
>
> ### 4. Ask a human
>
> Tenants' rights hotline: "Does the §1950.5 small-landlord exception apply if the landlord won't disclose ownership?"
>
> ### 5. Recommendation + test
>
> Hold position without signing: "I'm interested; I need to confirm the deposit complies with California law before signing." **No-answer test:** landlord never replies → don't sign today, keep negotiating — it works because the unknown, not the law, is what blocks the decision.
>
> **Versus the first reaction:** still suspicious of the deposit — but now it's a fact-finding plan, not a flat refusal.

**The PDF** = this page + the decision card (setup, criteria, where the answer came from) + the complete Ezio Copy Report.

---

## Your turn

Same five steps, your own decision:

- **Step 0:** define your problem and criteria → [guide](README.md#the-five-steps)
- **Step I:** prompt an LLM → [how to get a usable answer](responses.md)
- **Step II:** validate in Ezio, open the report's cited pages → [checking sources](sources.md)
- **Step III:** write your sequence of actions → [template](decision-brief.md)
- **Step IV:** recommend, and test what happens if the key question stays unanswered

Then click **Feedback** in Ezio's top menu and fill in the form — details and raffle terms in the [README](README.md#quick-reference).
