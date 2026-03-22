# SyncShift
### AI-powered shift scheduling built for college campuses. Right person, right shift, right now.

> 🏆 Built at **TruHacks 2026** — Truman State University Hackathon · Business Pitch Category  
> 👥 Team: **Dung (Tony) Le & Zachary Wellen**

---

![SyncShift](syncshift_infographic_final26.pdf)

## Inspiration

As an international student and campus worker at Truman State University, I'm legally capped at 20 hours of work per week. Every semester my schedule changes — new classes, exams, club commitments — and when emergencies happen, calling out means my manager is stuck scrambling for coverage through group chats.

We looked at every scheduling tool on the market and found the same problem: they're all built for managers, not employees. Nobody had built something that actually understood a student worker's life. That gap was our inspiration.

---

## What It Does

SyncShift is an AI-powered scheduling platform built for both managers and student employees.

- **Employees** input their classes, clubs, and commitments ranked by priority, creating a live availability profile
- **Managers** assemble schedules and get a real-time dashboard showing genuine availability at a glance
- **When a shift opens up**, SyncShift's AI algorithm instantly scans every eligible employee's real-time availability — accounting for class schedules, ranked priorities, and remaining work hours — and notifies the best match first
- If the first person declines, the next best candidate is notified automatically — just like Uber matching riders to drivers
- **F-1 international students** are protected automatically with built-in 20-hour weekly cap enforcement

No phone calls. No group chats. No coverage gaps.

---

## How We Built It

SyncShift is designed around two core components:

### 1. Dual-Sided Scheduling Interface
- **Employee side** — workers input and rank all commitments (classes, clubs, jobs), creating a dynamic availability profile
- **Manager side** — real-time dashboard showing genuine employee availability, not just empty time slots

### 2. AI Matching Algorithm
Inspired by Uber's dispatch system, the algorithm:
1. Detects a cancelled or open shift
2. Scans every eligible employee's real-time availability
3. Ranks candidates by availability score, remaining work hours, and priority conflicts
4. Notifies the best match first — they can accept or pass
5. If declined, automatically moves to the next best candidate

### 3. Campus System Integration
Designed to integrate with existing campus infrastructure:
- HR and payroll systems
- Class registration databases
- Housing and residential life platforms

---

## Challenges We Ran Into

- **Algorithm complexity** — student schedules are never the same week to week. Availability isn't just about being free at a given time; it requires accounting for ranked priorities, weekly hour caps, and last-minute changes simultaneously
- **Dual-market positioning** — convincing both managers and employees that a dual-sided platform adds value required careful thinking about UX and pitch framing
- **Scope** — designing a full business model, polished pitch, and infographic as a two-person team within a single hackathon weekend

---

## Accomplishments That We're Proud Of

- Designed a scheduling solution that genuinely centers the **employee** — something the entire scheduling software industry has overlooked
- Communicated a complex AI algorithm simply and effectively through the Uber analogy
- Built out a full business model — university licensing, SaaS subscriptions, and system integrations — in a single weekend
- Created a polished pitch infographic and presentation as a two-person team

---

## What We Learned

- The best product ideas often come from **personal pain points** — the frustration of navigating a 20-hour work cap with an inflexible scheduling system was the clearest signal we needed
- **Simplicity in communication** is just as important as sophistication in engineering — "AI-powered matching" means nothing to a tired manager at 6 AM, but "just like Uber, it finds the right person automatically" clicks instantly
- Framing a technical solution in **human terms** is a skill as valuable as building the solution itself

---

## What's Next for SyncShift

- **MVP development** — build a working prototype and pilot with campus employers at Truman State University
- **University expansion** — scale to other universities across the country through campus-wide licensing
- **Deeper integrations** — connect with existing campus HR, class registration, and payroll systems
- **Beyond campus** — expand to any employer relying on part-time or hourly workers with complex availability (hospitals, hotels, retail chains)
- **Predictive scheduling** — AI that anticipates coverage needs *before* a cancellation even happens

---

## Target Market

| Segment | Description |
|---|---|
| F-1 International Students | Legally capped at 20 hrs/week, complex and shifting schedules |
| Campus Employment Offices | Dining, facilities, libraries, administrative roles |
| Residence Hall Staff | RAs and desk workers requiring 24/7 coverage |
| Faculty & TAs | Office hours, lab sessions, grader coordination |
| Facilities & Custodial | Mixed full-time and part-time crews with strict coverage needs |

---

## Competitive Landscape

| Platform | Shift Swap | Employee-First | Student UX |
|---|---|---|---|
| When I Work | ✓ | ✗ | ✗ |
| Deputy | ✓ | ✗ | ✗ |
| Homebase | ✗ | ✗ | ✗ |
| Shiftboard | ✗ | ✗ | ✗ |
| **SyncShift** | ✓ | ✓ | ✓ |

---

## Business Model

| Revenue Stream | Description |
|---|---|
| 🏫 University License | Campus-wide deal covering all departments — dining, housing, academics |
| 📦 SaaS Subscription | Per-seat monthly plans for individual departments or smaller campuses |
| 🔗 System Integration | API integrations with HR, payroll, and class registration systems |
| 📈 Scale Beyond Campus | Expansion to hospitals, hotels, retail, and other hourly-worker employers |

---

## Built With

- AI matching algorithm (Uber-inspired dispatch model)
- Dual-sided scheduling interface
- Campus system integration layer (HR, payroll, class registration)

---

## Team

| Name | Role |
|---|---|
| Dung N. | Co-Founder — Ideation, Business Model, Pitch |
| Zach M. | Co-Founder — Ideation, Business Model, Pitch |

---

## License

This project was created for educational and hackathon purposes at TruHacks 2026.  
© 2026 SyncShift. All rights reserved.
