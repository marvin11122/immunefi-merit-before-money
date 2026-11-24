# Evidence sealed. Gate exposed.

## Why nobody learns the math

“Nobody” is polemic, not a census. The point is that the pipeline rarely rewards deriving the inequality. It rewards routing the report, matching a known-issue label, choosing a severity, and closing the queue. Under those incentives, people learn the interface around the proof instead of the proof. Bias does not require a room full of villains; it can be manufactured by a workflow that trains reviewers to trust familiar categories before unfamiliar evidence.

That is how an institution breeds its own biased apes: not necessarily stupid individuals, but smart people performing a role that makes independent thought expensive and procedural reflex cheap. Then a self-described dumb drug user spends four years learning mathematics and brings Lean 4 to a question the pipeline should be able to inspect. The punchline is not that the researcher is a genius. It is that the supposedly unserious person did the formal work while the serious process put a tollbooth in front of anyone checking it.

## The evidence exists; the exploit details stay private.

An Ethena research package has been executed locally and is being withheld from this public repository. It contains two Lean formalizations, two Ethena fork tests, one USDtb fork test, and a written finding that records both the demonstrated contract behavior and the limits of the production-attack claim.

Observed verification results:

- Lean 4 proof: exit code **0**.
- Ethena Foundry fork suite: **2 passed, 0 failed**.
- USDtb Foundry fork test: **1 passed, 0 failed**.

These are the actual local results, not a claim that a bounty accepted the report. The PoCs exercise local forks; no live exploit or permissionless production path is claimed as established. The written finding explicitly records the unresolved API/order path and withdraws an earlier impact extrapolation. Evidence that preserves its own limitations is more useful than a larger number that does not survive scrutiny.

## Technical statement, sanitized

For natural numbers `n` and positive `d`, integer division satisfies:

```text
floor(n / d) = 0  iff  n < d
```

That is not equivalent to `n = 0`: a positive numerator can disappear in the quotient. Consequently, a zero-tolerance check that infers “no deviation” from a truncated zero quotient does not, by that fact alone, prove exact equality. The formal work proves this distinction and the corresponding exact-zero property of a cross-multiplied predicate. It does not prove that every accepted mathematical input is reachable through a production interface.

The local tests exercise the deployed contracts on forks and check the reported behavior under their test setup. The remaining production question is reachability through the documented order/API path; the private finding marks that limitation explicitly. This public synopsis intentionally omits the protocol-specific scaling factor, function and selector names, addresses, order fields, fixtures, role identities, and transaction recipe. It is enough to state the theorem; it is not a reproduction guide.

## Public commitments, private contents

The following SHA-256 commitments identify the exact artifacts privately held. They let a later authorized reviewer check that disclosed files match the versions committed to here. **Hashes prove file identity, not correctness**; the proof and tests themselves remain undisclosed.

| Artifact | SHA-256 |
|---|---|
| Formal proof A | `85891c7d71b0f04fcdaa7c2badbd65a8cc33d86a8d79f4fb1e7c81e35343a319` |
| Formal proof B | `9f4c3ede9c6960b0f546d8063c5f808836b30bc242dc5ae76457773f6064ae22` |
| Ethena fork test | `f0c9da3bddd8854a0a1717f9e1cfd97b35586abff3e1a5b2af251da9dfc69c87` |
| USDtb fork test | `57433fd571509ed56e00762cf17419d541899bc8c721cf396b870882967cd4bf` |
| Written finding | `2165901c91f869b4773c6f91591dcef3effb636956fa7de6228d1c5dc91cab1c` |

No source, addresses, parameters, exploit steps, or PoC code are published here.

## The gate is the argument

On 24 November 2026, the authenticated Immunefi Studio page displayed **invite-only**. Its invite flow required a researcher to be ready to buy **300 credits (300 USDC) within 24 hours of receiving an invitation**. No invitation was requested; no credits were bought.

That is not a technical review. It is a willingness-to-pay test placed before access to review. A fee is not a rebuttal. An invitation is not triage. A purchase commitment cannot make a theorem more or less true. **The paywall is not the proof-checker; it is the part that prevents the proof-checker from being reached.**

The institutional comedy is precise: the evidence is machine-checkable, its scope limits are written down, and its hashes are public. The details remain sealed. The next move is not ours to simulate. If the response is a technical refutation, it can be evaluated. If it is procedural silence, that too will be visible—without this page pretending to know what anyone is thinking in private.

## The author, without prestige

I am dumb, I use drugs, and I spent four years learning mathematics. That is not evidence; it is the setup. The evidence is the formal work, the test results, and the public hashes above. The limitations are stated plainly. The technical files remain sealed.

## Limits of this notice

- No bounty has accepted the finding; no reward is owed.
- No live exploitation is claimed.
- No permissionless production attack path is claimed as established.
- Nobody is invited to test a live system.
- The underlying evidence remains private; hashes are commitments, not a substitute for review.
