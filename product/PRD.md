Accountability Journal — Product Requirements Document
GitHub: accountability-journal
Version: 2.0
Date: March 30, 2026

---

## 1. Problem Statement

I have a hard time building habits and sticking to my goals. The first version of this app tried to help with that by asking me to reflect on why I missed a habit — which was useful, but I realized it wasn't enough. Reflection without direction kept me looking backward without giving me anything to actually do differently.
Then I heard someone say: depression is often caused by the gap between who you want to be and who you are now. And the only way to close that gap is with action.
That changed how I thought about the whole thing. I didn't want an app that just asked me to explain myself. I wanted a system where I could put in my goals of who I want to be, check in with what I actually did today, and then see those two things side by side — so the gap is right in front of me. And then be prompted to write an action plan: one concrete thing I'll do next time to get closer to who I want to become.
So I rebuilt the journaling process to facilitate exactly that.

---

2. Solution Statement
Accountability Journal is a combined identity tracker, daily check-in tool, and action planner. Users define identity goals — statements about who they want to become — and each day they log what they actually did. The app places both side by side so the gap is visible, then prompts the user to write a specific action plan for next time.
A visual scrapbook layer (photos, stickers, calendar view) adds a personal and creative dimension, turning the app into a meaningful record of growth over time — not just a productivity tool.

---

3. Core Philosophy
The entire journaling flow is built on one principle:

"The gap between who you want to be and who you are is closed only through action."

This replaces the original reflection-only model with a three-part cycle:

Identity — Who do I want to be?
Reality — Who was I today?
Action — What will I do next time to close the gap?

---

4. Target User

- An individual focused on personal growth and identity-based habit formation
- Someone who wants accountability grounded in who they are becoming, not just what they are doing
- Me

---

5. The New Journaling Flow
Step 1 — Identity Goals (set once, updated anytime)
The user defines who they want to be using identity statements. These are not to-do items or habits — they are descriptions of the person they are working toward becoming.
Examples:

I am someone who moves their body every day.
I am a disciplined and consistent reader.
I am someone who shows up calm and present for the people I love.

Step 2 — Daily Check-In (done each day)
For each identity goal, the user writes a brief note on what they actually did (or did not do) that day. This is freeform and honest — not a checkbox.

Step 3 — The Mirror (automatic)
The app places the identity goal and the daily check-in side by side. The user sees the gap between who they said they want to be and who they were today. No judgment is added by the app — the visibility itself is the mechanism.

Step 4 — Action Plan (prompted after The Mirror)
The user is prompted to write a specific, concrete action plan for next time. The prompt reads:

"What is one specific thing you will do next time to get closer to who you want to be?"

This replaces the original reflection prompt entirely. The emphasis shifts from analyzing the past to planning forward action.

---

6. MVP Features
#Feature1Identity goal creation, editing, deletion2Daily check-in — freeform log per identity goal3The Mirror — side-by-side view of identity vs. actual4Action plan prompt and capture5Photo upload6Weekly summary report7Monthly summary report

---

7. Full Feature List — Version 2
#FeaturePriority1Identity goal creation, editing, deletionMust Have2Daily check-in (freeform log per identity goal)Must Have3The Mirror — side-by-side identity vs. actual viewMust Have4Action plan prompt and freeform captureMust Have5Weekly summary reportMust Have6Monthly summary reportMust Have7Photo upload with single decorative border styleNice to Have8Single-day habit override (skip without penalty)Should Have9Streak counter per identity goalShould Have10Identity goal categories / tagsShould Have11Dark / light mode toggleNice to Have

---

8. Future Updates (V3+)

Deletion reflection — "Why are you letting go of this version of yourself?" before an identity goal is deleted
Identity graveyard — a dedicated view of deleted goals and their farewell reflections
Supabase cloud sync (migrate from local storage)
Multiple border styles for photo stamps
More stickers for journal / calendar entries
Push / local notifications for check-in reminders
Shareable summary card (image export for social)

---

10. Design Requirements

All UI designed in Figma before implementation
Desktop-first layout, responsive down to mobile
Aesthetic: cute minimal with vintage touches
Design system: color palette, typography, spacing scale, component library
One photo border style (reference TBD — user to provide)
The Mirror is a core UI component — must be visually clear and distinct
Action plan prompt always reads: "What is one specific thing you will do next time to get closer to who you want to be?"

---

11. Screen Map
App
├── Dashboard (Today)
│     ├── Identity goal checklist
│     ├── Daily check-in (freeform per goal)
│     ├── The Mirror (identity vs. actual, side by side)
│     ├── Action plan prompt + input
│     ├── Mood rating
│     └── Photo upload + border stamp
├── Identity Goals Manager
│     ├── Add / Edit / Delete identity goal
│     └── Single-day override
├── Journal View
│     └── Browse past days — photos, check-ins, The Mirror, action plans
├── Reports
│     ├── Weekly summary
│     └── Monthly summary
└── Settings
      └── Theme toggle (dark / light)
  ---

12. Changelog
Version 2.0 — March 30, 2026

Replaced reflection prompt with identity-based journaling flow
Added identity goals as the primary organizing concept (replacing habit tracking)
Introduced The Mirror — the side-by-side view of identity vs. actual
Replaced missed-habit reflection with action plan prompt
Updated screen map to reflect new Dashboard structure
Updated all feature tables to reflect v2 flow
Philosophical grounding added to Section 3 (Core Philosophy)

Version 1.0 — March 20, 2026
Initial release. Habit-based tracking with missed-habit reflection prompts.
