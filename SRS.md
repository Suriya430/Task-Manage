# Software Requirements Specification (MoSCoW Prioritization)

## Must Have (The Non-Negotiable Core)
*If removed, the app fails to solve the user's core problem of friction, schedule blindness, and task paralysis.*

1. **The "3-Second" Quick Dump:** Ultra-low friction task entry (name and deadline only) without mandatory categories. 
   * *Why: The persona abandons complex apps; requires immediate offloading to prevent mental tracking.*
2. **Unified School-Work Timeline:** A single visual feed that explicitly overlaps school deadlines with work shift hours. 
   * *Why: The core differentiator. Visually shatters the "I have time later" illusion by revealing true free time.*
3. **The "Mountain Crusher" (Basic Breakdown):** A prompt that breaks a large task into three tiny, 5-minute starting steps. 
   * *Why: Directly targets the user's "Freeze Response" and procrastination loop.*
4. **Shift-Aware Nudges:** Proactive notifications alerting the user of a study window *before* a work shift begins. 
   * *Why: Prevents the late-night "danger zone" panic after finishing a shift.*
5. **Offline Resilience:** Ability to log a quick task offline (e.g., in a school basement) that auto-syncs later. 
   * *Why: If the 3-second dump fails due to no signal, the user's trust in the app breaks.*

## Should Have (Important, but not vital for launch)
*App functions without these, but they significantly enhance the core value proposition.*

1. **Focus Mode:** A toggle that hides the full timeline and displays only the single most important task right now.
2. **Quick-Start Timer (10-min):** A built-in timer to encourage starting a broken-down task.
3. **"Snooze" to Next Free Block:** Automatically rescheduling a missed task to the next logical gap in the timeline.

## Could Have (Nice-to-Haves for future iterations)
*High effort or lower impact features that delight but aren't strictly necessary.*

1. **Photo Sync for Work Schedules (OCR):** Taking a photo of a paper schedule to automatically extract shift dates/times.
2. **"Vibe Check" Dashboard:** Color-coding the day based on the estimated mental energy/cortisol required.
3. **Stress-Free Points:** Gamification rewarding early task completion with timed, guilt-free social media scrolling.
4. **Customizable Minimalist Themes:** Aesthetic adjustments to make the UI feel personalized and soothing.

## Won't Have (Explicitly excluded for v1)
*Distractions that dilute the core mission or add immense technical complexity.*

1. **Social & Community "Study Squads":** Adds distraction and infrastructure bloat.
2. **AI Academic Coaching:** The app is a logistics tool, not a subject-matter tutor.
3. **Resume Builder / History Export:** Solves a long-term problem, not the immediate daily cortisol spike.
4. **Mental Health Hub:** Guided breathing or counseling links distract from the core utility of time visualization.

## Prioritization Summary (Feature Grid)

| Category    | Features | Rationale |
|------------|----------|-----------|
| Must-Have  | • 3-Second Quick-Add<br>• Unified School-Work Timeline<br>• "Break it Down" (Mountain Crusher)<br>• Gap Alerts | These solve the core "mental bookmark" failure and the "mountain" effect. Without these, the app is just another generic calendar. |
| Should-Have| • Focus Mode (Single Task View)<br>• "Low-Cortisol" Themes<br>• Emergency Panic Filter<br>• Shift-Aware Snooze | These address the user's emotional state. They aren't vital for tracking, but they are vital for retention of a stressed-out student. |
| Could-Have | • Photo-to-Schedule Sync<br>• Scrolling Credits (Gamification)<br>• Task Energy Tagging (Mountain vs. Hill)<br>• Spotify/Focus Music Integration | These are "delighters." They make the app feel modern and helpful but aren't necessary for the first week of use. |
| Won't-Have | • 24/7 AI Tutor / Concept Explainer<br>• Ghost Study Rooms (Social)<br>• Bank/Earnings Integration<br>• Success Report Exports | These are out of scope. They increase complexity, data privacy concerns, and development time without solving the immediate procrastination loop. |