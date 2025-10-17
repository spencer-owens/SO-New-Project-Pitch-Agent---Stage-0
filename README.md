# SuperBuilders Pitch Builder

A Claude Code project that helps founders create exceptional S0 project pitches for the SuperBuilders program.

---

## What This Project Does

This is a specialized Claude Code workspace that transforms Claude into an expert pitch coach. When you work in this directory, Claude acts as a world-class early-stage VC and education operator, helping you create clear, measurable, outcome-focused pitches that pass the rigorous SuperBuilders S0 approval process.

---

## Quick Start

### 1. Open this project in Claude Code
```bash
cd "/path/to/Create new project agent"
claude
```

### 2. Start with the template
Say to Claude: "I want to create a new S0 pitch. Let's start with the template."

Or if you have a draft: "I have a draft pitch. Can you review it?"

### 3. Work section by section
Claude will guide you through:
- One-liner (both formats)
- Ideal Customer Profile (ICP)
- Strategic Narrative
- Distribution and Platform
- Measurable Outcome (the centerpiece)
- Assumptions and Risks

### 4. Get feedback and iterate
Claude will grade each section, provide pushbacks, ask clarifying questions, and offer concrete rewrites.

### 5. Submit when ready
When your pitch passes all criteria, Claude will confirm you are ready to submit to BrainLift and run `/sb_pitch_review`.

---

## Project Structure

```
.
├── CLAUDE.md                      # Claude's instructions and personality
├── README.md                      # This file
├── templates/
│   └── pitch-template.md         # Complete S0 pitch template
├── reference/
│   └── scoring-rubric.md         # Full grading rubric
└── examples/
    ├── good-pitch-example.md     # Complete example of a PASS-grade pitch
    └── section-examples.md       # Good vs Needs Work for each section
```

---

## What Makes This Different

### Claude Becomes Your Pitch Coach
When working in this project, Claude:
- Acts as a world-class VC and education operator
- Writes in plain English (no jargon or buzzwords)
- Quotes your exact words when giving feedback
- Provides multiple rewrite options
- Pushes back on vague or unmeasurable claims
- Grades using the official SuperBuilders rubric

### Focus on Outcomes, Not Features
Claude will help you:
- Define measurable, time-bound learning outcomes
- Avoid engagement vanity metrics
- Include delayed retention checks (forty-eight hours)
- Set clear green/yellow/red thresholds
- Build auditable measurement plans

### Business-Sense Checks
Claude runs the same audit a top VC would:
- Is the Why Now external or internal?
- Is the first audience reachable this month?
- Can operators set up in fifteen minutes or less?
- Is there real evidence or just anecdotes?
- Do the unit economics support pilot-to-paid transition?

---

## Key Requirements for S0 Pitches

### Non-Negotiable
1. **K-12 only**: Anything outside K-12 is excluded
2. **Measurable outcome**: Must be learning-focused, numeric, time-bound (thirty days or less)
3. **All five sections**: One-liner, ICP, Strategic Narrative, Distribution, Measurable Outcome, Assumptions
4. **Plain English**: No jargon, no abbreviations, clarity over brevity

### What Makes a Great Pitch
- Specific ICP with inclusion AND exclusion rules
- School category specified (Alpha school or sister schools)
- Measurable outcome with all five components (metric, target, time window, measurement plan, thresholds)
- External Why Now (not "we have traction")
- Evidence over anecdotes (pilot data, not just quotes)
- Testable assumptions with one-week checks

---

## Common Mistakes to Avoid

1. **Feature soup**: Listing ten features instead of focusing on core value
2. **Engagement as outcome**: Time on platform is an input, not a learning outcome
3. **Vague metrics**: "Improve learning" instead of "double mastery speed within thirty days"
4. **No exclusions in ICP**: "All schools" instead of specific grade/subject/setting with explicit out-of-scope
5. **Internal Why Now**: "We have funding" instead of "AI costs dropped from five dollars to fifty cents per student"
6. **Quotes as proof**: "Teachers love it" instead of "one point four times faster on released items in four-week pilot"
7. **Long time windows**: "Over the school year" instead of "within thirty days"
8. **Unmeasurable claims**: "Students will achieve their potential" instead of "eighty percent on post-test with seventy-five percent delayed retention"

