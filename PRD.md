This Product Requirements Document (PRD) outlines the technical and aesthetic specifications for the **Mind the Gap** landing page. It merges the sophisticated animations of *Cregg Paris* and *Sunrise Robotics* with the playful, high-utility UI of *Design Beyond Barriers* and *Poolside AI*.

---

# PRD: Mind the Gap Landing Page v1.0

## 1. Project Overview

**Mind the Gap** is an Irish psychology-backed study platform. The landing page must bridge the gap between "clinical psychology" and "student lifestyle," appearing professional yet highly accessible and energetic.

**Core Objective:** Drive conversions for the 12-question diagnostic tool.

---

## 2. Visual Identity & Design Language

* **Theme:** Light Mode (High-contrast, clean white backgrounds).
* **Primary Color Palette:** * **Core Blue:** #0055FF (Trust, Intelligence).
* **Accents:** Soft greys and "Cognitive Teal" (from the reference sites).


* **Typography (Inspired by Poolside AI):**
* *Headings:* Large, bold, tightened kerning (inter-letter spacing). Use a modern Sans-Serif like **Inter** or **Manrope**.
* *Body:* High readability, generous line height ().


* **Motion (Inspired by Sunrise Robotics & Cregg Paris):**
* **Scroll-Triggered Reveals:** Elements should fade and slide upward as they enter the viewport.
* **SVG Path Animations:** Use "line drawing" effects to visually connect the "Gap" as the user scrolls.



---

## 3. Functional Requirements (Mobile-First)

* **Responsiveness:** Fluid grid system. Desktop (1440px), Tablet (768px), and Mobile (375px).
* **Navigation (Inspired by Gentle Systems):** * Sticky header with a "Blur/Glassmorphism" effect.
* Mobile: A clean, full-screen overlay menu with large touch targets.


* **Performance:** LCP (Largest Contentful Paint) under 1.5s. Optimized WebP images and deferred JS for animations.

---

## 4. Detailed Component Breakdown

### 4.1 Navigation Bar

* **Behavior:** Transparent at the top; transitions to a solid/blurred white background on scroll.
* **CTA:** "Get Started" button remains visible on all devices.

### 4.2 Hero Section (The "Cregg Paris" Animation)

* **Visual:** A central "Gap" visual. As the page loads, animated dots or abstract "neural paths" bridge the gap.
* **Headline:** "Study Smarter, Not Harder. Backed by Psychology."
* **Interaction:** Subtle mouse-parallax effect on the background elements.

### 4.3 The 3-Step "How It Works"

This section uses **Design Beyond Barriers** style cards:

1. **The Diagnostic:** Visual of a 12-question progress bar.
* *Copy:* "How does your brain process info? Take 2 minutes to find out."


2. **The Study Hub:** A "fan" visual showing 1 of 700 personalized dashboard variations.
* *Copy:* "Your Hub, Your Rules. Personalized courses and subject recommendations."


3. **The AI Assistant:** A floating chat bubble visual.
* *Copy:* "24/7 support. Accountability streaks to keep the momentum."



### 4.4 Feature Showcase (Grid Layout)

* **Interactive Cards:** On hover, cards should lift (Shadow-pop) and icons should play a subtle loop animation.
* **Mobile:** These stack into a single-column carousel or a vertical list with "Reveal on Scroll."

### 4.5 Cognitive Profile Preview

* **Function:** A "peek" at what a profile looks like.
* **UI:** Use a radar chart or a "strength bar" visual to show different learning styles (e.g., Visual, Sequential, Active Recall).

---

## 5. Technical Stack Recommendations

| Layer | Technology | Reason |
| --- | --- | --- |
| **Frontend** | React or Next.js | Fast routing and component reusability. |
| **Animations** | GSAP (GreenSock) | To match the "Sunrise Robotics" scroll precision. |
| **Styling** | Tailwind CSS | Rapid UI development with mobile-first breakpoints. |
| **Icons** | Lucide-React | Clean, consistent stroke weight (matches Poolside AI). |

---

## 6. Optimization & Conversion Points

1. **Sticky CTA:** On mobile, a "Take the Diagnostic" button should pin to the bottom of the screen after the user scrolls past the Hero.
2. **Micro-copy:** Use "Irish-nuanced" friendly language to build local trust.
3. **Trust Badges:** "Verified Psychology Framework" badge placed near every CTA.

---

