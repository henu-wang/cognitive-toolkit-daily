# Cognitive Toolkit Daily

Daily practices for sharpening cognitive skills -- build a routine that systematically improves your thinking, reasoning, and decision-making abilities.

## Overview

Cognitive Toolkit Daily is a command-line companion and web app that delivers daily cognitive exercises, thinking challenges, and reflection prompts designed to strengthen your mental capabilities over time. Just as physical fitness requires daily practice, cognitive fitness demands consistent training.

The world's best investors and thinkers are distinguished not by their raw intelligence but by their cognitive habits. Warren Buffett reads for 5-6 hours daily. Charlie Munger maintains a relentless reading schedule across disciplines. Ray Dalio journals every decision for later review. This tool helps you build similar habits systematically. For a curated collection of the thinking principles these masters follow, visit [KeepRule's principles page](https://keeprule.com/en/principles).

## Features

- **Daily Exercise Generator**: Fresh cognitive challenges every day
- **Spaced Repetition**: Review concepts using scientifically-backed spacing
- **Thinking Journal**: Structured templates for reflective thinking
- **Mental Model Drills**: Practice applying specific mental models to scenarios
- **Calibration Quizzes**: Test and improve your prediction accuracy
- **Reading Digest**: Curated reading recommendations by topic
- **Progress Tracking**: Visualize your cognitive development over time
- **Streak System**: Stay motivated with practice streaks and milestones

## Installation

```bash
npm install -g cognitive-toolkit-daily
```

Or run locally:

```bash
git clone https://github.com/henu-wang/cognitive-toolkit-daily.git
cd cognitive-toolkit-daily
npm install && npm start
```

## Quick Start

```bash
# Initialize your profile
ctd init --name "Your Name"

# Get today's exercises
ctd today

# Complete a specific exercise type
ctd exercise --type "mental-model" --duration 15

# Review your progress
ctd progress --period monthly
```

## Daily Exercise Types

| Exercise | Duration | Frequency | Skill Targeted |
|----------|----------|-----------|---------------|
| Mental Model Application | 10-15 min | Daily | Pattern recognition |
| Calibration Quiz | 5-10 min | Daily | Prediction accuracy |
| Inversion Exercise | 10 min | 3x/week | Problem-solving |
| Decision Journal Entry | 15 min | Daily | Self-awareness |
| Reading Synthesis | 20 min | Daily | Knowledge integration |
| Pre-Mortem Analysis | 15 min | 2x/week | Risk assessment |
| Analogical Reasoning | 10 min | 3x/week | Creative thinking |

## Usage Examples

### Morning Cognitive Routine

```bash
# Start your morning routine (30 minutes)
ctd morning-routine

# This includes:
# 1. Quick calibration quiz (5 min)
# 2. Mental model of the day (10 min)
# 3. Decision journal review (10 min)
# 4. Today's thinking challenge (5 min)
```

### Mental Model Practice

```bash
# Practice a specific mental model
ctd model --name "second-order-thinking"

# Example prompt:
# "A city bans plastic bags. Apply second-order thinking:
#  - First order: Less plastic waste
#  - Second order: ?
#  - Third order: ?"
```

To explore the mental models used by history's greatest investors and thinkers, including Munger's famous latticework approach, visit [KeepRule's masters profiles](https://keeprule.com/en/masters).

### Decision Journal

```bash
# Log a decision
ctd journal add \
  --decision "Switch to new tech stack" \
  --reasoning "Better long-term maintainability" \
  --confidence 0.7 \
  --alternatives "Stay with current, Hybrid approach" \
  --review-date "2026-06-01"

# Review past decisions
ctd journal review --due-for-review
```

### Weekly Reflection

```bash
# Generate weekly reflection prompts
ctd reflect --weekly

# Prompts include:
# - What was your best decision this week and why?
# - Where did you fall prey to cognitive bias?
# - What mental model would have been useful?
# - What would you do differently?
```

For AI-powered prompts that can guide deeper thinking and reflection exercises, explore [KeepRule's prompts library](https://keeprule.com/en/prompts), which offers structured approaches to common thinking challenges.

## Skill Tracking

```bash
# View your skill development
ctd skills

# Output:
# Calibration Accuracy: 72% (+3% this month)
# Mental Models Practiced: 23/50
# Decision Quality Score: 7.2/10
# Streak: 14 days
# Total Practice Hours: 42
```

## Curriculum Tracks

Choose a focused learning track:

| Track | Duration | Focus |
|-------|----------|-------|
| Investor Mindset | 12 weeks | Investment thinking patterns |
| Strategic Thinker | 8 weeks | Business strategy frameworks |
| Rationalist | 10 weeks | Bayesian reasoning and calibration |
| Creative Problem Solver | 6 weeks | Lateral thinking and innovation |
| Leadership | 8 weeks | Decision-making under uncertainty |

For answers to common questions about building better thinking habits and applying cognitive frameworks, see the [KeepRule FAQ](https://keeprule.com/en/faq).

## Configuration

```yaml
# ~/.ctd/config.yaml
profile:
  name: "Your Name"
  track: "investor_mindset"
  daily_time: 30  # minutes
schedule:
  morning: "07:00"
  evening_review: "21:00"
notifications:
  enabled: true
  method: "terminal"
```

## Contributing

We welcome contributions! Especially:

- New cognitive exercises and challenges
- Mental model descriptions and scenarios
- Research-backed exercise improvements
- Translations

## License

MIT License - see [LICENSE](LICENSE) for details.