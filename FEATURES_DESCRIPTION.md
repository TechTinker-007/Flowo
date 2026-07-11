<div align="center">

# ⚡ Flowo

**A fast, collaborative task and project management app** — built for individuals and small teams who want clarity without clutter.

[![Live App](https://img.shields.io/badge/🔗_Live_App-Visit_Flowo-DB4035?style=for-the-badge)](https://troubler-s-fix.vercel.app/login)

</div>

> 🔒 **This repository is private.** This document exists to give visitors context on the project via the live link above.

---

## 🧭 What Flowo Is

Flowo helps you organize tasks and projects with the simplicity of **Todoist** and the visual precision of **Linear.app**. It's built on a modern, lightweight stack (React + Vite + Supabase) and is designed to stay fast and dependable as it grows — every feature is added deliberately, with existing functionality protected against regressions.

---

## 🚀 Core Features

### 📋 Task & Project Management
Create, organize, and track tasks within projects. Tasks support the everyday essentials — due dates, priorities, status, and grouping — so you can move from "idea" to "organized plan" in seconds. Projects act as containers that keep related work together and easy to scan.

### 👥 Collaboration
Flowo is built to be used with others, not just solo. Team members can be added to shared projects, assigned tasks, and kept in the loop as work moves forward — making it usable for small teams as easily as for individual productivity.

### ⚡ Real-Time Sync
Powered by Supabase Realtime, changes made by one person — a new task, an updated status, a comment — appear for everyone else instantly, with no manual refresh. This keeps a shared board trustworthy: what you see is always the current state, not a stale snapshot.

### 🤖 AI Assist
An AI layer (running on Groq's free-tier inference) helps reduce the friction of turning rough thoughts into structured tasks — offering suggestions and quick breakdowns without adding ongoing API costs to the product.

### 🔔 Notifications
Keeps users informed of relevant activity — task assignments, updates, and changes on projects they're part of — so nothing important gets missed silently.

### 🔌 Integrations
Designed with room to connect to other tools you already use, extending Flowo beyond a standalone task list into part of a broader workflow.

### 📱 Mobile-Responsive Design
The full interface adapts cleanly to smaller screens, so managing tasks doesn't require sitting at a desk. Layouts, navigation, and interactions have been specifically tuned for mobile use, not just scaled down from desktop.

### 🎨 Visual Design
Flowo uses a distinct visual identity rather than default styling:

- 🔴 **Accent color:** Signal red `#DB4035`
- 🔤 **Typography:** Inter
- 🎬 **Motion:** Subtle shadows and fast 150ms transitions for a responsive, tactile feel
- 💡 **Inspiration:** Todoist's clarity + Linear.app's structural precision

---

## 🗺 What Flowo Intentionally Doesn't Do (Yet)

To keep the app fast and focused, some features are deliberately out of scope for the current stage of the product:

- 💳 Billing / payments
- 👀 Live cursors or multiplayer presence indicators
- 📊 Table or Gantt chart views
- 🗂 Project templates
- 🔐 Single sign-on (SSO)
- 📴 Offline mode / PWA support

These aren't oversights — they're scoping decisions to keep the product lean while the core experience is refined. Some may be revisited in future phases.

---

## 🛠 Tech Stack

| | Layer | Technology |
|---|---|---|
| ⚛️ | Frontend | React + Vite + TypeScript |
| 💨 | Styling | Tailwind CSS |
| 🗄️ | Backend / Database | Supabase (Postgres + Realtime + Auth) |
| 🧠 | AI | Groq (free-tier inference) |
| ▲ | Hosting | Vercel |

---

## 📈 Status

Flowo is actively developed in scoped, additive batches — new features ship without breaking what already works. The project is private during this build phase; the live deployment link above always reflects the current version. See [`CHANGELOG.md`](./CHANGELOG.md) for a running history of releases.

## 📄 License

All Rights Reserved. See [`LICENSE.md`](./LICENSE.md) for details. The live application may be viewed and used via the deployed link; the source code is not licensed for reuse or redistribution.
