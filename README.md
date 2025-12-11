# Biblical Scene Specialist

> **AI-powered biblical character research and visualization system for Sunday school education. Generates age-appropriate, historically accurate image prompts for ages 5-12.**

[![Version](https://img.shields.io/badge/version-4.0-blue.svg)](https://github.com/joshikumar-ai/biblical-scene-specialist)
[![Audience](https://img.shields.io/badge/audience-ages%205--12-green.svg)](https://github.com/joshikumar-ai/biblical-scene-specialist)
[![Platforms](https://img.shields.io/badge/platforms-DALL--E%20%7C%20Midjourney%20%7C%20SD-orange.svg)](https://github.com/joshikumar-ai/biblical-scene-specialist)

---

## What This Does

**Input:** Any Bible character name (Moses, David, Ruth, Peter...)

**Output:** 
- Ranked scenes by teaching value
- Complete AI image prompts (DALL-E, Midjourney, Stable Diffusion)
- Historical context and character details
- Sunday school teaching integration
- Multilingual support (English, Telugu, Hindi)

---

## Quick Example

```
YOU: Moses

SYSTEM: 📖 BIBLICAL RESEARCH: Moses
        Testament: OT | Total Appearances: 847 verses

        🌟 SCENES RANKED BY TEACHING VALUE

        ⭐ SUNDAY SCHOOL PRIMARY [Ages 5-12]
        1. Baby Moses in Basket — Exodus 2:3 | Theme: God's Protection
        2. Burning Bush — Exodus 3:2-6 | Theme: God's Calling
        3. Parting Red Sea — Exodus 14:21-22 | Theme: Deliverance
        4. Ten Commandments — Exodus 31:18 | Theme: God's Law

        💡 RECOMMENDATION: Start with 1, 3, 4

YOU: RECOMMEND

SYSTEM: [Generates complete prompts for scenes 1, 3, 4 with:]
        - 150-250 word AI image prompts
        - Platform-specific versions (DALL-E/MJ/SD)
        - Historical context
        - Character descriptions with Middle Eastern ethnicity
        - Teaching points and discussion questions
        - Memory verses (trilingual)
```

---

## Key Features

### 🎯 Age-Appropriate Safety

Every prompt passes mandatory checklist:
- ✓ No violence, gore, or frightening imagery
- ✓ Middle Eastern ethnicity preserved
- ✓ Appropriate for 5-year-olds
- ✓ Clear teaching value

**Sensitive scenes auto-adapted:**
| Biblical Element | Sunday School Adaptation |
|------------------|--------------------------|
| Crucifixion | → Radiant cross with light rays |
| Battle scenes | → Before/after moments, not combat |
| Death events | → Peaceful, hopeful symbolism |

### 📚 Complete Prompt Packages

Each scene includes 8 sections:
1. **Metadata** — Scripture reference, theme, age rating
2. **Primary AI Prompt** — 150-250 words, platform-agnostic
3. **Platform Versions** — Optimized for DALL-E, Midjourney, SD
4. **Historical Context** — Time period, location, cultural details
5. **Character Details** — Ethnicity, clothing, expressions
6. **Setting Details** — Environment, lighting, color palette
7. **Composition Guidance** — Focal point, depth layers, symbolism
8. **Teaching Integration** — Discussion questions, memory verses

### 🌐 Multilingual Support

Commands: `TELUGU` | `HINDI`

Translates:
- Memory verses
- Discussion questions
- Teaching points

(AI prompts remain English for tool compatibility)

---

## Commands Reference

### Basic Commands
| Command | Function |
|---------|----------|
| `[Character name]` | Start research (Moses, David, Ruth...) |
| `1, 3, 5` | Generate specific scenes |
| `RECOMMEND` | Use AI recommendation |
| `ALL PRIMARY` | Generate all primary scenes |
| `FULL STORY` | 5-8 chronological scenes |

### Platform Commands
| Command | Function |
|---------|----------|
| `DALLE` | Optimize for DALL-E 3 |
| `MIDJOURNEY` | Optimize for Midjourney v6+ |
| `SD` | Optimize for Stable Diffusion XL |

### Advanced Commands
| Command | Function |
|---------|----------|
| `TELUGU` / `HINDI` | Translate teaching sections |
| `SERMON SERIES [theme]` | Multi-character thematic set |
| `EXPORT PDF` | Print-ready format |
| `ALTERNATIVES` | Different visual perspectives |

---

## Production Use Case

This system was used alongside the [Pixar Character System](https://github.com/joshikumar-ai/pixar-character-system) to create 30+ biblical characters for **Calvary Temple's Bible Exhibition 2025** (Hyderabad, India).

**Role in workflow:**
1. Biblical Scene Specialist → Research characters, select scenes
2. Pixar Prompt Generator → Apply character consistency
3. Stable Diffusion → Generate images
4. Final design → Exhibition-ready materials

---

## Technical Specifications

**Prompt Length Standards:**
- Primary prompt: 150-250 words
- DALL-E optimized: 300-400 characters
- Midjourney optimized: 200-300 words
- SD optimized: 250-350 words (weighted tokens)

**Quality Standards:**
- Historical accuracy: ±50 years for clothing/architecture
- Ethnographic precision: Specific regional heritage
- Theological review: Protestant non-denominational

**Platform Compatibility:**
- DALL-E 3 (primary)
- Midjourney v6+
- Stable Diffusion XL

---

## Repository Contents

```
biblical-scene-specialist/
├── README.md                           # This file
└── biblical_scene_specialist_v4.md     # Complete system
```

---

## Related Systems

- [Pixar Character System](https://github.com/joshikumar-ai/pixar-character-system) — Character consistency for AI images
- [Prompt Architect v6.0](https://github.com/joshikumar-ai/meta-prompt-system) — Prompt engineering framework
- [Expert Prompt Critique v5.1](https://github.com/joshikumar-ai/prompt-critic-system) — Quality assessment

---

## Author

**Joshi Kumar N**  
AI Systems Architect | Hyderabad, India

📧 joshi.ai.architect@gmail.com  
💼 [LinkedIn](https://linkedin.com/in/joshi-kumar-ai)  
🐙 [GitHub](https://github.com/joshikumar-ai)

---

## Version History

| Version | Changes |
|---------|---------|
| v4.0 | Progressive disclosure architecture, quick-start path |
| v3.0 | Multilingual support, export formats, session tracking |
| v2.0 | Mandatory safety checklist, platform optimizations |
| v1.0 | Initial release |

---

*Built for Sunday school teachers who want professional biblical illustrations without design expertise.*
