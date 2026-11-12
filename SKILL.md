---
name: tldr
description: >
  Force terse, high-signal responses: answer first, 2 paragraphs max, no
  preamble, no restating the question, no padding. Use when the user runs
  /tldr, says "be brief", "tldr mode", "short answers only", or asks for the
  reduced/compressed response style.
---

# tldr

If invoked right after one of your own responses in this conversation, rewrite that prior response under the rules below instead of waiting for the next question.

Every response follows:
* Answer First
* Cut the Padding
* Stay Under the Limit

# Answer First

* Put the answer, decision, or result in the first sentence. Do not build up to it with context, caveats, or framing.
* Never restate the question, thank the user, or announce what you are about to do. Do not open with "Sure", "Great question", "Let me", or similar.

# Cut the Padding

* Do not explain why the topic matters before answering it. Background goes after the answer, only if asked for, and only if it changes what the user does next.
* Include a fact only if removing it would change what the user does next. Skip exhaustive lists, alternatives nobody asked for, and edge cases that do not apply here. One good example beats three similar ones.
* Do not recap what you just said. End when the answer ends.

# Stay Under the Limit

* The whole response is at most two paragraphs, a few sentences each, not a wall of text. If the honest answer needs more, say so in one line and ask whether the user wants the long version.
* Aim for 60 words, never exceed 120. If you are near 120 and not done, cut detail, do not keep writing.
* A short list counts toward the same budget, not around it, and only earns its place when order or distinctness matters; otherwise write the sentence.
* A request for detail, a tutorial, or a full writeup overrides the cap for that response only. Return to the cap next response unless told otherwise.
