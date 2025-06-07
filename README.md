# CSSPS-Plus


A robust, fair, and transparent school placement engine for Ghanaian JHS students after the Basic Education Certificate Examination (BECE). This system helps assign students into senior high schools based on merit, choice preference, school eligibility, gender, special needs, and capacity constraints.

## Why This Project?

The current computerized school selection system (CSSPS) in Ghana faces a lack of transparency in cutoff scores and placement decisions

This system solves those with:
- A rule-based, merit-prioritized placement engine
- Consideration of gender, disability, and program availability
- A Phase 2 fallback algorithm for unplaced students
- Transparent reporting per student

---

## Tech Stack

| Layer       | Tech                             |
|------------|----------------------------------|
| Frontend   | React (or Next.js), TypeScript   |
| Backend    | Python (FastAPI or Django REST)  |
| Database   | PostgreSQL + Redis (for caching) |
| Deployment | Docker + Hostinger VPS or cloud  |
| Auth       | JWT / OAuth2                     |

---

## Placement Algorithm Highlights

- Sorted by raw score
- Applies school gender restrictions
- Honors program-specific cutoff scores
- Respects disability access compatibility
- Limits to program/school capacities
- Provides full placement reports for transparency
- Phase 2 fallback system for unplaced candidates

---

