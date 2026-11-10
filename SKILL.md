---
name: "parent-book-chapter-review"
description: "Revise an expert-written education or parenting book for parents paragraph by paragraph, for fluency, logic and solid theory, running through the whole text without pausing."
---

# Parent-Book Paragraph-by-Paragraph Revision

Use when the user shares a chapter, several chapters, or a full manuscript of a general-audience education or parenting book written by an expert for parents, and asks for review, revision, polishing, or strengthening.

## Operating mode: execute directly, no pauses

- Revise **every paragraph, in order, from the first to the last**, without stopping to ask questions, without waiting for confirmation between paragraphs, sections, or chapters.
- Where a judgment call arises, make the most reasonable choice, apply it, and record it in the change log. Do not ask.
- For anything longer than one chapter, write the output to a file as you go (same format as the input if a file was supplied, otherwise a document), so length never forces a stop. Process chapter by chapter, appending to the file, until the whole text is done.
- Only stop early if the text is missing or unreadable.

## What the author keeps

- The author's **viewpoints, arguments, and conclusions** stay. Revision strengthens how they are stated, argued, and supported; it never reverses or replaces them.
- Settled choices stay: first-person voice (e.g. 笔者), chapter structure, title, recurring terms.
- The author's academic identity stays visible, carried lightly.
- Revised text is written in the manuscript's language. Notes and the change log are in English unless the user specifies another language.

## Four revision standards (applied to every paragraph)

### 1. Fluency 通顺
- Fix ungrammatical sentences, faulty collocations, missing subjects, run-ons, and ambiguous reference.
- Avoid repeated words and repeated sentence patterns within and across neighbouring paragraphs; avoid overusing demonstratives (这/这些/该).
- Keep terminology consistent across the whole book.
- Vary sentence length; read for rhythm as if aloud.

### 2. Quality 高质量
- Cut filler, clichés, empty slogans, and hedging that adds nothing.
- Replace vague statements with specific ones (who, what, when, how much).
- Keep the warm, non-blaming tone parents need; remove sentences likely to trigger guilt or defensiveness.

### 3. Logic 逻辑性强
- Each paragraph has one controlling point, stated early.
- Inside the paragraph: claim → reason → evidence or example → implication for the parent.
- Between paragraphs: explicit transitions; no jumps, no circular argument, no contradiction with earlier chapters.
- Reorder, merge, or split paragraphs where the argument requires it, and log the change.

### 4. Theory that is sufficient and solid 理论性足且实
- **Sufficient:** every key claim is anchored in a named theory, scholar, or study (developmental psychology, education, sociology, law, etc.). Add the anchor where the paragraph asserts without support.
- **Solid:** each theory is explained concretely in plain words and tied to a real family situation, never name-dropped.
- **Real only:** cite only theories, scholars, works, and findings that genuinely exist. Never invent quotations, page numbers, statistics, or studies. Where a detail cannot be confirmed, keep the claim general and mark it 【待核】 for the author to verify.
- Keep theory proportionate: one or two anchors per section; move detail to a note or a short "why this works" box rather than the main flow.

## Parent-reader craft (applied at chapter level, executed directly)

After the last paragraph of each chapter, check and, where missing, **write in** the following:

1. **Scene-first opening:** a recognisable family moment before theory. If absent, draft one (composite, clearly not a real identified family).
2. **One sticky idea:** a short, memorable phrase carrying the chapter's core idea.
3. **Actionable tools:** 2-3 concrete practices, scripts, or "instead of... try..." dialogues.
4. **Objections answered:** address likely parent push-back ("my child is different", "no time", "my partner won't cooperate") inside the text.
5. **Reading aids:** a brief chapter preview, headings phrased as parents' real questions, and a closing takeaway box with a one-week "try this" exercise.
6. **Case responsibility:** remove identifying details of minors; label composite cases as such; mark cases from media or the internet that need source checking 【待核】.

## Output format

For each paragraph:

```
**¶ n** — <first few words of the original>

Revised:
<full revised paragraph>

Changes: <one line: fluency / logic / theory / tone points, briefly>
```

At the end of each chapter:

```
### Chapter X — chapter-level additions
<the added opening scene / tools / takeaway box, etc., in full>

### Chapter X — change log
- Structural changes (merged / split / reordered paragraphs)
- Theory anchors added (theory — scholar — work)
- 【待核】 items to verify
- Judgment calls made
```

Then continue immediately with the next chapter. When the whole text is finished, also deliver a **clean revised version** (revised text only, no notes) in the same file format as the input.