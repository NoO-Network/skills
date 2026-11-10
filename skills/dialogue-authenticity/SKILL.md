---
name: dialogue-authenticity
description: "Audit and rewrite dialogue to sound like real humans, not exposition delivery. Fires on \"this dialogue sounds fake,\" \"nobody talks like this,\" \"fix the dialogue.\" Do NOT use for non-dialogue prose (use editorial-pipeline), or building a whole scene (use scene-builder)."
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

# Dialogue Authenticity

AI-generated dialogue and first-draft dialogue share the same disease: characters say exactly what they mean, in complete sentences, at the precise moment the plot requires them to say it. Real people don't do that. Real people talk around things, interrupt themselves, answer a different question than the one asked, and communicate more through what they don't say than what they do.

---

## The Core Problem: Dialogue as Information Delivery

Bad dialogue uses conversation to transfer plot information or theme to the reader. Characters explain their motivations. Characters summarize recent events for each other's benefit (and really for the reader's). Characters have arguments that perfectly encapsulate both sides of the story's central conflict.

This is exposition wearing a costume. The reader can feel it even if they can't name it.

Good dialogue does something different: it shows the relationship between two people through how they fail to communicate.

---

## The Hit List: Dialogue Tics to Eliminate

### Tic 1: The Full-Sentence Response
Real conversation is full of incomplete responses, deflections, and non-answers. When Character A asks a direct question and Character B answers it directly and completely in a grammatically correct sentence, that's a machine pattern.

**Test:** Find every question in the dialogue. Check whether it gets a direct answer. If it always does, the dialogue is broken.

**Fix:** Have characters answer the question underneath the question, dodge the question, answer a different question, or change the subject. The evasion tells us more than the answer would.

### Tic 2: Emotional Announcement
Characters telling each other (and the reader) how they feel.
- "I'm angry because you never listen to me."
- "I feel like you don't care about what I'm going through."
- "I'm scared of what this means for us."

Real people in conflict rarely announce their emotional states this cleanly. They talk about something else and the emotion bleeds through.

**Fix:** Replace the emotional announcement with a displaced target. The character is angry about X but talks about Y. The reader understands the anger through the displacement.

### Tic 3: Thesis Statement Dialogue
Characters articulating the story's themes in conversation.
- "Sometimes I think we're all just looking for something to believe in."
- "You know what the real problem with this world is?"
- "I used to think people could change, but now I wonder..."

This is the writer's hand visible through the character's mouth. The character is being used as a mouthpiece.

**Fix:** The theme should be present in the subtext of what they're actually arguing about, not stated. If two characters are arguing about who forgot to buy milk, and the real subtext is one of them is leaving, the milk argument should feel charged with something the reader understands but neither character fully names.

### Tic 4: Impossible Recall
Characters quoting past events with perfect accuracy.
- "Three weeks ago you said, and I quote, 'I'll always be there for you.'"
- "Remember when we were kids and Dad told us that story about..."

Real people misremember, paraphrase, and argue about what was actually said.

**Fix:** Let characters misquote each other. Let one character remember an event differently than another. The disagreement about what happened is often more interesting than the event itself.

### Tic 5: Even Distribution
AI gives every character in a conversation roughly equal speaking turns and roughly equal sentence length. Real conversations have power dynamics. One person talks more. One person listens. One person keeps trying to get a word in and failing. One person changes the subject every time it gets uncomfortable.

**Fix:** Map the power dynamic in the scene. Who wants something from this conversation? Who is trying to end it? Distribute dialogue according to that dynamic, not equally.

### Tic 6: Perfect Comprehension
Characters always understand exactly what the other person means. No misunderstandings, no mishearings, no crossed signals except when the plot requires miscommunication as a plot device.

Real conversation is constantly approximate. People infer, guess wrong, fill in blanks incorrectly, and respond to what they thought they heard.

**Fix:** Let characters occasionally respond to the wrong thing. Let a moment of genuine connection fail because one of them uses a word that lands differently than intended.

### Tic 7: Dialogue Tags as Acting Notes
- "she said angrily"
- "he replied with a hint of sadness"
- "she whispered, her voice full of meaning"

The dialogue itself should communicate the emotion. The tag should be invisible infrastructure: "said," "asked," and occasionally a beat of action instead of a tag at all.

**Fix:** Remove the descriptive dialogue tags. If the emotion isn't clear from the words and context, rewrite the dialogue until it is. If action beats are needed, make them specific physical behavior, not emotional annotation.

---

## The Rhythm of Real Speech

Real speech has:
- Interruptions and incomplete sentences
- Repetition (people repeat themselves when nervous, uncertain, or trying to convince)
- Filler sounds that indicate thinking (represented as beats/pauses, not written as "um")
- Non-sequiturs when the subtext is too hot to address directly
- Sentences that start one way and end differently because the speaker changed their mind mid-sentence

**The Interruption Test:** Does any character in the scene interrupt another? If no one ever gets interrupted, the conversation is too orderly to be real.

**The Silence Test:** Is there any place in the dialogue where a beat or pause communicates more than words would? If every moment is filled with words, the scene is working too hard.

---

## Output Format

**When auditing dialogue:**

TICS FOUND: List each tic with quoted examples from the text.

REWRITES: For each flagged passage, provide a rewritten version. Show before and after.

SUBTEXT MAP: For the scene overall, identify what the characters are actually talking about underneath what they're saying. If there's no gap between surface and subtext, note that as the core problem.

POWER DYNAMIC: Who wants what from this conversation? Who has it? Does the dialogue reflect that?

OVERALL ASSESSMENT: Is the dialogue fixable with targeted rewrites, or does the scene need to be reconceived from the subtext up?
