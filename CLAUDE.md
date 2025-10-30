# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This project is focused on transforming a book idea into a complete novel through a structured waterfall progression system. The goal is to create schema and tools to facilitate this creative development process.

## MCP Configuration

The project uses the Context7 MCP server (configured in `.mcp.json`) for enhanced context capabilities.

## Skill Development Workflow

### 1. Understanding Skills Structure

Skills are located in `.claude/skills/` directory. Each skill is a specialized knowledge module for specific aspects of novel development.

**Path Structure**: `.claude/skills/<skill-folder>/SKILL.md`

**Available Skills:**
- **character-voice-and-arc** (`.claude/skills/character-voice-and-arc/SKILL.md`): Character development, voice consistency, and emotional arc tracking
- **leprechaun-realm-worldbuilding** (`.claude/skills/leprechaun-realm-worldbuilding/SKILL.md`): Fantasy world construction and magical systems
- **romantasy-plot-brainstorming** (`.claude/skills/romantasy-plot-brainstorming/SKILL.md`): Plot development for romantic fantasy
- **romantasy-prose-style** (`.claude/skills/romantasy-prose-style/SKILL.md`): Writing style guidelines and prose techniques
- **romantasy-scene-builder** (`.claude/skills/romantasy-scene-builder/SKILL.md`): Scene construction framework with dialogue and pacing

Each `SKILL.md` file contains:
- Metadata (YAML frontmatter with name and description)
- Comprehensive guidelines and frameworks
- Examples and templates
- Checklists and validation criteria

### 2. Skill Development Process

When developing or extending skills, follow this workflow:

#### A. Initial Assessment
1. Use `tree .claude -a` to see existing skills structure
2. Read the current skill file to understand existing content
3. Create a todo list to track development tasks
4. Identify gaps or areas for expansion

#### B. Content Development Strategy
1. **Start with Structure**: Outline major sections before writing
2. **Layer Complexity**: Begin with core concepts, add depth progressively
3. **Include Examples**: Every concept should have concrete examples
4. **Provide Templates**: Give actionable frameworks users can apply
5. **Add Checklists**: Include validation criteria for quality control

#### C. Iterative Enhancement Pattern
```
1. Review existing content
2. Identify next logical section
3. Add comprehensive content with:
   - Theoretical framework
   - Practical application
   - Examples from the story context
   - Do's and don'ts
   - Templates or formulas
4. Ensure consistency with other sections
5. Update any cross-references
```

### 3. Ideation and Expansion Guidelines

When ideating on skills:

#### Content Types to Include
- **Frameworks**: Structured approaches to tackle specific challenges
- **Techniques**: Specific methods with step-by-step instructions
- **Examples**: Multiple examples showing different applications
- **Templates**: Fill-in-the-blank structures for common scenarios
- **Checklists**: Validation points to ensure quality
- **Common Mistakes**: What to avoid and why
- **Advanced Techniques**: Progressive complexity for mastery

#### Section Development Order
1. **Core Concepts**: Fundamental principles
2. **Application Methods**: How to use the concepts
3. **Examples & Templates**: Concrete implementations
4. **Edge Cases & Variations**: Handling special scenarios
5. **Quality Checks**: Validation and refinement

### 4. Best Practices for Skill Updates

#### Do's:
- ✅ Maintain consistent formatting and structure
- ✅ Use clear headers and subheaders for navigation
- ✅ Include both theory and practical application
- ✅ Provide multiple examples for complex concepts
- ✅ Add cross-references between related sections
- ✅ Use formatting (bold, italics, code blocks) for clarity
- ✅ Include emotional and sensory details in examples
- ✅ Track progress with TodoWrite tool

#### Don'ts:
- ❌ Don't add content without examples
- ❌ Don't create sections without practical application
- ❌ Don't duplicate content across skills unnecessarily
- ❌ Don't forget to maintain the YAML metadata
- ❌ Don't add complexity without foundation

### 5. Quality Assurance

Before finalizing skill updates:
1. **Completeness**: Does each section have theory, practice, and examples?
2. **Consistency**: Does new content align with existing material?
3. **Clarity**: Can someone apply this immediately?
4. **Context**: Do examples fit the romantasy leprechaun narrative?
5. **Progression**: Does content build logically from simple to complex?

## Development Status

### ✅ Completed Skills (4/6)

| Skill | Lines | Status | Key Features |
|-------|-------|--------|--------------|
| **romantasy-story-architect** | 550+ | ✅ Complete | **META-SKILL**: Three-phase workflow, decision checklists, chapter breakdown template, skill integration guides, session scripts |
| **romantasy-scene-builder** | 450+ | ✅ Complete | Scene structures, dialogue techniques, emotional arcs, transitions, examples |
| **character-voice-and-arc** | 550+ | ✅ Complete | Voice distinction, arc tracking, emotional mapping, practice exercises |
| **romantasy-prose-style** | 870+ | ✅ Complete | Show vs tell, Irish elements, sentence craft, sensual writing, love triangle prose, 15 exercises |

**Total Completed Documentation**: ~2,420 lines

### 🟡 In Progress Skills (2/6)

| Skill | Lines | Status | What's Done | What's Needed |
|-------|-------|--------|-------------|---------------|
| **leprechaun-realm-worldbuilding** | 391 | 🟡 70% | Succession law, characters, vault/prophecy, magic basics, settings, plot points | Expanded magic mechanics, deeper politics, cultural traditions, consequences framework |
| **romantasy-plot-brainstorming** | 453 | 🟡 70% | Three-act structure, romance beats, brainstorming basics, subplots, pacing | More techniques, chapter breakdown, subplot integration, tension tracking |

**Total In-Progress Documentation**: ~844 lines

### 📊 Overall Progress

- **Total Skills**: 6
- **Completion Rate**: 67% of core skill development (4/6 complete)
- **Total Documentation**: 3,200+ lines
- **Next Priority**: Complete worldbuilding and plot-brainstorming skills

### 🎯 Remaining Work

**Priority 1: Complete In-Progress Skills**
- [ ] Expand `leprechaun-realm-worldbuilding` (estimated +200 lines)
  - Magic system mechanics and costs
  - Realm politics and factions depth
  - Setting descriptions (specific rooms, landmarks)
  - Cultural traditions and customs
  - Magical consequences framework

- [ ] Expand `romantasy-plot-brainstorming` (estimated +150 lines)
  - Advanced brainstorming techniques
  - Chapter-by-chapter breakdown template
  - Subplot integration strategies
  - Tension tracking tools
  - Plot problem-solving techniques

**Priority 2: Schema & Waterfall System**
- [ ] Design schema for waterfall progression tracking
- [ ] Define stages from concept to manuscript
- [ ] Create validation criteria for each stage
- [ ] Build transition checkpoints between stages

**Priority 3: Integration & Workflow**
- [ ] Skill integration system (how skills work together)
- [ ] Cross-skill consistency checking
- [ ] Version control for manuscript iterations

**Priority 4: Future Skills (Lower Priority)**
- `revision-strategies`: Structured editing approaches
- `beta-reader-integration`: Feedback incorporation methods
- `publishing-preparation`: Final manuscript preparation
- `chapter-drafting`: Chapter-level writing framework

## Usage Instructions

When working on this project:
1. Start by reviewing existing skills in `.claude/skills/`
2. Use the skill frameworks when developing story content
3. Extend skills based on emerging needs during writing
4. Maintain consistency with the romantasy leprechaun theme
5. Document new patterns and techniques as they emerge
