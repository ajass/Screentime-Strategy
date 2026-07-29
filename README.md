# Screentime Strategy

Resources for teaching 11-year-old kids about screen time, dopamine, and self-regulation. Designed for twin boys who are obsessed with their tablets. The goal is not to ban screens — it is to teach them WHY excessive screen time is harmful so they develop self-regulation skills.

---

## Parent Workflow Diagram

```
┌─────────────────────────────────────────────────────────
│  PHASE 1: PREPARATION (parents only, before kids know)
│
│  Read parent-guides/01-screen-time-research.md
│  └─ Learn the science: dopamine, displacement, health effects
│
│  Read parent-guides/02-video-discussion-guide.md
│  └─ Learn the twin approach + when to hand out each worksheet
│
│  Read parent-guides/03-video-comprehension-quiz.md
│  └─ Learn how to administer the quiz separately
│
│  Read parent-guides/04-family-plan-guide.md
│  └─ Learn how to negotiate the agreement without overriding agency
│
│  Read parent-guides/05-time-management-guide.md
│  └─ Set up tablet controls (iPad/Android/Fire) BEFORE the session
│
│  Read parent-guides/06-breaking-the-agreement.md
│  └─ Know the consequence ladder before you need it
│
│  Print 2 copies of each kid worksheet:
│  └─ kid-worksheets/worksheet-1-self-quiz.txt
│  └─ kid-worksheets/worksheet-2-video-notes.txt
│  └─ kid-worksheets/worksheet-3-levelups-bigquestion.txt
│  └─ kid-worksheets/family-plan-agreement.txt
│  └─ quiz questions only from 03-video-comprehension-quiz.md
│
└─────────────────────────────────────────────────────────
                          │
                          ▼
┌─────────────────────────────────────────────────────────
│  PHASE 2: VIDEO SESSION (with kids, ~60-75 min)
│
│  BEFORE pressing play:
│  └─ Hand each kid worksheet-1 (self-quiz) ONLY
│  └─ Say: "Answers are private, no looking at brother's paper"
│
│  Press play: https://youtu.be/6iJdRoeYay0
│
│  At 0:41 — pause, kids fill out worksheet-1 (self-quiz)
│  At 2:26 — pause, hand out worksheet-2 (notes)
│  At 4:56 — pause, discuss chapter questions together
│  At 7:48 — pause, discuss chapter questions together
│  At 9:15 — pause, discuss chapter questions together
│  Video ends — collect worksheets, do NOT review yet
│
└─────────────────────────────────────────────────────────
                          │
                          ▼
┌─────────────────────────────────────────────────────────
│  PHASE 3: QUIZ (separate rooms, ~15 min)
│
│  Boy 1 in room A with quiz on paper (no screens)
│  Boy 2 in room B with quiz on paper (no screens)
│  Swap when first is done
│  └─ Do NOT review answers immediately
│
└─────────────────────────────────────────────────────────
                          │
                          ▼
┌─────────────────────────────────────────────────────────
│  PHASE 4: REFLECTION (one-on-one, ~10 min each)
│
│  Hand out worksheet-3 (level ups + big question)
│  Each kid fills it out privately
│
│  Then take each boy aside individually:
│  └─ Ask: "Are you the boss of your tablet or is it the boss of you?"
│  └─ Write down what each says
│  └─ Do NOT do this together — twins will mirror each other
│
└─────────────────────────────────────────────────────────
                          │
                          ▼
┌─────────────────────────────────────────────────────────
│  PHASE 5: FAMILY PLAN (separate session, ~30-45 min)
│
│  Bring both kids together
│  └─ "You each came up with your own number. Let's build a plan."
│
│  Fill out family-plan-agreement.txt together:
│  └─ Part A: Their screen time number (summer + school days)
│  └─ Part B: What counts as screen time (consumption vs creation)
│  └─ Part C: Screen-free zones and times (non-negotiable)
│  └─ Part D: Their two level ups
│  └─ Part E: Review schedule (weekly check-in, two-week review)
│  └─ Part F: Everyone signs — kid, mom, dad
│
│  Set up tablet controls WITH them (not secretly)
│  └─ Enter their number into Screen Time / Family Link / Kids
│  └─ Configure staged warnings (15 min, 5 min, 1 min)
│  └─ Exclude school, creative, and messaging apps
│  └─ Tablets charge in kitchen overnight
│
└─────────────────────────────────────────────────────────
                          │
                          ▼
┌─────────────────────────────────────────────────────────
│  PHASE 6: ONGOING (weeks to months)
│
│  Week 1:      Daily life with the timer. Expect pushback.
│  Week 2:      First check-in (one-on-one, 5 min each)
│  Week 2:      Two-week review — adjust the number if needed
│  Weeks 3-4:   Pushback decreases. Monitor for violations.
│  Week 4:      Second review. Is the number working?
│  Weeks 5-8:   Stabilize. Watch for self-regulation emerging.
│  Week 8:      Monthly review. Can they try self-managing?
│
│  If they break the agreement:
│  └─ Level 1 (grumpy at timer): no consequence, dopamine talking
│  └─ Level 2 (testing edges): conversation, hold the line
│  └─ Level 3 (sneaking/lying): 24hr reduced autonomy, earn back in 3 days
│  └─ Level 4 (repeated): renegotiate number downward
│  └─ See parent-guides/06-breaking-the-agreement.md for full details
│
│  The long game:
│  Months 1-2:  Timer runs the show, they fight it
│  Months 3-4:  They start anticipating the timer
│  Months 5-6:  They check the time themselves
│  Months 7+:   They may set their own alarms. Let them try.
│
└─────────────────────────────────────────────────────────
```

