# Flowo — Project Description

## Short About Blurb (for GitHub's "About" field)
Flowo is a fast, collaborative task management app built with React, Vite, and Supabase — inspired by the clarity of Todoist and the polish of Linear. Live demo linked below.

---

## Full Description (350 words)

Flowo is a modern task and project management application designed for individuals and small teams who want the speed of a lightweight tool without sacrificing the structure of a full project management suite. Built on a React + Vite frontend with a Supabase backend, Flowo focuses on doing the essentials — tasks, projects, and collaboration — exceptionally well, rather than trying to be everything at once.

The design language draws inspiration from Todoist's approachability and Linear.app's precision: a warm signal red (#DB4035) accent color, Inter typography, subtle shadows, and fast 150ms transitions that make every interaction feel immediate. The interface is fully mobile-responsive, so task management doesn't stop at the desktop.

Under the hood, Flowo uses Supabase Realtime to keep task boards, comments, and project updates in sync across every connected device instantly — no refresh required. For teams, this means everyone is always looking at the current state of the board, whether they're updating a task from a laptop or checking progress from a phone.

Flowo also includes an AI assist layer (powered by Groq's free-tier inference) that helps with quick task breakdowns, smart suggestions, and reducing the friction of getting a rough idea into a structured task — without adding paid API costs to the stack.

The product is being built iteratively and transparently: every feature ships as a scoped, regression-safe addition, with deliberate boundaries around what's *in* (core task/project management, collaboration, realtime sync, notifications, AI assist, integrations) and what's intentionally *out* for now (billing, live cursors/presence, Gantt/table views, templates, SSO, offline/PWA support). This keeps the app lean, dependable, and easy to reason about as it grows.

Flowo is deployed on Vercel and actively maintained. The codebase is private, but the live product is available to explore at the link below — feedback and feature ideas are always welcome.

**Live demo:** [(https://troubler-s-fix.vercel.app/login)]
