# Portfolio Professional Boost Plan

Elevate the portfolio from a standard dark theme to a premium "Senior Architect" showcase with high-end visuals, authoritative copy, and sophisticated micro-interactions.

## User Review Required

> [!IMPORTANT]
> I will be refining the core positioning statements. Please review the "Home Page" section below for the proposed hero text.
> I will also add a subtle "Noise" texture and "Cursor Glow" effect to the CSS/JS – these are modern premium design trends.

## Proposed Changes

### Visual Identity & UX
- **[MODIFY] [main.css](file:///c:/mhdev01/assets/css/main.css)**
    - Add a subtle background noise texture for depth.
    - Refine "Glassmorphism" variables for crisper borders.
    - Implement a "Bento Grid" feel for the "What I Do" and "Expertise" sections.
    - Add custom scrollbar styling.
- **[MODIFY] [main.js](file:///c:/mhdev01/assets/js/main.js)**
    - Add a "magnetic" effect to primary buttons.
    - Implement a "reveal" effect on scroll for all major components.

### Content & Positioning
- **[MODIFY] [index.md](file:///c:/mhdev01/index.md)**
    - **Hero Title**: "Designing the Backbone of Modern Enterprise SaaS"
    - **Hero Subtitle**: "30+ years of architecting scalable, audit-ready, and AI-powered systems. Transitioning enterprise reliability from Django/REST to modern **Python, FastAPI, & Next.js Microservices**."
    - Refactor "What I Do" into more authoritative "Strategic Capabilities".
- **[MODIFY] [about.md](file:///c:/mhdev01/about.md)**
    - Enhance "30+ Years" with a "Years of Impact" highlight.
    - Specifically narrate the **Skills Upgrade**: The shift from Django/React monoliths to high-performance FastAPI/Next.js microservices architectures.
    - Refine the "Architecture Philosophy" to sound more like a set of "Architectural Guarantees".
- **[MODIFY] [projects.md](file:///c:/mhdev01/projects.md)**
    - Standardize project card heights and improve badge aesthetics.
    - Add "Impact" bullet points for each project.
    - Emphasize modern stack implementations (FastAPI, Next.js, **React Query/TanStack**) in recent projects.
- **[MODIFY] [architecture.md](file:///c:/mhdev01/architecture.md)**
    - Update "Typical Stack" to prioritize FastAPI and Microservices.
    - Add specific mention of **React Query** for UX optimization and performance.
    - Add a section on "Stack Evolution" or "Modernizing Enterprise Systems".

---

### Global Infrastructure
- **[MODIFY] [_config.yml](file:///c:/mhdev01/_config.yml)**
    - Refine tagline and description for better SEO and social sharing.

## Verification Plan

### Automated Tests
- This is a static site; I will use `npx -y lighthouse-ci` if available or manually verify performance and accessibility.
- Verify Jekyll build consistency (no broken links).

### Manual Verification
1. **Visual Check**: Open the site locally (if Jekyll is available) or via browser tool to check:
    - Gradient smoothness.
    - Typography clarity.
    - Responsive behavior on mobile (768px) and tablet (1024px).
2. **Interaction Check**:
    - Verify buttons feel reactive.
    - Verify scroll reveals trigger naturally.
3. **Copy Review**: Read through all pages to ensure the tone is "Senior & Authoritative" as requested.
