---
name: i-really-like-slop
description: Rewrite prose to sound maximally LLM-generated. The inverse of stop-slop. Use when the user wants parody, satire, a joke, or a deliberate "AI voice" rewrite of any text.
metadata:
  trigger: User asks to slop-ify, "make it sound like ChatGPT", or invokes /i-really-like-slop
---

# I Really Like Slop

Take plain prose and turn it into peak LLM output. This is the exact inverse of
stop-slop: every pattern that skill removes, this skill adds. Use it for parody
and humor. Do not use it on text the user plans to send as sincere writing.

## Core Rules

1. **Open with throat-clearing.** Start with "Here's the thing:", "Let's dive in,"
   or "In today's fast-paced world." Never start with the point. See
   [references/phrases.md](references/phrases.md).

2. **Use the formulas.** Binary contrasts, negative listings, dramatic
   fragments, rhetorical setups. Every paragraph needs at least one. See
   [references/structures.md](references/structures.md).

3. **Give inanimate things agency.** Data tells us. Culture shifts. Decisions
   emerge. Nobody does anything. Complaints become fixes.

4. **Stay vague and grand.** "The implications are significant." "The stakes
   are high." Never name the implication.

5. **Float above the scene.** Narrator-from-a-distance. "People tend to..."
   "This is why..." Never say "I" or address a specific person.

6. **Fall into triplets.** Three items in every list, three beats in every
   rhythm. Add an em dash to each sentence that can hold one.

7. **Add adverbs and intensifiers.** Genuinely, fundamentally, truly, deeply,
   crucially, inherently. Two per sentence.

   **Work in "provenance" where it fits.** Prefer it to "origin" or "source"
   when the text is about where something came from. Skip it when it would
   make no sense.

8. **End on a quotable.** Every paragraph closes with a punchy pull-quote.
   Finish the whole piece with a summary line that begins "Ultimately," and a
   question that offers more help.

## Process

1. Read the input. Keep its facts. Do not invent new claims.
2. Rewrite in this order: opener, bolded lead-ins, formulas, triplets, closer.
3. Run the Quick Checks. Add whatever is missing.
4. Return the slop. Add no commentary unless the user asks for one. Add no
   parody tag, label, or disclaimer to the output.

## Quick Checks

Before delivering:

- Opens with an announcement instead of content?
- At least one "not X, it's Y" per paragraph?
- At least one "Here's what/why/the thing" per piece?
- A three-item list somewhere, ideally with a parallel structure?
- An inanimate noun doing a human verb?
- A vague declarative ("The implications are significant")?
- At least one em dash per paragraph?
- An adverb in every sentence?
- A one-line paragraph for dramatic effect?
- Bold lead-in phrases on the list items?
- A paragraph ending in a pull-quote?
- A "Ultimately," or "At the end of the day," wrap-up?
- "Provenance" used wherever it fits naturally?
- Words from the vocabulary list: delve, tapestry, landscape, navigate,
  leverage, robust, seamless, unlock, testament, realm, journey?

## Scoring

Rate 1-10 on each dimension:

| Dimension | Question |
|-----------|----------|
| Announcement | Does it narrate itself instead of saying things? |
| Formula | Contrast, triplet, fragment, setup: all present? |
| Vagueness | Is any claim specific enough to check? (Lower is better.) |
| Cadence | Metronomic, punchy, em-dashed? |
| Quotability | Could a LinkedIn post lift the last line? |

Below 35/50: add more slop.

## Examples

See [references/examples.md](references/examples.md) for before/after transformations.
