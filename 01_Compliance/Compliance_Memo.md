# Compliance Memo — Texas Excess Proceeds / Surplus Funds Recovery

**Prepared:** August 31, 2026
**Not legal advice.** This is a plain-English summary of statutes found through public research,
meant to shape the business model before you spend money or contact anyone. Have a Texas
attorney confirm all of this — ideally one who already works excess-proceeds cases — before you
sign up a claimant or take a dollar.

## The single biggest constraint

Texas Tax Code §34.04(i): **"A person who is not an attorney may not charge a fee to obtain
excess proceeds for an owner."** Attorneys who do this work are capped at 25% of the amount
recovered or $1,000, whichever is less — and that cap covers the *whole* engagement (research,
petition drafting, consultation — no stacking extra fees on top).

This applies specifically to **tax-sale excess proceeds held by a county district clerk** — the
exact category Harris County calls "excess proceeds," sitting in the court registry. Practically:
you (as a non-attorney) cannot legally charge a claimant a percentage or flat fee to help them
get *this specific* type of money back. A Harris County judge's own case-management rules (found
in research) require any attorney filing these petitions to certify in writing that they were
hired directly by the client, not through a third-party assignee — which also closes off a
"finder refers to attorney for a cut" arrangement in the way it's often imagined.

Separately, Texas Occupations Code §1702.104 (Private Security Act) treats **locating owners of
unclaimed/abandoned property through anything beyond public-record review** as regulated
investigative work, requiring a Class A or Class C Investigations Company license from Texas
DPS's Private Security Bureau. Straight public-records lookups are exempt; skip-tracing,
database searches, and similar owner-location work generally are not.

For the *separate* bucket of general unclaimed property (Comptroller-held funds via
ClaimItTexas.gov, not court-registry excess proceeds), Property Code §74.507 does let a
non-attorney finder charge up to 10% — but still requires the DPS investigations license, a
sales tax permit, and a written agreement meeting specific disclosure requirements
(§74.507(c)).

## What this means for the business model

The idea as first described — build a system that finds Harris County excess-proceeds cases,
locates the owners, and takes a cut of what they recover — runs directly into §34.04(i) as a
non-attorney. Three realistic paths, roughly in order of how directly they match the original
idea:

1. **Attorney-led model.** You (or a co-founder) become the licensed attorney, or you bring one
on as an owner/employee — not an independent referral relationship, since fee-splitting between
a lawyer and a non-lawyer for a referral is generally barred under the Texas Disciplinary Rules
of Professional Conduct (Rule 5.04). The business becomes the operations/research/tech engine
behind an actual law practice, with the attorney's name on every petition and every fee capped
at 25%/$1,000 by statute.
2. **Data & software model.** Sell access to the researched, verified case list itself — a flat
subscription or per-record fee, paid regardless of outcome, to attorneys, title companies, or
claimants who then handle their own petition (or hire their own counsel). This sidesteps
"charging a fee *to obtain* excess proceeds," but likely still needs the DPS investigations
license the moment you're doing more than reading public records to attach identifying info to a
name (skip tracing, database lookups, etc.) — confirm the exact line with counsel.
3. **General unclaimed-property locator model.** Pivot away from court-registry excess proceeds
entirely and build the DPS-licensed, 10%-fee finder business for Comptroller-held unclaimed
property instead. Different statute, different (still real) licensing bar, no $1,000 cap.

None of these are "pick one and go" — they need a licensed Texas attorney's sign-off before any
outreach happens. I can build out any of the three; I'd lean toward starting with **Option 2**
because it's buildable immediately without a license (pure research/data product) and keeps
Options 1 and 3 open as the license/attorney relationship comes together.

## New: listing attorneys on the site for claimants to contact

Texas Occupations Code Chapter 952 (the "Lawyer Referral Service Quality Assurance Act")
requires anyone who **operates a lawyer referral service** — defined broadly as a person or
service that "refers potential clients to lawyers," regardless of what you call it — to hold a
state certificate. The catch: **certificate applicants must be a governmental entity or
nonprofit operating primarily for the public's benefit.** A for-profit LLC generally cannot
qualify, which closes off an active "referral/matching" model outright.

There's a real distinction, though, between a *referral service* (matching, screening, or
recommending a specific lawyer to a specific person) and a plain *advertising directory* (a
public list where attorneys pay a flat fee to appear, and visitors browse and contact whoever
they choose, with no matching or recommendation from you). The latter is much closer to Yellow
Pages/Avvo-style attorney advertising and doesn't obviously trigger Chapter 952 — but State Bar
ethics commentary defines an LRS as "any organization that holds itself out to the public as a
lawyer referral service," so the line depends on how the feature actually behaves (self-serve
static listing vs. anything that looks like matching), not just what you call it.

**Practical read:** build it as a static, self-serve directory — attorneys apply and pay to be
listed, you don't rank, match, or recommend one over another, and the page doesn't use the word
"referral." Still get a Texas attorney to bless the exact page before it goes live with real
attorney listings, since this is a licensing question with real teeth (Chapter 952 violations,
plus State Bar advertising rules 7.01–7.07, which govern how lawyers themselves may be listed).

## Other things a Texas attorney should confirm before launch
- Whether solicitation of Harris County claimants is restricted by timing (e.g., barred until
some period after the certified-mail notice under Tax Code §34.03) or by consumer-protection
rules (DTPA) given how often these claimants are in financial distress.
- Entity choice (LLC is the default assumption below) and whether a professional entity structure
is required given the licensing questions above.
- Data handling: names, addresses, and case amounts pulled from court and county records are
public record, but building a marketing list from them and contacting people directly can still
trigger telemarketing/mail-solicitation rules — check TCPA/CAN-SPAM equivalents if outreach is by
phone, text, or email rather than mail.

## Sources reviewed
- Tex. Tax Code §34.03, §34.04 (excess proceeds, notice, fee cap, filing deadline)
- Tex. Prop. Code Ch. 74, esp. §74.507 (finder fee cap), §74.509 (handling fee)
- Tex. Occ. Code §1702.104 (Private Security Act — investigations company license)
- Harris County (Judge Lockett, Tax Master) case-management rules on excess-proceeds petitions
- DPS Private Security Bureau guidance on "heir-finders" (Feb. 2018)
