# StudyOS SaaS Upgrade Plan

## Phase 1 (Immediate)
- Convert single HTML file into React + Vite app
- Create reusable components:
  - Dashboard
  - Timetable
  - Courses
  - Calendar
  - Modals

## Phase 2
- Add Supabase
- Authentication (Email/Password)
- Cloud sync

## Phase 3
- Database tables:
  - users
  - courses
  - topics
  - events
  - timetable_slots

## Phase 4
- Mobile responsiveness
- PWA support
- Notifications

## Phase 5
- Production deployment
  - Vercel
  - Supabase

## First code refactors needed from uploaded file
1. Remove localStorage-only architecture.
2. Replace inline onclick handlers with component events.
3. Split CSS into modules.
4. Sanitize all rendered content.
5. Add routing.
