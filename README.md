<div align="center">

<img src="https://img.shields.io/badge/Claude-AI%20Skills-da7756?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude AI Skills"/>
<img src="https://img.shields.io/badge/Skills-3%20Included-191919?style=for-the-badge" alt="3 Skills"/>
<img src="https://img.shields.io/badge/Made%20by-TechGVS-da7756?style=for-the-badge&logo=youtube&logoColor=white" alt="TechGVS"/>
<img src="https://img.shields.io/badge/Works%20on-Claude.ai%20Web-F0ECE0?style=for-the-badge&logo=googlechrome&logoColor=da7756" alt="Claude Web"/>

<br/><br/>

# 🧠 Claude AI Custom Skills Pack
### by TechGVS

**3 powerful skills that give Claude a structured method — for deeper research, sharper thinking, and human-sounding writing.**

[📺 Watch Tutorial](#-video-tutorial) · [⚡ Quick Install](#-installation) · [📖 How to Use](#-how-to-use-each-skill) · [💡 Examples](#-real-results--examples)

</div>

---

## 📺 Video Tutorial

> **Watch the full step-by-step guide on how to download, install, and use these skills in Claude AI.**

<div align="center">

[![Watch TechGVS Tutorial on YouTube](https://img.youtube.com/vi/YOUR_VIDEO_ID/maxresdefault.jpg)](https://youtu.be/YOUR_VIDEO_ID)

**▶ Click the thumbnail above to watch on YouTube**

*Replace `YOUR_VIDEO_ID` with your actual YouTube video ID before publishing*

</div>

> 💡 **In the video you'll see:**
> - How to find the Skills tab in Claude (Customize → Skills)
> - How to upload a `.skill` ZIP file in under 60 seconds
> - Live demo of Deep Research vs regular Claude — side by side
> - Live demo of Deep Thinking frameworks applied to a real decision
> - Combined `/deep-research /deep-thinking` workflow in action

---

## 📦 What's Inside This Repo

| Skill File | Trigger Phrase | What It Does |
|-----------|---------------|-------------|
| `deep-research.skill` | `deep research on [topic]` | Runs a 5-phase structured research methodology with 5–12 web searches, source evaluation, and multi-perspective synthesis |
| `deep-thinking.skill` | `deep thinking about [topic]` | Applies 6 reasoning frameworks (Six Hats, Inversion, Steel Manning, Pre-Mortem, Second-Order Effects, Analogy) before answering |
| `humanizer.skill` | `humanize this text: [paste]` | Detects and removes 25 AI writing patterns — makes output sound genuinely human-written |

> **Use all three together** for research-backed, deeply-reasoned, human-sounding output.

---

## ⚡ Installation

### Step 1 — Download the skill files

Click the green **Code** button above → **Download ZIP**, then unzip.

Or download individual `.skill` files directly:

- [`deep-research.skill`](./deep-research.skill) ← Click to download
- [`deep-thinking.skill`](./deep-thinking.skill) ← Click to download
- [`humanizer.skill`](./humanizer.skill) ← Click to download

### Step 2 — Open Claude.ai on web

Go to **[claude.ai](https://claude.ai)** in your browser (desktop web — not mobile app).

> ⚠️ Skills require a **Pro, Max, Team, or Enterprise plan**. Free accounts cannot upload custom skills.

### Step 3 — Go to the Skills tab

```
Profile Icon → Settings → Customize → Skills
```

### Step 4 — Upload each skill

1. Click the **`+`** button (or `+ Create skill`)
2. Select **"Upload a ZIP file"**
3. Upload `deep-research.skill`
4. Claude reads the file and shows the skill name + description automatically
5. Repeat for `deep-thinking.skill` and `humanizer.skill`

### Step 5 — Toggle ON and start a new chat

Enable all three skills in your skills list. Open a **new chat** and try:

```
deep research on Claude AI custom skills
```

That's it. ✅

---

## 📖 How to Use Each Skill

### 🔬 Skill 1 — Deep Research

**Trigger phrases:**
```
deep research on [topic]
thoroughly research [topic]
do deep research on [topic]
comprehensive research [topic]
detailed research [topic]
in-depth analysis of [topic]
```

**What Claude does internally (5 phases):**

```
PHASE 1 → Query Decomposition
         Break topic into 5–8 sub-questions
         Plan 5+ different search angles

PHASE 2 → Multi-Angle Web Search
         Search from 7 angles: Direct, Expert, Counterpoint,
         Data, Comparison, Future, Case Study

PHASE 3 → Source Evaluation
         Rate each source: Authority + Recency + Bias + Cross-verification
         Discard weak sources silently

PHASE 4 → Synthesis
         Structure output: Overview → Key Findings → Multiple Perspectives
         → Data & Evidence → Limitations → Conclusion → Sources

PHASE 5 → Quality Check
         ✓ 5+ angles searched?  ✓ Opposing views included?
         ✓ Sources cited?  ✓ Gaps acknowledged?
```

**Output structure you'll always get:**
```
🔍 RESEARCH OVERVIEW
📊 KEY FINDINGS (with citations)
🔄 MULTIPLE PERSPECTIVES
   → Mainstream / Expert / Critical / Industry views
📈 DATA & EVIDENCE
⚠️  LIMITATIONS & GAPS
💡 SYNTHESIZED CONCLUSION
📚 SOURCES USED
```

---

### 🧠 Skill 2 — Deep Thinking

**Trigger phrases:**
```
deep thinking about [topic]
think deeply about [topic]
critically analyze [topic]
thorough analysis of [topic]
think step by step deeply [topic]
```

**What Claude does internally (5 steps):**

```
STEP 1 → Problem Clarification
         Restate the real question
         Identify hidden assumptions
         Define key terms precisely

STEP 2 → First Principles Breakdown
         What do we know for CERTAIN?
         What are we ASSUMING (that might be wrong)?

STEP 3 → Multi-Framework Analysis (choose 3+)
         🤍 White Hat  → Pure facts only
         🖤 Black Hat  → What could go wrong?
         💛 Yellow Hat → What are the benefits?
         💚 Green Hat  → Creative alternatives?
         🔄 Inversion  → How would you GUARANTEE failure?
         ⚔️ Steel Man  → Strongest version of opposing argument
         🔮 2nd+3rd Order Effects → Unintended consequences
         💀 Pre-Mortem → Imagine it failed — why?
         🔗 Analogy    → Where was this solved before?

STEP 4 → Synthesis
         Where do frameworks AGREE? → High confidence
         Where do they DISAGREE?   → Uncertain territory

STEP 5 → Action Implications
         If this is a decision — what should actually be done?
```

**Output structure you'll always get:**
```
🧠 DEEP THINKING ANALYSIS: [Topic]
   Problem Restated
   Hidden Assumptions Identified
   First Principles Foundation
   Multi-Framework Analysis
   Areas of High Confidence
   Areas of Uncertainty
   Synthesized Position
   What Would Change This Conclusion
   Action Implications
```

---

### ✍️ Skill 3 — Humanizer

**Trigger phrases:**
```
humanize this text: [paste your text]
make this sound more human: [paste]
remove AI writing from: [paste]
```

**What it detects and fixes (25 patterns):**

| Category | Patterns Fixed |
|----------|---------------|
| Content | Significance inflation, promotional language, vague attributions, formulaic "challenges" sections |
| Language | AI vocabulary words, copula avoidance ("serves as"), negative parallelisms, rule of three |
| Style | Em dash overuse, excessive bold, title case headings, emojis in text |
| Communication | Chatbot artifacts ("I hope this helps!"), sycophantic tone |
| Filler | "In order to", excessive hedging, generic positive conclusions |

> Based on [Wikipedia's Signs of AI Writing](https://en.wikipedia.org/wiki/Wikipedia:Signs_of_AI_writing) — maintained by WikiProject AI Cleanup.

---

## 💡 Real Results & Examples

### Deep Research — Before vs After

| | Without Skill | With Deep Research Skill |
|--|--------------|--------------------------|
| **Query** | "AI tools for students India" | Same query |
| **Approach** | Single-pass from training data | 5–12 web searches, 7 angles |
| **Output length** | ~300–500 words | ~900–1,400 words |
| **Sources cited** | Rarely | Always, with credibility notes |
| **Perspectives** | One (mainstream) | 4 (mainstream, expert, critical, industry) |
| **Limitations noted** | Never | Always |
| **Time** | Instant | 60–90 seconds |

---

### Deep Thinking — Before vs After

**Question:** *"Should I build a Flutter app or a web app for my startup?"*

**Without skill — typical Claude answer:**
> Flutter is great for mobile apps with native performance. Web apps are better for broad reach. Choose based on your target audience and team skills.

**With Deep Thinking skill — what you actually get:**

```
Problem Restated:
Real question = What platform maximises chances of startup success
given unknown constraints?

Hidden Assumptions:
→ Assuming "one platform first" is even the right approach
→ Assuming team has equal Flutter/web skill (probably not true)

Inversion (How to guarantee failure):
→ Pick Flutter without a mobile-first use case
→ Pick web without considering offline needs
→ Pick based on what you know, not what users need

Pre-Mortem:
→ Flutter: Failure mode = Web traffic you can't capture,
  slow iteration for non-native devs
→ Web: Failure mode = Poor mobile UX kills retention if
  product is inherently mobile

Second-Order Effects:
→ Flutter → App Store reviews build trust but slow shipping
→ Web → SEO-discoverable, faster MVP, but limited device access

Synthesized Position (High Confidence):
Web-first if: B2B / SaaS / content / discovery product
Flutter-first if: B2C / daily-use / offline / device sensors needed
```

---

### Combined Usage — Maximum Power

```
/deep-research /deep-thinking on [your topic]
```

Claude runs **Deep Research first** (collects real evidence via web search), then runs **Deep Thinking** on that actual data (not assumptions). This is the highest-quality workflow possible.

**Example:**
```
/deep-research /deep-thinking on whether Claude AI is better than
ChatGPT for Indian developers in 2026
```

You'll get: Multi-angle research with citations → First principles + 6 frameworks applied to the findings → Nuanced, evidence-based conclusion.

---

### Humanizer — Before vs After

**Before (AI-written):**
> This groundbreaking tool serves as a testament to the transformative potential of AI, marking a pivotal moment in the evolving technological landscape. It is not just about efficiency; it is about fostering innovation and underscoring the vital role of human-AI collaboration in today's dynamic environment.

**After (Humanized):**
> The tool speeds up repetitive tasks. Whether that actually changes how teams work depends on whether anyone on the team bothers to learn it properly — which, in my experience, is the bottleneck in most "AI transformation" stories.

---

## 🔗 Combined Trigger Reference

```bash
# Single skills
deep research on [topic]
deep thinking about [topic]
humanize this text: [paste text here]

# Combined (use both together)
/deep-research /deep-thinking on [topic]

# Gujarati triggers also work
deep research કરો [topic]
deep thinking કરો [topic]
```

---

## ❓ FAQ

**Q: Does this work on the free Claude plan?**
A: No. Custom Skills require Pro, Max, Team, or Enterprise plan. Code Execution must also be enabled in Settings → Feature Preferences.

**Q: Does this work on the Claude mobile app?**
A: Skills are managed via Claude.ai web. Once set up on web, they may work in mobile conversations — check current Anthropic documentation at [support.claude.com](https://support.claude.com).

**Q: Can I use all 3 skills at the same time?**
A: Yes. All 3 can be toggled ON simultaneously. Use the right trigger phrase and Claude applies whichever skill is relevant.

**Q: Are these files safe? Will they share my data?**
A: These `.skill` files are plain ZIP archives containing only a `SKILL.md` text file. No external calls, no data collection. Your skills are private to your account.

**Q: Can I edit these skills?**
A: Yes — unzip the file, edit `SKILL.md` in any text editor, re-zip, re-upload. Claude will use your modified version.

**Q: Will these skills work with Claude Code (terminal)?**
A: The Deep Research and Deep Thinking skills are designed for Claude.ai web. The Humanizer skill (`humanizer.skill`) was originally built for Claude Code and works in both environments.

---

## 📋 Requirements

| Requirement | Detail |
|-------------|--------|
| Platform | Claude.ai web (claude.ai) |
| Plan | Pro / Max / Team / Enterprise |
| Code Execution | Must be enabled in Settings |
| Setup time | ~2 minutes for all 3 skills |

---

## 📁 Repository Structure

```
claude-skills/
├── deep-research.skill      ← ZIP: deep-research/SKILL.md
├── deep-thinking.skill      ← ZIP: deep-thinking/SKILL.md
├── humanizer.skill          ← ZIP: humanizer/SKILL.md + README + LICENSE
└── README.md                ← This file
```

---

## 🙏 Credits

| Skill | Credit |
|-------|--------|
| `deep-research` | Built by **TechGVS** |
| `deep-thinking` | Built by **TechGVS** |
| `humanizer` | Originally by [@blader](https://github.com/blader/humanizer) — v2.3.0 |

---

## 📺 Subscribe to TechGVS

> If these skills helped you, **subscribe to TechGVS on YouTube** for more Claude AI tips, smart tricks, and AI tools tutorials for Indian developers and students.

<div align="center">

[![Subscribe to TechGVS](https://img.shields.io/badge/YouTube-TechGVS-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@TechGVS07)
[![Follow on GitHub](https://img.shields.io/badge/GitHub-Follow-191919?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Sadhi-Team-16)

</div>

---

## 📄 License

- `deep-research.skill` — MIT License
- `deep-thinking.skill` — MIT License
- `humanizer.skill` — MIT License (see `humanizer/LICENSE`)

---

<div align="center">

Made with ❤️ by **TechGVS** · For Indian developers, students, and AI enthusiasts

*Star ⭐ this repo if it helped you!*

</div>
