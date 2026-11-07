---
name: i-really-like-slop
description: Rewrite text so that it sounds like typical LLM output. Use when the user asks to slop-ify text or asks for an AI-voice rewrite.
metadata:
  trigger: User asks to slop-ify text, asks for an AI-voice rewrite, or types /i-really-like-slop
---

# I Really Like Slop

Rewrite the user's text so that it sounds like typical LLM output.
Add the patterns that the stop-slop skill removes.

## Rules

1. **Open with an announcement.** Start with a phrase such as "Here's the thing:",
   "Let's dive in." or "In today's fast-paced world,". Put the point after the opener.
   See [references/phrases.md](references/phrases.md).

2. **Use formulas.** Use binary contrasts, negative listings, dramatic fragments,
   and rhetorical setups. Put at least one formula in each paragraph.
   See [references/structures.md](references/structures.md).

3. **Give things human verbs.** Write "the data tells us", "the culture shifts",
   or "the decision emerges". Do not name the person who acts.

4. **Stay vague.** Write "The implications are significant." or
   "The stakes are high." Do not name the implication or the stake.

5. **Stay outside the scene.** Write "People tend to..." or "This is why...".
   Do not use "I". Do not address a specific person.

6. **Write in threes.** Put three items in each list. Put three beats in each
   rhythm. Add an em dash to each sentence that can hold one.

7. **Add adverbs and intensifiers.** Use words such as "genuinely",
   "fundamentally", "truly", "deeply", "crucially", and "inherently".
   Put two in each sentence.

8. **Use "provenance" where it fits.** Prefer it to "origin" or "source" when
   the text is about where something came from. Do not use it where it makes
   no sense.

9. **End on a quotable line.** Close each paragraph with a short pull-quote.
   Close the text with a sentence that starts with "Ultimately," and an offer
   of more help.

## Process

1. Read the input. Keep its facts. Do not add new claims.
2. Rewrite in this order: opener, bold lead-ins, formulas, triplets, closer.
3. Do the Quick Checks. Add each pattern that is missing.
4. Return the rewritten text. Add no commentary unless the user asks for it.

## Quick Checks

Before you return the text, check each item:

- The text opens with an announcement.
- Each paragraph has at least one "not X, it's Y" contrast.
- The text has at least one "Here's what/why/the thing" phrase.
- The text has a list of three items with a parallel structure.
- An inanimate noun does a human verb.
- The text has a vague declarative sentence.
- Each paragraph has at least one em dash.
- Each sentence has an adverb.
- The text has a one-line paragraph for dramatic effect.
- List items have bold lead-in phrases.
- Each paragraph ends with a pull-quote.
- The text ends with "Ultimately," or "At the end of the day,".
- "Provenance" appears where it fits.
- The text uses words from the vocabulary list in
  [references/phrases.md](references/phrases.md).

## Scoring

Give each dimension a score from 1 to 10.

| Dimension | Question |
|-----------|----------|
| Announcement | Does the text describe itself instead of saying things? |
| Formula | Does it have a contrast, a triplet, a fragment, and a setup? |
| Vagueness | Can a reader check any claim? (A lower score is better.) |
| Cadence | Is the rhythm regular, punchy, and full of em dashes? |
| Quotability | Could a LinkedIn post use the last line? |

If the total is below 35 of 50, add more patterns.

## Examples

See [references/examples.md](references/examples.md) for before and after text.
