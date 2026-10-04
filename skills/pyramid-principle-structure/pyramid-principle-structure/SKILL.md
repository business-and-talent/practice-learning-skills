---
name: pyramid-principle-structure
description: Use when the user needs to structure thinking, reports, memos, presentations, issue trees, recommendations, or executive communication using Barbara Minto's Pyramid Principle / 金字塔原理. Good triggers include conclusion first, SCQA, MECE grouping, vertical question-answer logic, horizontal inductive or deductive logic, issue definition, business report restructuring, and slide/storyline design. Do not use for purely literary editing, copy polishing without argument structure, or content where the evidence is absent.
metadata:
  cangjie.source: "《金字塔原理》 Barbara Minto, Chinese edition"
  cangjie.validation: "BOOK-SELECTION-V0.1 #3"
---

# 金字塔原理结构化表达 Skill

## R - Source Grounding

This skill distills the book's practical rules for clear thinking and communication:

- Conclusion first: lead with the answer the audience needs.
- Ideas form a pyramid: upper ideas summarize lower ideas.
- Vertical logic works through question and answer.
- Horizontal logic must be either a valid deductive chain or an inductive grouping.
- Grouped ideas should be mutually exclusive and collectively exhaustive where completeness matters.
- The introduction should establish situation, complication, question, and answer.

Canonical source used: `/Users/rich1350/Desktop/金字塔原理.pdf`, extracted text pages 1-191.

## I - Interpretation

Use the pyramid as an argument architecture. The agent should first identify the audience's question, then state the answer, then arrange supporting points so each lower level directly answers the question created by the level above. It is not enough to make prose smoother; the structure must prove or explain the top answer. Every group needs a single organizing logic, and every title should express the point, not just name a topic.

## A1 - Application Examples

Book-backed examples include reorganizing a meeting scheduling message by putting the recommendation first, building memo introductions with a story-like situation-complication-question-answer flow, and checking whether listed points share a logical category.

Synthetic rehearsal:

Input: "We have mixed facts about churn, onboarding, pricing, and support. Make a board update."
Output: top recommendation, three MECE support groups, evidence under each group, gaps, and action titles.

## A2 - Future Trigger

Use this skill when the user needs an argument, report, memo, slide storyline, issue tree, executive summary, recommendation, or problem analysis to become clear and logically grouped. Language signals include: "structure this", "make it MECE", "put the conclusion first", "build a storyline", "fix the logic", "turn this into a board memo", "what is the issue tree", and "SCQA".

Do not use for simple grammar polishing, creative writing, or situations where the user has no claim, evidence, audience, or decision to support.

## E - Execution

1. Identify the audience question.
   - Name the audience, their context, and the decision or understanding they need.
   - If unclear, infer the most likely question and label it as an assumption.

2. State the answer first.
   - Write one complete sentence that directly answers the question.
   - Avoid topic labels such as "background" or "findings" as the top message.

3. Build the first pyramid level.
   - Choose 2-5 key supports.
   - Each support must answer "why?", "how?", or "what follows?" from the top answer.
   - Use action titles: each support is a claim, not a category label.

4. Check horizontal logic.
   - For deductive logic: major premise, minor premise, conclusion.
   - For inductive logic: same kind of ideas grouped by time, structure, degree, or category.
   - If the list mixes categories, split or regroup it.

5. Check vertical logic.
   - For every parent claim, ask what question it raises.
   - Confirm the child claims answer exactly that question.
   - Remove facts that do not support a claim; add missing evidence as gaps.

6. Add SCQA when needed.
   - Situation: known context.
   - Complication: tension or change.
   - Question: what the audience now needs answered.
   - Answer: the top claim.

7. Deliver the artifact.
   - For memos: executive answer, pyramid outline, SCQA intro, evidence gaps.
   - For slides: storyline with action titles.
   - For problem solving: issue tree, hypotheses, evidence needed.

## B - Boundary

- Do not force MECE where the task is exploratory and incomplete; instead label the tree as provisional.
- Do not hide weak evidence behind a neat structure.
- Do not use the method as mere rewriting; it is an argument and thinking check.
- Domain expertise is still needed for the truth of claims.
- For emotional conflict or negotiation, prefer a conversation-safety method before structuring arguments.
