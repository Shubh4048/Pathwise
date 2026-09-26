# Project TODO

- [x] Build the marketing landing page with the specified headline, subheading, benefits, CTAs, and honest-career positioning
- [x] Add authenticated entry and protected product navigation
- [x] Implement validated five-step onboarding for profile, current skills, goal, constraints, and career preferences
- [x] Add career goal suggestions, custom goals, and uncertain-goal support
- [x] Add persistent profile, career goal, roadmap, phase, task, project, assessment, progress, and coach data models
- [x] Implement AI-backed structured career analysis and roadmap generation with realistic, non-guaranteed language
- [x] Implement Career Reality Check with strengths, prerequisites, skill gaps, difficulty, and journey estimate
- [x] Implement adaptive roadmap updates for completed work, weak prerequisites, missed days, limited time, and goal changes
- [x] Build the authenticated dashboard centered on today’s plan and next actionable step
- [x] Build Roadmap experience with ordered phases, objectives, prerequisites, durations, projects, and completion criteria
- [x] Build Today’s Tasks experience with checkboxes, duration, difficulty, resources, completion tracking, shortened plans, and “I don’t understand this.” help
- [x] Build Projects experience with objectives, requirements, milestones, outputs, and portfolio guidance
- [x] Build Progress experience with roadmap, task, skill, project, streak, weekly consistency, milestone, and weak-area tracking
- [x] Build AI Coach experience grounded in the user’s profile, roadmap, progress, and current plan
- [x] Build Profile experience with editable preferences and career-goal change flow
- [x] Establish elegant responsive visual system for desktop and mobile with accessible states and restrained motion
- [x] Add Vitest coverage for career workflow and task completion behavior
- [x] Run typecheck, tests, and responsive visual verification
- [x] Save a final checkpoint and deliver the project version

- [x] Define free versus premium CareerPath AI features and upgrade messaging
- [x] Add subscription entitlement data and protected premium backend procedures
- [x] Add premium upgrade page and premium feature gates across roadmap, coach, assessments, and progress
- [x] Defer payment-ready checkout integration because the current release is intentionally free-only
- [x] Defer premium entitlement UX testing because premium UI was intentionally removed from the current release
- [x] Defer freemium release checkpoint because the current release is intentionally free-only

- [x] Defer Razorpay replacement because payment integration is intentionally not part of the current release
- [x] Defer Razorpay identifiers and webhook verification until premium billing is revisited
- [x] Defer premium upgrade UI and INR/UPI configuration because premium UI was removed
- [x] Defer Stripe cleanup from the user-facing release because checkout is not exposed
- [x] Defer Razorpay entitlement testing and India-ready payment checkpoint until premium billing is requested again

- [x] Verify the landing-page brand edit from CareerPath AI to Pathwise AI and confirm styling consistency
- [x] Run typecheck, tests, and a landing-page screenshot verification
- [x] Save and deliver the updated Pathwise checkpoint

- [x] Remove premium sections, upgrade prompts, and billing actions from the user-facing Pathwise app
- [x] Fix onboarding name persistence so the entered name replaces the Alex Morgan fallback throughout the workspace
- [x] Replace India-specific and role-specific onboarding examples with globally neutral instructions and placeholders
- [x] Test the free workspace, onboarding identity flow, and updated copy on desktop and mobile
- [x] Save and deliver the updated free Pathwise checkpoint

- [x] Add a directly testable display-name resolver covering custom onboarding names and legacy Alex fallbacks
- [x] Verify the custom-name flow logic across dashboard, sidebar, and profile surfaces
- [x] Save and deliver a new checkpoint after the free-only cleanup

- [x] Create a new minimal Pathwise logo asset for app and social use
- [x] Replace the old sparkle mark across landing, onboarding, sidebar, and metadata surfaces
- [x] Verify logo rendering consistently on desktop and mobile
- [x] Save and deliver the updated logo-integrated Pathwise checkpoint

- [x] Enable user-selectable light and dark themes across the app
- [x] Add accessible theme toggle controls to public and authenticated surfaces
- [x] Verify dark-mode contrast on landing, onboarding, and workspace views
- [x] Save and deliver the dual-theme Pathwise checkpoint

- [x] Replace the static greeting with a local browser-time-aware greeting
- [x] Add testable morning, afternoon, evening, and night boundaries
- [x] Verify time-aware greetings on desktop and mobile workspace views
- [x] Save and deliver the time-aware Pathwise checkpoint

- [x] Replace hardcoded streak and progress metrics with values derived from completed tasks
- [x] Add tests for one-task completion and zero/completed task progress states
- [x] Remove the inactive Settings navigation entry or make it functional
- [x] Verify dashboard metrics and navigation on desktop and mobile
- [x] Save and deliver the corrected metrics checkpoint
