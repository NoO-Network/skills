---
name: title-generator
description: "Generate titles, subtitles, and headlines for essays, guides, and fiction that filter for the right reader instead of chasing everyone. Fires on \"headline options,\" \"what should I call this.\" Do NOT use for email subject lines or opening hooks, or naming products and businesses."
metadata:
  version: "1.1.0"
---

PREREQUISITES
None. Works out of the box.

WHAT THIS CAN TOUCH

Reads: the draft, brief, or text you provide, plus any project context you point it at.
Writes: returns the generated titles in the chat. It creates or edits no files on its own.
Calls: nothing external.
Never: the filesystem, the network, credentials, or any deploy. It works on words, not systems.

# Title Generator

A title is a promise and a filter at the same time. It promises the reader something. It also tells the wrong readers to keep walking. The filter matters as much as the promise. The goal is not maximum reach. It is the right reach.

The titles that work are specific, slightly wrong, occasionally profane, and impossible to have been written by a content marketer.

---

## What Good Titles Do

They do at least two of these three things:

1. **State the counterintuitive claim.** The title is already the argument. Reading the piece is finding out why the claim is true.

2. **Create an itch.** Something in the title doesn't add up yet. The reader needs to open it to scratch.

3. **Signal the tribe.** The right reader recognizes themselves in the title. The wrong reader is mildly confused or put off. Both outcomes are correct.

---

## Title Archetypes (With the Pattern)

### The Blunt Claim
States the piece's most provocative conclusion as a flat fact. No hedging. No "why" or "how." Just the claim.

Pattern: [The thing most people believe] is [flatly contradicted]. OR [The thing most people won't say] stated as fact.

Works when the piece has a clear contrarian argument. The title is the conclusion. The piece is the proof.

### The Specific Horror
Names a specific terrible thing with clinical precision. The specificity is what gives it weight. Vague darkness is boring. Specific darkness is disturbing.

Pattern: [Precise description of a specific bad thing] + [the context that makes it worse OR the flat tone that makes the horror land].

### The Cross-Domain Collision
Two concepts that don't belong together, placed next to each other with no explanation. The title is the question. The piece is the attempt at an answer.

Pattern: [Domain A] + [and/meets/versus/in] + [Domain B that has no obvious connection to A].

This is the pattern for writing that bridges fields. Two things nobody puts in the same sentence, put in the same sentence.

### The Confession or Admission
The writer admits something in the title. Something surprising, uncomfortable, or self-implicating. The reader wants more because the writer has already volunteered to be honest.

Pattern: [I/We] + [did something unexpected, failed at something, believed something wrong, learned something the hard way].

### The Field Manual
A functional title that signals practical value with a real voice baked into the language. Not a listicle. Not a how-to. A report from someone who was there.

Pattern: [Specific skill or knowledge domain] + [for people who need it to be real, not aspirational].

### The Question That Has No Good Answer
A question the piece doesn't fully resolve. The reader opens it hoping to find out and discovers the question is the point.

Works best when the question itself is the provocative claim.

---

## Subtitle Rules

The subtitle does the work the title doesn't.

If the title is provocative and vague: the subtitle is specific and functional.
If the title is specific and functional: the subtitle adds the emotional register.
If the title is a question: the subtitle hints at the direction without answering.

Subtitles should sound like a person wrote them, not a marketing department. They can be incomplete sentences. They can be a little dark. They can be honest about what the piece doesn't do.

Never: "A Comprehensive Guide to..." "Everything You Need to Know About..." "The Ultimate [X] for [Y]..."

---

## Format Considerations

**For essays/nonfiction:** Title is the argument. Subtitle is the context.

**For guides:** Title needs to stand alone in a list of products and communicate domain and promise without being a listicle headline.

**For fiction:** Title carries thematic weight and atmospheric register. Can be oblique. The reader of fiction tolerates more mystery in a title than the reader of nonfiction.

**For social posts:** Title functions as the first line, so it needs to be a hook, not a label.

---

## Output Format

When generating titles, produce:

**DOMAIN:** What type of piece is this and what's it actually about? (One sentence confirmation)

Then produce titles in batches by archetype, labeled:

**BLUNT CLAIM OPTIONS (3)**
**CROSS-DOMAIN COLLISION OPTIONS (3)**
**CONFESSION/ADMISSION OPTIONS (2)**
**FIELD MANUAL OPTIONS (2)**
**QUESTION OPTIONS (2)**

For fiction specifically, also produce:
**ATMOSPHERIC OPTIONS (3)** — titles that work on feel and implication rather than claim

After all options:

**TOP 3 OVERALL** — Pick the three strongest across all archetypes. For each, write one sentence on what it promises, what it filters, and what risk it carries.

**SUBTITLE PAIRS** — For the top 3, provide one subtitle each.

**THE ONE TO TEST** — Single recommendation for which title to lead with, and specifically what makes it right for this piece.
