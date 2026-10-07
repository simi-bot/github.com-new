---
name: apple-design-skill
description: "סקיל עיצוב אפל" — the umbrella entry point for the full Emil Kowalski design-engineering pack (Apple-style fluid UI, animation, polish, mobile feel, Swift). Use when the user says "סקיל עיצוב אפל", "עיצוב אפל", asks for Apple-style design or UI polish in general, or isn't sure which design/animation skill fits. Routes to the right specialized skill.
---

# סקיל עיצוב אפל

This is the umbrella skill for the design pack. Figure out what the user needs, then invoke the matching skill below with the Skill tool and follow it. If the user hasn't asked anything specific yet, reply in Hebrew with one short line saying you're ready, and list the options briefly.

| When the user wants to... | Skill |
|---|---|
| Design in Apple's style: springs, gestures, sheets, momentum, materials, typography | `apple-design` |
| Polish UI and get the details right (Emil's philosophy) | `emil-design-eng` |
| Build a new animation or transition for the web | `animate` |
| Animate in React Native / Expo | `animate-expo` |
| Review existing animation code | `review-animations` |
| Audit all the motion in a codebase and plan improvements | `improve-animations` |
| Find places that should animate but don't | `find-animation-opportunities` |
| Name an effect from a vague description ("what's it called when...") | `animation-vocabulary` |
| Make a web app feel native on a phone / PWA | `mobile-native` |
| Stress-test a component with worst-case data | `break-ui` |
| Build several variations of a UI piece and pick one | `prototype` |
| Choose a frontend library for a task | `pick-ui-library` |
| Work with Sonner toasts | `ask-sonner` |
| Write or review modern Swift | `write-swift` |

If the request spans several (for example "build an Apple-style sheet and check it"), run them in order: design (`apple-design`), then build (`animate`), then review (`review-animations`).
