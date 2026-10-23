Technical Inspection Tracker


Problem

Inspection status is passed around by phone and paper, so results get lost, checks are repeated, and teams get conflicting instructions.

Solution

One shared checklist per team. Each line carries its rule reference (IN and T sections), a Pass / Fail / N/A result, the inspector's name and the time. A Fail requires a written reason, so the team knows exactly what to fix.

Features
Team registry: car number, name, college, type (CV, EV, DC-CV, DC-EV), inspection responsible person, tallest driver
Stages: pre-inspection, mechanical, tilt, weighing, noise (CV), brake, EV and DC sign-offs, post-event
Measured values (ground clearance, wheelbase, egress time, weight, noise level)
Open-failures board and re-inspection history
CSV export of all results
Works on a phone at the inspection bay
Tech

Plain HTML, CSS and JavaScript in one file, no build step. Built with Claude from the official rule book.

Run it

Open index.html in a browser. In this standalone version data is saved in the browser only (use "Load demo data" to try it). The shared multi-inspector version used a hosted database and is not part of this repo.

Roadmap
Shared backend (Firebase or Supabase) so all inspectors see live updates
Full EV and DC checklists
Read-only status view for teams 
