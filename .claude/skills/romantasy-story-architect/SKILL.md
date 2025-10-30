# Romantasy Story Architect: Master Guide

## SKILL METADATA
```yaml
---
name: romantasy-story-architect
description: Meta-guide for coordinating all romantasy writing skills, completing decision points, and managing the novel development workflow from concept to manuscript
---
```

## What This Skill Does

The **Story Architect** is your master coordinator. It doesn't teach you *how* to write—the other skills do that. Instead, it shows you:

1. **How all skills work together** as an integrated system
2. **Which decisions you need to make** to complete your story
3. **The workflow** from blank page to finished manuscript
4. **How to fill in the blanks** in worldbuilding and plot skills
5. **When to use which skill** during your writing process

Think of this as the **instruction manual for your romantasy writing toolkit**.

---

## Your Skill Architecture

### Current Skills Overview

```
.claude/skills/
│
├── romantasy-story-architect/       ← YOU ARE HERE
│   └── SKILL.md                     ← Master guide
│
├── REFERENCE SKILLS (Complete - Use As-Is)
│   ├── romantasy-prose-style/
│   │   └── SKILL.md                 ← How to write romantasy prose
│   ├── romantasy-scene-builder/
│   │   └── SKILL.md                 ← How to structure scenes
│   └── character-voice-and-arc/
│       └── SKILL.md                 ← Character development
│
└── YOUR STORY SKILLS (Need Completion)
    ├── leprechaun-realm-worldbuilding/
    │   └── SKILL.md                 ← Fill in YOUR world details
    └── romantasy-plot-brainstorming/
        └── SKILL.md                 ← Fill in YOUR plot decisions
```

### How Skills Are Different

**Reference Skills** (Complete):
- Generic romantasy guidance
- Use as templates and examples
- Techniques apply to any story
- No decisions needed—just reference them

**Story Skills** (Need Your Input):
- Specific to YOUR leprechaun story
- Have decision points marked `[TBD]` or `[Choose name]`
- Need YOU to fill in the blanks
- Contain YOUR world rules and plot choices

---

## The Three-Phase Workflow

### Phase 1: Story Foundation (Decision-Making)

**Goal**: Complete all decision points in your story skills

**Skills to Complete**:
1. `leprechaun-realm-worldbuilding` - Define your world
2. `romantasy-plot-brainstorming` - Answer plot questions

**How to Do This**: Work through the Decision Points Checklist (below)

**Duration**: 2-5 focused sessions with Claude

**Output**: All `[TBD]` and `[Choose name]` filled in with YOUR decisions

---

### Phase 2: Story Architecture (Planning)

**Goal**: Create your chapter-by-chapter outline

**Create**: `chapter-breakdown.md` in project root

**How to Do This**:
1. Use completed worldbuilding skill
2. Use completed plot-brainstorming skill
3. Follow the Chapter Breakdown Template (below)

**Duration**: 1-3 sessions

**Output**: Complete 30-35 chapter outline

---

### Phase 3: Story Execution (Writing)

**Goal**: Write your manuscript chapter by chapter

**How to Do This**:
1. Start each chapter by referencing `chapter-breakdown.md`
2. Use ALL skills simultaneously:
   - Worldbuilding for consistency
   - Character-voice for dialogue
   - Scene-builder for structure
   - Prose-style for writing technique

**Duration**: Ongoing (the actual writing)

**Output**: Your novel, chapter by chapter

---

## Phase 1 Deep Dive: Completing Decision Points

### Worldbuilding Skill Decision Checklist

Open `.claude/skills/leprechaun-realm-worldbuilding/SKILL.md` and work through these:

#### Character Decisions

**The Uncle (Conall)**:
- [x] Name: Conall ✓ (already decided)
- [x] NYC Business: Private Banking ✓ (already decided)
- [ ] Physical description details (eye color, specific features, signature style)
- [ ] Amulet appearance and how it works specifically
- [ ] His emotional vulnerabilities (what breaks his control?)
- [ ] His genuine motivation beyond power

