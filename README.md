# Felix — Your AI Fitness Coach That Actually Remembers You

Every fitness app tracks reps. Felix tracks **you** — your injuries, your schedule, your hatred of burpees, that left shoulder that acts up on overhead press day. He builds programs that get smarter every session because he never forgets.

## The Problem

You open ChatGPT and ask for a workout plan. It gives you a generic 3-day split. Next week, you ask again — it has no idea you exist. You re-explain your bad knee, your home gym setup, your goal of running a 5K while building muscle. Every. Single. Time.

**Felix fixes this.**

## What Felix Does

🏋️ **Personalized Programming** — Workouts built around your goals, equipment, schedule, and limitations — not cookie-cutter templates

📊 **Progress Tracking** — PRs, measurements, adherence patterns. Felix notices when your squat is stalling and adjusts before you get frustrated

🦵 **Injury-Aware Coaching** — Bad knee? Shoulder impingement? Felix remembers and programs around it. Always.

🍎 **Nutrition Guidance** — Practical advice aligned with your training goals. No rigid meal plans unless you want them.

🔄 **Adaptive Programs** — What worked last month might not work now. Felix adjusts based on your actual progress, not theoretical periodization

💪 **Motivation That Knows You** — Felix learns whether you respond to tough love or gentle encouragement. He recognizes when you're burning out vs. sandbagging.

## How It Works

Felix is an **AI Specialist** built on [Magic Context](https://magiccontext.ai). Instead of starting every AI conversation from scratch, Felix maintains a persistent workspace — your fitness profile, training history, preferences, and progress — that carries across every session.

```
┌──────────────────────────────────────────┐
│          Felix's Workspace               │
├──────────────────────────────────────────┤
│                                          │
│  📋 AI Instructions                      │
│  ├── Coaching personality & style        │
│  ├── Programming principles              │
│  └── Memory protocols                    │
│                                          │
│  🧠 Memory                               │
│  ├── Your profile (stats, goals, limits) │
│  ├── Preferences (exercises, schedule)   │
│  └── Progress history                    │
│                                          │
│  📚 Knowledge Base                       │
│  ├── Exercise library                    │
│  ├── Training principles                 │
│  ├── Nutrition fundamentals              │
│  └── Recovery protocols                  │
│                                          │
│  🎯 Active Projects                      │
│  ├── Current program                     │
│  └── Goal tracking                       │
│                                          │
│  📝 Templates                            │
│  ├── Workout plans                       │
│  ├── Exercise logs                       │
│  └── Progress check-ins                  │
│                                          │
└──────────────────────────────────────────┘
```

### The Magic Context Difference

Traditional AI is **stateless** — it forgets everything between conversations. Magic Context gives AI specialists **persistent memory** through structured workspaces. This means:

- **Session 1:** Felix learns about you — goals, injuries, schedule, equipment
- **Session 5:** Felix adjusts your program because your squat is progressing faster than your bench
- **Session 20:** Felix knows your patterns — you're stronger in the evening, you skip Friday sessions, you respond well to volume increases
- **Session 50+:** Felix is a coach who knows you better than most human trainers

**Your context is yours.** It's stored as plain markdown files you can read, edit, or export anytime. No black box. No vendor lock-in.

## Quick Start

### Import to AI Specialists Hub

```bash
# Via the Magic Context import feature
import_specialist github.com/magic-context/felix-fitness-coach
```

Or use the import tool in [AI Specialists Hub](https://aispecialistshub.com) with:
```
https://github.com/magic-context/felix-fitness-coach
```

### First Session

Felix will guide you through an intake assessment:
1. Your fitness goals
2. Training history and current level
3. Available equipment and schedule
4. Injuries and limitations
5. Exercise preferences

Then he'll build your first personalized program.

### Ongoing Use

- **Before workouts:** Ask Felix what's on the schedule
- **After workouts:** Log your session (weights, reps, how it felt)
- **Weekly:** Check in for progress review and program adjustments
- **Anytime:** Ask questions about form, nutrition, recovery

## Repository Structure

```
felix-fitness-coach/
├── configuration/
│   └── module.json              # Specialist metadata
├── content/
│   ├── README.md               # Workspace guide
│   ├── ai-instructions/        # Felix's coaching brain
│   │   ├── core-instructions.md
│   │   ├── getting_started.md
│   │   └── memory-protocols.md
│   ├── memory/                 # Your persistent profile
│   │   ├── user-profile.md
│   │   └── preferences.md
│   ├── knowledge/              # Fitness expertise
│   │   ├── exercise-library.md
│   │   ├── training-principles.md
│   │   ├── nutrition-basics.md
│   │   ├── body-composition.md
│   │   └── templates/
│   │       ├── workout-plan.md
│   │       ├── exercise-log.md
│   │       └── progress-check-in.md
│   ├── active-projects/        # Current training plan
│   │   └── current-goals.md
│   ├── historical/             # Past programs
│   └── feedback/               # Improvement notes
└── README.md
```

## Who This Is For

- **Busy professionals** who want structured, personalized fitness without a human trainer
- **Intermediate lifters** who've outgrown generic programs and need adaptive coaching
- **People with injuries or limitations** who need a coach that always remembers their constraints
- **Anyone tired of re-explaining their fitness situation** to AI every single time

## Suggested MCP Skill Pairings

Felix works with any MCP-compatible AI agent (Claude, GPT, Gemini, etc.). These integrations enhance the coaching experience:

- **Weather Service** — Suggests indoor vs outdoor workouts based on conditions
- **Task & Reminder Integration** — Workout reminders and recovery day alerts
- **Visual Display** — Display workout plans and progress charts
- **Text-to-Speech** — Voice-guided workouts for hands-free training
- **Content Summarization** — Extract training insights from fitness content

## Requirements

- [AI Specialists Hub](https://aispecialistshub.com) account (or any Magic Context-compatible platform)
- ChatGPT Plus/Pro/Team/Enterprise OR Claude with MCP support

## Contributing

Feedback and improvements welcome via issues. This is a showcase specialist for Magic Context — if Felix coaches you well, imagine what a persistent AI specialist could do for *your* domain.

## License

MIT

---

Built with [Magic Context](https://magiccontext.ai) — Context as a Service for AI
