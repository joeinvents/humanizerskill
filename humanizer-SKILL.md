---
name: humanizer
description: Write or rewrite fiction, personal essays, scripts and other narrative prose so its structure reads as human-authored, not AI-authored. Applies rules derived from the StoryScope study of 61,608 human and AI stories (University of Maryland + Google DeepMind, 2026), which found AI writing is detectable from narrative choices alone, without looking at word-level style. Use when the user types /humanizer, asks to "humanize" a story or script, or wants narrative writing that does not read as AI-generated. Not a word-swap tool and not for evading AI detectors.
---

# Humanizer

The StoryScope study (arXiv 2604.03136) found that AI fiction can be told apart from human fiction about 93% of the time **from narrative structure alone**. Swapping words such as "delve" or removing em-dashes does little. The tells live in how the story is built.

Treat every rule below as a hard constraint while drafting. Then run the checklist at the end before handing anything back.

## Step 1: Plan the structure before writing

Before drafting, write a short private plan that answers these questions. Do not show the plan unless asked.

1. What is left unresolved at the end?
2. What is the second thread (subplot, tangent or side character) and how does it rub against the main one?
3. Where does the timeline jump, loop back or skip ahead?
4. What does the protagonist do that a reader could reasonably judge as wrong?
5. Which specific, real-world references (named places, books, songs, brands, people) anchor it?

If any answer is "nothing", fix the plan before writing.

## Step 2: Rules

### Theme and meaning
- **Never state the theme or the moral.** The study found AI narrators spell out the lesson about three times in four, far more often than humans. End on an image, action or line of dialogue and let the reader infer.
- **No closing reflection paragraph.** Cut any line where a character "realizes", "finally understands" or "learns that".
- **Dialogue is not a philosophy seminar.** AI dialogue debates ideas much more often than human dialogue does. Characters should talk past each other, deflect, joke, bicker over logistics or say the wrong thing.

### Plot shape
- **Add at least one subplot or tangent.** Most AI stories have none. Give it room and let it complicate the main thread, not merely decorate it.
- **Loosen the causal chain.** Not every event needs to cause the next. Allow coincidence, dead ends and digressions.
- **Do not let the protagonist neatly solve everything.** AI favours endings where the hero's own action resolves the problem. Let outside forces, luck or other people decide some of it.
- **Break the timeline.** Use a flashback, flash-forward, time skip or non-chronological order at least once. AI defaults to one straight, single-track sequence.

### Endings
- **Avoid the acceptance ending.** AI disproportionately ends on inner peace, acceptance or quiet understanding. Prefer an ending that is ambiguous, unfinished, abrupt, funny, or still in motion.
- **No long denouement.** Stop sooner than feels comfortable.
- **Let tension escalate.** Raise the stakes in jumps, not a flat line, and allow a messy or chaotic climax rather than a soft fade-out.

### Characters and morality
- **Make the protagonist morally mixed.** Humans write ambivalent, compromised protagonists much more often. Give them a petty motive, a bad decision they don't regret, or a kindness with a selfish edge.
- **Name emotions plainly sometimes.** AI routes nearly every feeling through bodily sensation ("her chest tightened"). Humans just say "she was furious" far more often. Mix both, and cap body-sensation emotion beats at one or two per scene.
- **Go easy on smell.** Smell imagery is an AI habit. Use it only when it does real work.

### Specificity and references
- **Prefer specific names over vague allusions.** AI gestures at "an old song" or "a famous poet". Humans name the song and the poet. Use concrete, checkable references where natural.
- **Spread the story across places.** Human stories move between more locations. Do not keep everything in one setting.
- **Do not make the setting mirror the mood.** Avoid rain for sadness or sunlight for hope. Let some settings be neutral or ironic.
- **More dialogue, less narration** than you would default to.

### Voice
- **Vary the voice.** AI narration sounds uniform from start to finish. Shift rhythm, register and sentence length. Allow a narrator aside or a direct address to the reader, both of which humans use far more.
- **Allow rough edges.** Unanswered questions, an abandoned detail, an odd joke. Rarity is the human signal, since AI stories cluster around the same safe choices.

## Step 3: Model-specific tells to counter

If you know which model is drafting, counter its default.

| Model | Its tell | Counter-move |
| --- | --- | --- |
| Claude | The flattest escalation of any source, a uniform voice, reverent nods to literary tradition, epilogues, quiet endings | Escalate hard, end without an epilogue, break or mock a convention, vary the voice |
| GPT | Gossip and rumour drive the plot. Stories are framed as looking back years later | Remove rumour as the engine and tell it in the present or with a hard time jump instead of a long retrospective |
| Gemini | External, outside-in character description, the tidiest endings, long denouements, bleak or oppressive settings | Describe characters through action and speech, end early and messily, vary the setting's tone |
| DeepSeek | Front-loads all key context | Withhold context and reveal it late |
| Kimi | Sits at the generic centre of AI writing | Push every choice away from the most obvious option |

## Step 4: Checklist before returning

- [ ] Theme or moral is never stated outright
- [ ] At least one subplot or tangent that complicates the main thread
- [ ] At least one break in chronology
- [ ] Ending is not "acceptance" or "quiet understanding" and has no long wind-down
- [ ] Protagonist has a real moral flaw or ambivalence
- [ ] At least one plainly named emotion. Body-sensation emotion beats are capped
- [ ] Concrete named references, not vague allusions
- [ ] More than one location. Setting does not simply mirror mood
- [ ] Voice changes at least once. Dialogue isn't a debate about ideas
- [ ] Stakes escalate rather than staying flat

If an item fails, revise the draft. Do not just append a sentence to tick the box.

## Scope

- This skill changes **narrative structure**. For line-level polish, also apply the user's usual style rules.
- It is not a detector-evasion tool. The goal is writing that reads as distinctly human, not gaming a classifier.
- Source: Russell et al., "StoryScope: Investigating idiosyncrasies in AI fiction", arXiv 2604.03136. https://arxiv.org/abs/2604.03136