**The Nephew (Fergus)**:
- [x] Name: Fergus ✓ (already decided)
- [ ] Specific physical scars/marks (from what?)
- [ ] His greatest fear
- [ ] What he does when he's alone
- [ ] His relationship with the land (specific abilities)
- [ ] Bar/pub he frequents (name, location)

**The Protagonist (Brigid)**:
- [x] Name: Brigid ✓ (already decided)
- [ ] Her NYC apartment details (neighborhood, style)
- [ ] Her fashion sense (practical? Stylish? Mix?)
- [ ] What she does for fun in NYC
- [ ] Her family background (parents alive? Relationship?)
- [ ] First sign of magic awakening (specific moment)

**Fergus's Ex** (Book 2 Setup):
- [ ] Name: [Choose Irish name]
- [ ] Appearance: [Describe - beautiful but how?]
- [ ] Her role in leprechaun court
- [ ] Why she thought she'd be queen
- [ ] Her magical specialty

#### Magic System Decisions

Current: Basic framework exists

**Needs Decision**:
- [ ] **Magic Costs**: What does using big magic cost? (Energy? Life force? Emotional toll?)
- [ ] **Power Limitations**: What CAN'T leprechaun magic do?
- [ ] **Brigid's Magic Specifics**:
  - [ ] What exactly are her elemental powers? (Fire? Earth? All elements?)
  - [ ] What's her binding magic? (Can she bind people? Objects? Promises?)
  - [ ] What's her healing magic? (Physical wounds? Emotional? Magical damage?)
- [ ] **Learning Curve**: Can she control magic immediately or need training?
- [ ] **Visual Signature**: What color/appearance is her magic? Fergus's? Conall's?

#### Realm Politics Decisions

Current: Basic council structure exists

**Needs Decision**:
- [ ] **Noble Houses**: How many? Name them. What does each represent?
- [ ] **The Council**: How many members? How is representation decided?
- [ ] **Voting/Decision Process**: Unanimous? Majority? Weighted votes?
- [ ] **Fergus's Father's Death**: How exactly did he die? (Assassination? Magical disease? Accident?)
- [ ] **Timeline**: How long has Fergus been managing the realm?

#### Setting Details

Current: Basic estate description exists

**Needs Decision**:
- [ ] **Gleann Scáth Rooms**: Name and describe:
  - [ ] Library (where almost-kiss happens)
  - [ ] Brigid's bedroom
  - [ ] Ballroom (formal reception)
  - [ ] Kitchen/dining
  - [ ] Fergus's personal space
  - [ ] Conall's office
  - [ ] Hidden entrances to fae realm
- [ ] **The Vault Location**: Where is it physically? How is it hidden?
- [ ] **The Field** (where Brigid/Fergus consummate): Specific location, what makes it special?
- [ ] **The Pub** (first meeting): Name, village name, what's it like inside?

#### Cultural Traditions

Current: Minimal—NEEDS EXPANSION

**Needs Decision**:
- [ ] **Leprechaun Holidays/Celebrations**: What do they celebrate?
- [ ] **Marriage Traditions**: What makes a fae marriage binding?
- [ ] **Succession Ritual**: What exactly happens in the ceremony?
- [ ] **Food Culture**: What do leprechauns eat/drink that's special?
- [ ] **Music/Arts**: What entertains them?
- [ ] **Taboos**: What's forbidden? Why?

---

### Plot Skill Decision Checklist

Open `.claude/skills/romantasy-plot-brainstorming/SKILL.md` and work through these:

#### Core Plot Questions

Current: Framework exists

**Needs Decision**:
- [ ] **First Meeting Location**: The pub—exact location, how she gets there, why she's there
- [ ] **The Almost Sex Interruption**: Where are they? What exactly interrupts? Who finds them?
- [ ] **Forest Chase Details**: What triggers Brigid to run? Exactly what does she see/feel?
- [ ] **The Field Scene**: When in the story? What happens magically during?
- [ ] **Vault Discovery Trigger**: What causes them to find/access the vault?
- [ ] **Conall's Attack**: Where? When? What's his plan exactly?
- [ ] **The Battle**: Who else is there? What magic is used? How do they win?
- [ ] **Conall's Prison**: Where/what is it? Who guards it? Can he communicate from inside?

