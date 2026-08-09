# Client-NeXtHer

**Juhi Agarwal · neXtHer** — helping women, especially mothers, use AI, mindset and practical systems to build their own income.

> ⚠️ **Status: PROSPECT, not yet a client.** Nothing signed, no revenue, no pricing agreed.
> If this doesn't convert, move the repo to archive rather than leaving a non-client in the client list.

**Last updated:** August 2026 · **Owner:** Kiran, Production X Creative Studio

---

## Where things stand

| | |
| --- | --- |
| **Her ask** | *"A digital production partner who can help me film, edit, publish, and grow high quality content as we build the brand together."* |
| **Her accounts** | `@juhiagarwal.coach` — 34 posts, 1,209 followers · Threads `@juhiagarwal.coach` — 3 followers |
| **Her references** | `@upgradingkatie` (415K — the blueprint) · `@melrobbins` (12.6M — the destination) |
| **Last contact** | Warm reply, then a scheduling question left unread |
| **Next action** | Send `deck/neXtHer-What-I-Found.pdf`, point her at slides 5 and 6, then leave it a week |

---

## The one-paragraph version

Her account advertises five different things at once — burnout in the bio, marriage across the grid, growth quotes in Stories, healing-plus-productivity on Threads, and AI-plus-income in what she actually told us. A visitor can't tell what she does, and neither can the algorithm. She has never spoken on camera in 34 posts, her best writing sits in captions where the platform can't reward it, and there is no funnel — nothing pinned, one highlight, no list. **The work isn't filming. It's picking one business, then publishing for it every week.**

The encouraging part: `@upgradingkatie` proved this exact model at 415K in the US, she's at the same life stage, and nobody in India is doing it in Hinglish for mothers.

---

## What's in here

### `strategy/`
| File | |
| --- | --- |
| **`client-brief.md`** | **Start here.** One page — the niche, her situation, what we'd do |
| `deep-read-round-2.md` | Latest analysis. Where it disagrees with older docs, this wins |
| `reference-accounts-addendum.md` | Katie and Mel breakdown. Revises two calls in the main strategy |
| `marketing-strategy.md` | Full strategy — positioning, content system, channels |
| `what-she-teaches.md` | What "AI training" concretely means, and the offer ladder |

### `outreach/`
| File | |
| --- | --- |
| **`CALL-SHEET.md`** | **Keep open during the call.** Ten questions, what to listen for, the deflections |
| `whatsapp-message.md` | Messages in his own voice, follow-ups, timing |
| `proposal.md` | Written proposal **with pricing** — internal only, never sent |

### `deck/` — what goes to her
- **`neXtHer-What-I-Found.pdf`** ← send this
- `neXtHer-What-I-Found.pptx` — editable
- `research-deck.html` — the source the PDF renders from
- `build_research_deck.js` — builds the PPTX · `render_research.js` — builds the PDF
- `logo/` — the Production X mark rebuilt as vector, plus its generator

### `archive/`
The earlier proposal deck, which **includes pricing**. Superseded — money is handled in conversation, not on a slide.

---

## Rebuilding the deck

```bash
npm install pptxgenjs playwright sharp
node deck/logo/make_logo.js        # regenerate logo assets
node deck/build_research_deck.js   # → neXtHer-What-I-Found.pptx
node deck/render_research.js       # → neXtHer-What-I-Found.pdf + screenshots
```

`render_research.js` also runs two checks: elements spilling off-slide, and text overlapping other text. Both should report clean.

**Paths inside the scripts assume the old flat layout — update them for these folders before running.**

---

## Two rules that matter

**1. Every claim in the deck must be checkable.**
Its whole power is that she can verify it in two minutes — her Threads line, her Story text, her bio, Katie's numbers. An earlier draft claimed "I spent a week / roughly 20 hours" and that was cut: it wasn't true, and she knew we were away on a family emergency. One unverifiable claim would make her doubt everything else.

**2. No pricing in anything she sees.**
The client deck has none. Money is a conversation. `outreach/proposal.md` and everything in `archive/` are internal.

---

## Open questions for her

1. Is `@juhiagarwal.coach` becoming neXtHer, or does neXtHer get its own account?
2. "Trusted by 100+ women" — paid clients or free sessions?
3. **Has anyone paid her for AI training yet?** Biggest unknown in the plan
4. What can she actually teach in AI, concretely?
5. Budget and runway?
6. Willing to be on camera, talking, in Hinglish?

---

## Also on Drive

`Production-X-OS / 07-Clients / Juhi Agarwal - neXtHer` holds the same markdown plus a `Profile.md`. The prospecting shortlist that came out of this work lives in `04-Sales`.