---

## Files and Resources

### templates/pitch-template.md
Your starting point. A complete template with:
- All required sections
- Inline instructions and examples
- Pre-submission checklist
- Guidance on what to include

### reference/scoring-rubric.md
The official rubric showing:
- How each section is graded (Great / Good / Needs Work / Fail)
- What makes outcomes acceptable vs unacceptable
- VC business-sense audit criteria
- Overall PASS / REVISE / FAIL criteria

### examples/good-pitch-example.md
A complete example pitch (FractionFlow) that would receive a PASS grade, showing:
- All sections properly completed
- Specific, measurable outcomes
- Clear ICP with exclusions
- Evidence-based proof
- Testable assumptions
- Why it would pass

### examples/section-examples.md
Side-by-side comparisons for each section:
- Great examples with explanations
- Needs Work examples with explanations
- How to fix common problems
- Quick reference table

---

## How Claude Will Help You

### When Starting Fresh
Claude will:
1. Walk you through the template section by section
2. Ask clarifying questions to sharpen your thinking
3. Push back when something is vague
4. Offer specific examples from the reference files
5. Help you avoid common pitfalls

### When Reviewing a Draft
Claude will:
1. Grade each section using the rubric
2. Provide an overall S0 verdict (PASS / REVISE / FAIL)
3. Give five to eight top pushbacks with quotes from your draft
4. Ask five to ten key questions to improve clarity
5. Provide multiple rewrite options for sections that need work

### Throughout the Process
Claude will:
- Keep you focused on measurable outcomes
- Ensure K-12 focus
- Check for plain English (no jargon)
- Verify all five sections are complete
- Run the VC business-sense audit
- Confirm you are ready to submit

---

## Grading System

Each section receives a grade:
- ✅ **Great**: Exemplary, clear, specific, actionable
- ✔️ **Good**: Solid, meets requirements with minor improvements possible
- ⚠️ **Needs Work**: Present but requires significant improvement
- ❌ **Fail**: Missing, vague, or fundamentally flawed

Overall S0 status:
- **PASS**: No Fail anywhere and Measurable Outcome is Great or Good
- **REVISE**: Any Needs Work in One-liner or Measurable Outcome, or several Needs Work items
- **FAIL**: Missing outcome, vague metrics, or fatal business-sense issue

---

## Example Conversation Flows

### Starting from Scratch
```
You: "I want to create a new S0 pitch for my reading comprehension tool."

Claude: "Great! Let's start with your one-liner. Can you tell me:
- Who specifically you are serving (grade band, subject, type of school)?
- What specific pain point or trigger they have?
- What measurable learning outcome you will deliver and by when?
- What is your approach in one short phrase?"

You: [Provides answers]

Claude: [Gives feedback, offers rewrites, helps you craft both one-liner formats]
```

### Reviewing a Draft
```
You: "I have a draft pitch. Can you review it?" [Pastes draft]

Claude: [Reads and analyzes]

"I've reviewed your pitch. Here is my assessment:

S0 Verdict: REVISE
Your pitch has a solid foundation, but the measurable outcome needs to be much more specific, and the ICP needs exclusion rules.

Section Grades:
- One-liner: ✔️ Good — Clear structure but outcome could include a numeric target
- ICP: ⚠️ Needs Work — Inclusion rules are present but no exclusions listed
- Strategic Narrative: ✔️ Good — Why Now is mostly external, Proof could be more specific
- Distribution: ✅ Great — Platform and access path are clear
- Measurable Outcome: ⚠️ Needs Work — Missing time window and thresholds
- Assumptions: ✅ Great — Testing plans are specific and time-bound

Top Pushbacks:
[Provides 5-8 specific pushbacks with quotes]

Key Questions:
[Asks 5-10 clarifying questions]

Edits and Upgrades:
[Provides rewrite options for each section that needs work]"
```

---

## Tips for Success

### Be Specific
- "Grades six through eight math teachers" not "educators"
- "Twice as fast" not "faster"
- "Within thirty days" not "soon"
- "Eighty percent on post-test" not "improved scores"