---

## Repository Structure

```
Screentime-Strategy/
├── README.md                              ← You are here
│
├── parent-guides/
│   ├── 01-screen-time-research.md          Research, dopamine science, how to explain to kids
│   ├── 02-video-discussion-guide.md        Chapter-by-chapter discussion questions + twin approach
│   ├── 03-video-comprehension-quiz.md      13-question quiz + parent administration instructions
│   ├── 04-family-plan-guide.md             How to negotiate the agreement, handle high proposals
│   ├── 05-time-management-guide.md         Tablet setup, visual timers, escalation ladder
│   └── 06-breaking-the-agreement.md        Violation levels, consequences, reset conversation
│
└── kid-worksheets/
    ├── worksheet-1-self-quiz.txt           Hand out BEFORE video (self-quiz only)
    ├── worksheet-2-video-notes.txt          Hand out at 2:26 (note space per chapter)
    ├── worksheet-3-levelups-bigquestion.txt Hand out AFTER video (level ups + big question)
    └── family-plan-agreement.txt            Fill out together in Phase 5 (sign and date)
```

---

## Quick Reference

| What | File | When |
|------|------|------|
| The science behind the approach | parent-guides/01-screen-time-research.md | Read first |
| How to run the video session | parent-guides/02-video-discussion-guide.md | Read before session |
| The quiz + how to give it | parent-guides/03-video-comprehension-quiz.md | Read before session |
| How to negotiate the plan | parent-guides/04-family-plan-guide.md | Read before Phase 5 |
| How to enforce time limits | parent-guides/05-time-management-guide.md | Read before Phase 5 |
| What to do when they break it | parent-guides/06-breaking-the-agreement.md | Read before you need it |
| Kid self-quiz (printable) | kid-worksheets/worksheet-1-self-quiz.txt | Hand out before video |
| Kid notes (printable) | kid-worksheets/worksheet-2-video-notes.txt | Hand out at 2:26 |
| Kid level ups + big question (printable) | kid-worksheets/worksheet-3-levelups-bigquestion.txt | Hand out after video |
| Family plan agreement (printable) | kid-worksheets/family-plan-agreement.txt | Fill out in Phase 5 |

---

## Video

["Solving Screen Addiction for Kids & Teens — Media Stamped #1"](https://youtu.be/6iJdRoeYay0) by Nicole Stamp (Global Citizen, 13:21)

## Sources

- CDC (2025): Associations Between Screen Time Use and Health Outcomes Among US Teenagers
- Nature Human Behaviour (2024): Weighing the risks and benefits of screen time for children
- NPR (2023): Anti-dopamine parenting — interviews with Dr. Anna Lembke (Stanford), Dr. Kent Berridge (Univ. of Michigan)
- NewYork-Presbyterian (2025): Screen Addiction — Dr. Andrea Temkin-Yu (Weill Cornell)
- JAMA (2025): Addictive screen use patterns and mental health outcomes