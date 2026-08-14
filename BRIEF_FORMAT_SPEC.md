# NPPE Brief Track — format spec

Paste this at the top of each batch, then attach 2–3 `chX_Explainer.html` files.
Ask for: "Build the Brief tracks for these, following the spec."

---

## What the Brief is

A **refresher track for material already learned**, not a shorter teaching track.
The Explainer teaches from zero. The Brief assumes the Explainer has been heard.

## Output

One `chX_Brief.html` per chapter. Clone the source Explainer file exactly and
replace only the `SEGMENTS` array. Do not touch the player code.

- Same number of segments as the source
- Same `title` strings, character for character — diagram 3 must map to diagram 3
- Same field names: `title`, `text`, `ex`
- Change only the `<title>` tag and `<h1>` to read "Brief"

## Length

- Whole chapter: **~70% shorter** than the source (`text` + `ex` word count)
- Per segment: 55–80 words of `text`, 20–30 words of `ex`
- No single segment over ~110 words total, so nothing runs past ~45 seconds

## Sentence order — this is the core rule

Audio can't be skimmed, so the point goes first:

1. **The rule**, stated flat in the opening sentence
2. **The conditions and qualifiers** that make it true — *usually*, *only if*,
   *unless the wording is unmistakable*, the numbers, the thresholds
3. **The boundary or flip** — where the rule reverses, when there is one
4. **`ex`**: one concrete situation, present tense, no scene-setting

Never build up to the point. Ten seconds in, the listener should already know
whether this segment is one they needed.

## Cut

- **Every inline parenthetical definition.** This is ~32% of the source wordcount
  and the single biggest win. "negligence (carelessness that causes harm)" →
  "negligence".
- Doubled passages — the concise version followed by the same content restated
  in plain words. Keep one pass.
- "In simple words", "In simple terms", "This idea is about", "The important
  thing to understand is"
- Hype and filler: "incredibly", "totally", "absurd", "the ultimate sweet deal",
  "massive", "fatal", "vaporizes"
- Rhetorical questions and second-person setup ("Imagine you...")

## Keep

- Every qualifier and condition — this is what separates a useful brief from a
  keyword list, and it is what the exam tests
- All numbers, durations, thresholds, percentages
- Case names, with the one thing each stands for
- The twist / flip, compressed to one sentence
- The word that marks the dividing line (negative vs positive, timing vs count,
  condition precedent vs timing)

## Tone

Plain, declarative, spoken. Short sentences. No bullets or lists — it is read
aloud. Write numbers as words where they are spoken naturally
("twenty years", "life plus seventy years").

## Accuracy

Flag anything in the source that is outdated or internally inconsistent rather
than carrying it forward. Use the corrected value in the Brief and say so.

Known corrections already applied:
- **Trademark term: 10 years**, renewable indefinitely (not 15) — changed June 2019
- **Industrial design: later of 10 years from registration or 15 from filing**
  (not a flat 10) — changed November 2018
- ch9 names both *Begro* and *BG Checo v. BC Hydro* for the same principle;
  these are different cases and one must be chosen

## Batching

2–3 chapters per conversation, fresh chat each time. More than that and the
output turns generic — the close reading that catches errors and preserves
conditions does not survive bulk processing.