#### Chapter Breakdown Questions

**Needs Decision**:
- [ ] **Total Chapters**: 30? 35? 40?
- [ ] **POV Structure**: All Brigid? Some dual POV with Fergus/Conall?
- [ ] **Act Break Points**: Which chapters end Act 1 and Act 2?
- [ ] **Key Scene Placement**: Which chapter for:
  - [ ] The Proposal (NYC)
  - [ ] Arrival in Ireland
  - [ ] Meeting Fergus (pub)
  - [ ] First kiss (with whom?)
  - [ ] Amulet discovery
  - [ ] Forest reveal
  - [ ] The Field
  - [ ] Vault opening
  - [ ] The Battle
  - [ ] Resolution/coronation

#### Relationship Progression

**Needs Decision**:
- [ ] **Physical Intimacy Timeline** (Mark which chapters):
  - [ ] First touch (accidental)
  - [ ] First deliberate touch
  - [ ] First kiss (with whom?)
  - [ ] First intimate moment (where? With whom? How far?)
  - [ ] The Field scene (chapter #)
  - [ ] Any other intimate scenes
- [ ] **Emotional Beats** (Mark which chapters):
  - [ ] Brigid first doubts Conall
  - [ ] Brigid first trusts Fergus
  - [ ] Brigid discovers amulet
  - [ ] Brigid realizes she loves [chosen one]
  - [ ] Brigid makes final choice

---

## Working With Claude: Session Scripts

### Session Type 1: Decision-Making Session

**Use this script**:

```
PROMPT: "Let's complete the worldbuilding skill together. Start with
the Character Decisions section of the checklist in story-architect
skill. Ask me each decision point one by one, help me think through
the implications, then update the worldbuilding skill with my answers."
```

**What Claude will do**:
1. Open story-architect skill (this file)
2. Find the Character Decisions checklist
3. Ask you each question
4. Discuss implications and options
5. Update worldbuilding skill with your answer
6. Move to next question

**Example interaction**:
```
Claude: "The first unchecked item is Conall's physical description
details. We know he's dark, lean, sharp-featured. What about his
eye color?"

You: "Dark brown, almost black."

Claude: "Perfect. That plays into the darkness/control theme. What
about his signature style—does he have a specific look? Always wears
certain colors, particular jewelry besides the amulet?"

You: "Always black or charcoal suits. Expensive watch. No other jewelry
—the amulet is hidden under his shirt."

Claude: "Excellent. Updating worldbuilding skill now..."
```

### Session Type 2: Chapter Outline Creation

**Use this script**:

```
PROMPT: "Using my completed worldbuilding and plot-brainstorming skills,
let's create chapter-breakdown.md. Use the template from story-architect
skill. Let's plan 34 chapters in three acts."
```

**What Claude will do**:
1. Review your worldbuilding decisions
2. Review your plot decisions
3. Use the Chapter Breakdown Template (below)
4. Create chapter-breakdown.md with your structure
5. Ask for your input on key placement decisions

### Session Type 3: Writing Session

**Use this script**:

```
PROMPT: "Let's write Chapter [#] using chapter-breakdown.md and all
relevant skills. The chapter is: [chapter description from breakdown]."
```

**What Claude will do**:
1. Read chapter-breakdown.md for chapter goal
2. Reference worldbuilding for consistency
3. Reference character-voice for dialogue
4. Reference scene-builder for structure
5. Reference prose-style for writing technique
6. Write the chapter maintaining all your decisions

---

## Chapter Breakdown Template

Create this file: `chapter-breakdown.md`

```markdown
# Chapter Breakdown - [Your Book Title]

**Total Chapters**: 34
**POV**: Brigid (third person limited)
**Status**: ⬜ Planning | ⬜ Drafting | ⬜ Revising

---

## ACT ONE: Setup & Seduction
*Chapters 1-10 (~25%)*

**Ch 1: [Title]** - [One-sentence description]
- Location:
- POV:
- Key beats:
- Emotional arc:
- Status: ⬜ Outlined | ⬜ Drafted | ⬜ Revised | ⬜ Final

**Ch 2: [Title]** - [One-sentence description]
- Location:
- POV:
- Key beats:
- Emotional arc:
- Status: ⬜ Outlined | ⬜ Drafted | ⬜ Revised | ⬜ Final

[Continue for all Act 1 chapters]

---

## ACT TWO: Escalation & Revelation
*Chapters 11-25 (~50%)*

**Ch 11: [Title]** - [One-sentence description]
[Same format]

**MIDPOINT** (Chapter ~17): [Major revelation]

[Continue for all Act 2 chapters]

---

## ACT THREE: Choice & Climax
*Chapters 26-34 (~25%)*

**Ch 26: [Title]** - [One-sentence description]
[Same format]

**CLIMAX** (Chapter ~32-33): [The battle and choice]

[Continue for all Act 3 chapters]

---

## Key Scenes Placement

| Scene | Chapter # | Status |
|-------|-----------|--------|
| The Proposal | Ch 3 | ⬜ |
| Meeting Fergus (Pub) | Ch 6 | ⬜ |
| First Kiss (with ?) | Ch ? | ⬜ |
| Amulet Discovery | Ch ? | ⬜ |
| Forest Reveal | Ch ? | ⬜ |
| The Field | Ch ? | ⬜ |
| Vault Opening | Ch ? | ⬜ |
| Conall's Attack | Ch ? | ⬜ |
| The Battle | Ch 32 | ⬜ |
| Resolution | Ch 34 | ⬜ |

---

## Writing Progress

- Total Chapters: 34
- Outlined: 0/34
- Drafted: 0/34
- Revised: 0/34
- Final: 0/34

**Current Chapter**: [#]
**Target Completion**: [Date]
**Daily/Weekly Goal**: [Words/Chapters]
```

---

## Skill Integration: How They Work Together

### When Writing a Scene

**You'll reference multiple skills simultaneously:**

```
SCENE: Brigid and Fergus in the library (almost-kiss, interrupted)

USE:
├─ chapter-breakdown.md
│  └─ "Chapter 14: Library Tension - They almost kiss, Conall interrupts"
│
├─ leprechaun-realm-worldbuilding
│  ├─ Library description (you filled this in!)
│  ├─ Fergus's physical details and mannerisms
│  └─ Conall's possessive behavior patterns
│
├─ character-voice-and-arc
│  ├─ Fergus's dialogue patterns (teasing, Irish phrases)
│  ├─ Brigid's internal conflict voice
│  └─ Emotional arc: Both moving from tension → desire
│
├─ romantasy-scene-builder
│  ├─ Almost-kiss scene structure
│  ├─ Interruption technique
│  └─ Aftermath handling
│
└─ romantasy-prose-style
   ├─ Building tension through prose
   ├─ Sensual writing techniques
   ├─ Irish flavor (a ghrá, etc.)
   └─ Show don't tell for desire
```

**Result**: A scene that:
- ✅ Matches your chapter outline
- ✅ Uses your world/character details
- ✅ Maintains character voices
- ✅ Follows proven scene structure
- ✅ Uses sophisticated prose techniques

### When Revising

**Check each skill for consistency:**

```
REVISION CHECKLIST:

□ Worldbuilding Consistency
  - Does magic work the same way throughout?
  - Are setting details consistent?
  - Do character descriptions match?
  - Are political rules followed?

□ Character Consistency
  - Does Fergus always talk like Fergus?
  - Does Brigid's internal voice stay true?
  - Do characters act according to their motivations?
  - Are emotional arcs progressing logically?

□ Scene Structure
  - Does each scene have clear goal/obstacle/outcome?
  - Is tension building appropriately?
  - Are transitions smooth?
  - Does pacing vary correctly?

□ Prose Quality
  - Am I showing, not telling?
  - Is sensual writing at the right level?
  - Are Irish elements used naturally?
  - Is sentence rhythm varied?
```

---

## Quick Reference: Which Skill When?

### Planning Stage
- **story-architect** (this): Overall workflow guidance
- **plot-brainstorming**: Structure your story arc
- **worldbuilding**: Make all world/character decisions

### Outlining Stage
- **story-architect**: Chapter breakdown template
- **plot-brainstorming**: Beat placement
- **worldbuilding**: Scene locations and details

### Drafting Stage (Every Chapter)
- **chapter-breakdown.md**: What happens this chapter
- **worldbuilding**: Setting, character, magic consistency
- **character-voice**: Dialogue and internal monologue
- **scene-builder**: Scene structure and flow
- **prose-style**: Writing techniques

### Revision Stage
- **story-architect**: Consistency checklist
- All skills: Check against established rules

---

## Common Workflows

### Workflow 1: "I'm just starting"

```
1. Session 1: Complete worldbuilding character decisions
2. Session 2: Complete worldbuilding magic/realm decisions
3. Session 3: Complete worldbuilding setting/culture decisions
4. Session 4: Complete plot-brainstorming key questions
5. Session 5: Create chapter-breakdown.md (34 chapters)
6. Session 6+: Start writing Chapter 1
```

### Workflow 2: "I have ideas but need structure"

```
1. Dump all ideas into worldbuilding and plot skills
2. Use story-architect checklists to find gaps
3. Fill in missing decisions
4. Create chapter-breakdown.md
5. Start writing
```

### Workflow 3: "I'm stuck mid-draft"

```
1. Check chapter-breakdown.md - are you on track?
2. Review worldbuilding - have you violated any rules?
3. Check character-voice - are characters acting consistently?
4. Review plot-brainstorming - where should you be emotionally?
5. Use scene-builder to structure the next scene
```

---

## Skill Maintenance

### When to Update Skills

**Update worldbuilding skill when**:
- You discover new world details while writing
- You make a rule clarification
- You add new locations/characters

**Update character-voice skill when**:
- A character's voice evolves
- You discover new mannerisms
- Emotional arcs shift

**Update chapter-breakdown.md when**:
- You split a chapter
- You realize you need more/fewer chapters
- Chapter content changes significantly

### How to Update

```
PROMPT: "I just realized [new detail] while writing Chapter 12.
Update the [skill name] to include this and check if it conflicts
with anything already established."
```

Claude will:
1. Add the new detail to the correct skill section
2. Check for conflicts with existing decisions
3. Flag any inconsistencies
4. Suggest adjustments if needed

---

## Tips for Success

### Do's ✅

- **Make decisions early**: Don't leave blanks for "later"
- **Trust your gut**: First answer is often best
- **Stay consistent**: Check skills before making changes
- **Update as you go**: Don't wait until revision to update skills
- **Use chapter-breakdown.md**: Keep it current and reference it always

### Don'ts ❌

- **Don't leave skills incomplete**: Fill in ALL decision points
- **Don't contradict yourself**: Check worldbuilding before adding new rules
- **Don't skip the outline**: chapter-breakdown.md saves you later
- **Don't ignore reference skills**: They're full of useful techniques
- **Don't change major decisions mid-draft**: Finish draft, then revise if needed

---

## Next Steps

### If you haven't started:

1. **Read this entire skill** (you just did! ✓)
2. **Open worldbuilding skill** and start with Character Decisions
3. **Work through decision checklists** with Claude (one session per section)
4. **Complete plot-brainstorming decisions**
5. **Create chapter-breakdown.md**
6. **Write Chapter 1** using all skills

### If you're mid-process:

1. **Check which decisions are still `[TBD]`** in your story skills
2. **Complete any missing decisions** before writing further
3. **Verify chapter-breakdown.md exists** and is up to date
4. **Resume writing** with confidence

### If you're revising:

1. **Use the revision checklist** above
2. **Check each chapter against chapter-breakdown.md**
3. **Verify consistency** with worldbuilding and character skills
4. **Polish using prose-style** techniques

---

## Summary

**This skill is your master control panel.**

- **Phase 1**: Fill in story decision blanks → Complete worldbuilding & plot skills
- **Phase 2**: Create chapter outline → Build chapter-breakdown.md
- **Phase 3**: Write your novel → Use ALL skills simultaneously

**Remember**:
- Reference skills = templates (use as-is)
- Story skills = YOUR decisions (fill in blanks)
- chapter-breakdown.md = YOUR roadmap (create and maintain)

**You have everything you need. Now make the decisions and write your story!**
