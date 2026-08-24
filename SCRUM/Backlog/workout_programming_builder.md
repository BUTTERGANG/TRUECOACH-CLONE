---
status: backlog
priority: P2
agent_claimed: null
claimed_at: null
updated: 2026-08-20
---

# Workout Programming Builder

> **Repo:** TRUECOACH-CLONE
> **Description:** Drag-and-drop workout builder with exercise library and template system

---

## Context

Coaches need to build programs -- drag exercises from library, set sets/reps/RPE, arrange into weeks.

---

## Acceptance Criteria

- [ ] Exercise library with search and filter by muscle group/equipment
- [ ] Drag-and-drop program calendar (week/day view)
- [ ] Set configuration: reps, weight, RPE, rest, notes per exercise
- [ ] Template save/load system for reusable programming blocks

---

## Technical Notes

- dnd-kit for drag-and-drop; Drizzle schema for program structure; exercise library as seed data
