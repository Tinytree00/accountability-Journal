# Accountability Journal 

## Live Demo
https://accountability-journal-rho.vercel.app/

## Problem
Building habits is hard — but the real issue is never knowing *why* they don't stick. Most habit trackers just mark a red X and move on. There's no space to reflect, no record of what actually got in the way, and nothing to look back on over time.

## Solution
I thought it would be really neat to have a journal, habit tracker, and scrapbook all in one place. the journaling and habit goes hand in hand to really reflect on why i'm not following thru with certain habits I want to build and provide both a visual and descriptive representation of that. while the scrapbooking part would just be a cute addition to include with the process. adding pictures and stickers to the journal and or calendar to have a nice overall visual view of how time has passed

## Tech Stack
 Frontend
  - React 18
  - Vite 5
  - Pure JSX with inline styles (no CSS framework)

  Storage
  - localStorage (client-side persistence, no backend)

  Assets
  - Custom SVG assets designed in Figma and Canva

Storage:
- AsyncStorage (v1 — local)
- Supabase v2 (v2 — cloud sync, planned)

Deployment:
Run Locally
  git clone https://github.com/deana-tham/accountability-Journal.git
  cd accountability-Journal
  npm install
  npm run dev
  Then open http://localhost:5173 in your browser.

  Built With
  - https://react.dev/
  - https://vitejs.dev/
  - Deployed on https://vercel.com/

## MVP
The minimum version of the app will allow users to:
- Add, edit, and delete habits
- Complete a daily check-in — mark each habit done or not done
- Trigger a reflection prompt when a habit is missed: *"What stopped you from doing [habit] today?"*
- Upload a photos onto calendar
- View a weekly summary report
- View a monthly summary report

## Product Delvelopment 
Have a lookie at my Product file for more details
