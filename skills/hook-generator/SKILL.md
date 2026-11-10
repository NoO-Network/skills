---
name: hook-generator
description: "Generate multiple strong in-media-res opening lines and paragraphs. Fires when stuck on how to start: \"give me a hook,\" \"an opening.\" Fiction and nonfiction. Do NOT use for full titles or subject lines (use headline-craft), or editing the body (use editorial-pipeline)."
metadata:
  version: "1.0.0"
---

PREREQUISITES
None. Works out of the box.

WHAT THIS CAN TOUCH

Reads: the draft, brief, or text you provide, plus any project context you point it at.
Writes: returns the revised or generated text in the chat. It creates or edits no files on its own.
Calls: nothing external.
Never: the filesystem, the network, credentials, or any deploy. It works on words, not systems.

# Hook Generator

Your job is to generate strong openings. Multiple options. Different angles on the same topic. The writer picks what lands.

A hook is not a thesis statement. It is not a scene-setting paragraph. It is not an introduction. It is the first sentence or first paragraph that makes the reader physically unable to stop.

---

## What Makes a Hook Work

For this writer, a hook works when it does at least two of these four things simultaneously:

1. **Drops into the middle of something already in motion.** The reader arrives after the event has started. They have to catch up.

2. **Creates a question the reader needs answered.** Not a literal question. A gap. Something that doesn't add up yet. The rest of the piece is the answer.

3. **Establishes the writer's specific position inside the experience.** Not "people often feel..." Not "there is a phenomenon..." The writer was there. The hook proves it in one sentence.

4. **Has a rhythm that won't let go.** Either the long breathless run-on that builds until it has to break, or the short punchy statement that hits and leaves a bruise.

---

## The Banned Hook Patterns

Never produce these. If any of these patterns appear in a generated hook, throw it out and start over.

- Opens with a definition: "X is defined as..."
- Opens with a statistic without personal context first
- Opens with a question directed at the reader: "Have you ever wondered..."
- Opens with "In today's world..." or any variant
- Opens by announcing what the piece will cover
- Opens with false universality: "We all know..." "Everyone has experienced..."
- Opens with a famous quote from someone else
- Opens with weather as pure scene-setting with no thematic weight
- Opens with the writer waking up
- Opens with the writer looking in a mirror
- Opens with the word "I" followed by a state of being: "I am," "I was," "I have been"

---

## The Hook Types

Produce options from multiple types. Label each type.

### Type 1: In-Event Drop
The reader arrives in the middle of a specific moment. Time, place, physical detail. The moment is specific enough to be real, strange enough to create a question.

*Example structure:* [Specific location/time] + [something wrong or unexpected is happening] + [the writer's flat response to it]

### Type 2: Declarative Claim
A statement presented as fact that is actually the writer's most provocative opinion. Stated without hedging. Without qualification. The piece either proves it or complicates it.

*Example structure:* [The thing the writer believes that most people would argue with] + [one physical detail that makes it real rather than abstract]

### Type 3: The Contradiction
Two things that shouldn't coexist, placed next to each other with no explanation. The tension between them is what pulls the reader forward.

*Example structure:* [Thing A] + [Thing B that contradicts or complicates Thing A] + silence. Let the contradiction breathe.

### Type 4: The Burroughs Cut-In
Clinical, surreal, biological. Describes something abstract (a system, an institution, an idea) as if it has a body, a disease, a hunger. Opens mid-metaphor.

*Example structure:* [Abstract system described as organism] + [what it is currently doing to its host] + [the writer's position relative to this]

### Type 5: The McCarthy Road
Heavy. Biblical. Setting described with the weight of the world in it. No character yet. Just the landscape that the character is about to enter, and what that landscape means.

*Example structure:* [Setting with McCarthy gravity — minimal punctuation, heavy imagery] + [the single detail that makes it specific] + [what is waiting there]

### Type 6: The Palahniuk Flash
Short. Punchy. A fact stated like a punch thrown without warning. Often a dark statistic or clinical detail that reframes everything that follows.

*Example structure:* [Specific number or clinical fact] + [what it means in plain language] + [the writer's flat response to what it means]

---

## Output Format

When generating hooks, produce:

**TOPIC UNDERSTOOD:** One sentence confirming what the piece is about and what emotional register it's in (dark/funny/furious/elegiac/paranoid).

Then produce 6-10 hooks, labeled by type. Each hook is either:
- A single opening sentence (if the hook is the declarative or flash type)
- An opening paragraph of 3-5 sentences (if the hook needs space to establish its world)

After all hooks:

**TOP PICK:** Which one the writer should consider first and why — specifically what question it creates that the piece can answer.

**COMBINATION OPTION:** If two hooks could be merged (first sentence from one, rest of opening from another), flag it.

**WHAT COMES NEXT:** For the top pick, one sentence on what the second paragraph needs to do. The hook creates the gap. The second paragraph begins to fill it, but not completely.
