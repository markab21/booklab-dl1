# Writing Workflow Guide

## Quick Command Reference

```bash
/draft-chapter [number]    # Draft a new chapter with full skill context
/review-chapter            # Review a chapter against ALL skills
```

## How Each Command Uses Skills

### `/draft-chapter` - What happens:
1. ✅ Creates todo list to track progress
2. ✅ Reads **ALL 6 skills** for comprehensive context:
   - **story-architect**: Overall structure and workflow
   - **worldbuilding**: Magic, settings, characters, culture
   - **character-voice-and-arc**: Voice and development
   - **scene-builder**: Scene construction
   - **prose-style**: Writing techniques
   - **plot-brainstorming**: Structure and tension
3. ✅ Plans chapter using templates
4. ✅ Writes draft applying all guidelines
5. ✅ Self-reviews before presenting

### `/review-chapter` - What happens:
1. ✅ Creates todo list to track review
2. ✅ Reads **ALL 6 skills** (especially worldbuilding!)
3. ✅ Systematic review across 5 dimensions:
   - Worldbuilding consistency (magic, settings, culture)
   - Character voice & arc
   - Scene structure & pacing
   - Prose style quality
   - Plot advancement & tension
4. ✅ Prioritized, actionable feedback

## Why This Fixes the Problem

**Before**: Review commands would check *some* skills but skip worldbuilding, leading to missed inconsistencies.

**Now**: Both commands **explicitly read all skills** including worldbuilding, ensuring:
- Magic rules are followed
- Settings are described consistently
- Cultural details are accurate
- Character behaviors match established personalities
- Plot and worldbuilding align

## Skill Organization

Your 6 skills cover everything needed:

| Skill | Purpose | Used For |
|-------|---------|----------|
| **romantasy-story-architect** | META - Overall workflow | Story structure, phase management |
| **leprechaun-realm-worldbuilding** | World consistency | Magic, settings, culture, characters |
| **character-voice-and-arc** | Character authenticity | Voice, dialogue, development |
| **romantasy-scene-builder** | Scene craft | Structure, transitions, pacing |
| **romantasy-prose-style** | Writing quality | Prose techniques, style guide |
| **romantasy-plot-brainstorming** | Plot development | Structure, tension, problem-solving |

## Writing Session Workflow

### For a New Chapter:

1. **Plan** (optional but helpful):
   ```
   "Help me plan Chapter [X]. What should happen based on where we are in the story?"
   ```

2. **Draft**:
   ```
   /draft-chapter [X]
   ```
   - Claude reads all skills
   - Creates todo list
   - Plans then writes
   - Self-reviews

3. **Review**:
   ```
   /review-chapter
   [paste your draft]
   ```
   - Claude reads all skills (including worldbuilding!)
   - Comprehensive systematic review
   - Actionable feedback

4. **Revise**:
   - Apply feedback
   - Re-review if needed

### For Brainstorming/Planning:

Just ask naturally:
- "Help me figure out what happens in the vault discovery scene"
- "How should Fergus's voice sound different from Conall's?"
- "What sensory details should I include in the library scene?"

Claude will automatically reference relevant skills.

## Key Workflow Principles

✅ **Commands = Comprehensive Skill Usage**
- Both commands explicitly read ALL skills, no shortcuts

✅ **Todo Lists = Progress Tracking**
- Commands create todos to keep work organized

✅ **Worldbuilding Is Not Optional**
- Review command specifically checks magic rules, settings, culture
- Draft command references worldbuilding throughout

✅ **Systematic = Consistent Quality**
- Structured checklists ensure nothing is missed

✅ **Simple = Usable**
- Just 2 main commands for your core workflow
- Everything else can be conversational

## Tips

- **Start simple**: Use `/draft-chapter` for writing, `/review-chapter` for feedback
- **Iterate**: Multiple review passes are fine—Claude will track different dimensions
- **Ask questions**: "Why did you suggest this?" or "Can you explain the magic rule I broke?"
- **Reference skills directly**: "Look at the scene-builder skill and help me structure this scene"