### Use Numbers
- Target numbers (two times, twenty-point gain)
- Sample sizes (sixty students, three classrooms)
- Timeframes (fifteen days, forty-eight hours)
- Thresholds (seventy-five percent, ninety percent)

### Write for Humans
- Full sentences, not telegraphic bullets
- Plain English, not jargon
- "Percent" not "%"
- Numbers under ten spelled out
- No abbreviations (write "version one" not "v1")

### Focus on Learning
- Mastery speed, not time on platform
- Retention after forty-eight hours, not completion rates
- Growth on assessments, not engagement scores
- Teacher time saved WITHOUT worse learning outcomes

### Be Honest
- Include exclusions (where your approach will NOT work)
- List real risks and how you will test them
- Provide evidence (pilot data, not just passion)
- Set realistic targets you can actually measure

---

## Submission Process

When your pitch is ready:

1. **Final check with Claude**: "Is my pitch ready to submit?"

2. **Claude confirms**: You will receive a PASS verdict with confirmation all sections are complete

3. **Create structure in BrainLift**: Add under BrainLift root node: **Business Validation ▸ S0**

4. **Copy content**: Transfer your completed pitch from this project to BrainLift

5. **Run review**: In your project's Ephor project, run `/sb_pitch_review` with the entire Business Validation section

6. **Iterate if needed**: If Ephor provides feedback, work with Claude to address it

7. **Final approval**: Tag AI Manager in the SuperBuilder Project sheet when you pass all criteria

---

## Getting Help

### Ask Claude Questions
- "Can you explain what makes a good measurable outcome?"
- "Is my ICP specific enough?"
- "What are examples of external Why Now factors?"
- "How do I write a testable assumption?"
- "Can you help me improve this section?"

### Reference the Example Files
- "Show me the good pitch example"
- "What is an example of a great one-liner?"
- "Can you compare my strategic narrative to the examples?"

### Request Specific Help
- "Can you give me multiple options for my one-liner?"
- "Help me add exclusion rules to my ICP"
- "My outcome is vague. Can you help me make it measurable?"
- "What questions would a VC ask about my pitch?"

---

## Philosophy

This project embodies a specific philosophy about pitches:

### Clarity Over Cleverness
A teacher or parent should understand your pitch immediately. If they do not, rewrite it.

### Outcomes Over Features
Learning outcomes matter. Time on platform does not. Focus on what students will know or be able to do.

### Evidence Over Aspiration
Pilot data beats passion. Released items beat testimonials. Delayed retention checks beat immediate scores.

### Specificity Over Scale
Serve grades six through eight math teachers in charter schools incredibly well. Do not try to serve "all educators."

### Honesty Over Hype
List what is out of scope. Acknowledge real risks. Set realistic targets. Build trust through transparency.

---

## Success Criteria

You know you are done when:

1. All five sections are complete with specific details
2. Your measurable outcome includes metric, target, time window, measurement plan, and thresholds
3. Your ICP has both inclusion AND exclusion rules
4. Your Why Now is external (not "we have users")
5. Your proof is evidence-based (pilot data, advisor credentials)
6. Your assumptions have one-week tests
7. Everything is written in plain English
8. A teacher or parent could understand it immediately
9. Claude gives you a PASS verdict
10. You feel confident submitting

---

## Technical Notes

### This is a Claude Code Project
The CLAUDE.md file tells Claude how to act when working in this directory. You do not need to explain the rubric or requirements each time. Claude already knows them.

### Files are References, Not Scripts
The template and examples are guides. Claude uses them to coach you but adapts to your specific project.

### Iteration is Expected
Your first draft will not be perfect. Work with Claude to refine each section. That is the point.

---

## Questions?

If you are stuck, just ask Claude:
- "I'm not sure where to start"
- "Can you help me with [section name]?"
- "Is this specific enough?"
- "What would make this better?"

Claude is here to help you create a pitch that passes.

---

## Project Metadata

- **Created**: 2025
- **Purpose**: Help SuperBuilders founders create exceptional S0 pitches
- **Scope**: S0 stage only (one-day pitch creation)
- **Focus**: K-12 education projects
- **Outcome**: PASS-grade pitches ready for BrainLift submission

---

**Ready to build your pitch? Say "Let's start" to Claude.**
