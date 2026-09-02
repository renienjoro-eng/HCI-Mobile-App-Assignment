# HCI Mobile App Presentation Deck Outline

**Total Duration:** 10–15 Minutes

**Format:** Slide Deck (PowerPoint / Google Slides / Markdown) + Live Balsamiq Demo

---

## Slide 1: Title Slide

- **Title:** University Student Portal Mobile App – Human–Computer Interaction Project
- **Subtitle:** Prototype & Usability Evaluation Report
- **Course:** Human–Computer Interaction (HCI)
- **Presenter(s):** Group 1 (Joseph Nyori — folder organization, uploads, presentation template)
- **GitHub Repository:** [https://github.com/renienjoro-eng/HCI-Mobile-App-Assignment](https://github.com/renienjoro-eng/HCI-Mobile-App-Assignment)

---

## Slide 2: Project Overview & Problem Statement

- **Background:** University students regularly need access to academic and administrative services such as course registration, fee statements, academic results, and student profile information.
- **Problem Statement:** These services are often difficult to access, presented through complicated interfaces, or spread across multiple platforms, causing delays, confusion, and difficulty finding information.
- **Proposed Solution:** A centralized mobile application that brings common student services together in one simple and intuitive interface, designed using HCI principles and prototyped in Balsamiq.

---

## Slide 3: Target Users & Research Methodology

- **Target User Group:** University students (primary), including new students and continuing students who primarily use smartphones and require quick access to university information.
- **User Research Approach:** At least five user interviews/surveys conducted to understand how students access services, common difficulties, frequently used services, expectations of a mobile student portal, preferred navigation patterns, and how they prefer to receive feedback.
- **Key Research Findings:** Core insights that informed functional requirements, usability requirements, user personas, and the information architecture.

---

## Slide 4: User Personas

- **Persona 1 (Primary) — The New Student:**
  - **Background:** A university student still becoming familiar with university systems and services.
  - **Goals:** Easily find university services, register for courses without confusion, check fee information, access academic information.
  - **Pain Points:** Difficulty understanding complicated interfaces, difficulty locating specific services, uncertainty about whether an action was successful.
  - **Quote:** *(insert representative quote)*

- **Persona 2 (Secondary) — The Continuing Student:**
  - **Background:** A university student who regularly accesses academic and administrative services.
  - **Goals:** Register for courses quickly, check academic results, monitor fee information, manage student information.
  - **Pain Points:** Time-consuming processes, complicated navigation, difficulty locating frequently used information.
  - **Quote:** *(insert representative quote)*

---

## Slide 5: Functional & Usability Requirements

- **Core Functional Requirements:**
  - Student login and secure access
  - Student dashboard with quick access to services
  - Course registration (browse, select, review, confirm)
  - Fee statement viewing
  - Academic results viewing
  - Student profile viewing and editing
  - Feedback and confirmation after key actions
  - Consistent navigation between services

- **HCI / Usability Requirements:**
  - Simple and understandable language
  - Clear navigation and consistent layouts/controls
  - Visibility of system status and appropriate feedback
  - Touch-friendly controls for smartphone interaction
  - Error prevention and minimized unnecessary steps
  - Readable text and clear organization

---

## Slide 6: Information Architecture & Task Flow

- **Information Architecture:**
  - University Student Portal
    - Login
    - Dashboard (Courses / Fees / Results / Profile)
    - Mobile Navigation (Home / Courses / Fees / Results / Profile)

- **Core Task Flows:**
  - Course Registration: Login → Dashboard → Course Registration → Browse → Select → Review → Confirm → Registration Successful → Dashboard
  - Fee Statements: Login → Dashboard → Fee Statements → View → Review → Dashboard
  - Academic Results: Login → Dashboard → Academic Results → Select Period → View → Dashboard
  - Student Profile: Login → Dashboard → Profile → View → Edit → Save → Confirmation

---

## Slide 7: Initial Sketches & Low-Fidelity Wireframes

- **Early Concepts:** Side-by-side display of hand-drawn low-fidelity paper sketches vs. initial digital concepts (12 sketches covering splash, login, dashboard, courses, fees, results, profile).
- **Design Decisions:** Layouts chosen to prioritize mobile navigation, clear information hierarchy, touch-friendly controls, and consistency.

---

## Slide 8: Balsamiq High-Fidelity Prototype Overview

- **Interactive Prototype Overview:** 12+ linked mobile screens built in Balsamiq, including splash, login, dashboard, course registration, browse courses, select courses, review selection, registration confirmation, fee statements, academic results, student profile, and edit profile.
- **Mobile Navigation:** Navigation bar, back buttons, and gesture-friendly touch elements designed for smartphone screens.
- **The 3 Core User Scenarios:**
  - **Scenario 1:** Course registration — browse, select, review, confirm.
  - **Scenario 2:** Checking fee statements — login, view, review, return.
  - **Scenario 3:** Checking academic results — login, select period, view, return.

---

## Slide 9: Live Demo / Scenario Walkthrough

- **Format:** Embed short GIF/Video or transition to interactive Balsamiq walk-through.
- **Step-by-step demonstration** of the 3 user scenarios operating seamlessly across linked screens.

---

## Slide 10: Usability Testing & Findings

- **Testing Setup:** At least five representative user testing sessions.
- **Evaluation Metrics:** Task completion rate, user errors, time-on-task, and user satisfaction feedback.
- **Key Usability Issues Identified:** Top 3 usability bottlenecks discovered during testing (to be completed after testing).

---

## Slide 11: Design Iterations (Before & After)

- **Iterative Refinement:** Visual comparison showing Balsamiq screens before and after user feedback.
- **Applied HCI Principles:** Specific heuristic fixes applied — increased contrast, better button affordance, clearer confirmation dialogs, improved navigation consistency, and touch-friendly interactions.

---

## Slide 12: Team Contributions & GitHub Workflow

- **Team Responsibilities:**
  | Member | Role |
  |---|---|
  | Irene Njoroge | GitHub repo, collaborators, folder structure, README |
  | Irene Serianai | Research questionnaire/interview guide + interviews |
  | Rachael Muriithi | Problem statement, objectives, target users |
  | Alex Njenga | 2 user personas + user journey |
  | Francis Mwariri | Low-fidelity sketches |
  | Kibet Kerich | 4–6 Balsamiq screens |
  | Erickson Kibet | Information architecture |
  | Brian Kirunde | Functional + usability requirements |
  | Terence | Task flow diagrams + consistency review |
  | Joseph Nyori | Folder organization, upload tracking, presentation template |

- **GitHub Repository Structure:** `docs/`, `research/`, `wireframes/`, `usability-testing/`, `iterations/`, `final/` folders with meaningful commit history showing contributions from group members.

---

## Slide 13: Conclusion & Q&A

- **Key Takeaways:** Summary of project outcomes and learning experiences — a centralized, intuitive, and accessible student portal prototype built using HCI principles.
- **Future Work:** Potential feature additions — real university system integration, secure authentication, real-time results and fees, online payment, push notifications, and accessibility improvements.
- **Q&A:** Thank you! We welcome your questions.

---

## File Location in Repository

This outline is stored at:

```text
final/presentation_outline.md
```

To push directly from a terminal:

```bash
cat << 'EOF' > final/presentation_outline.md
# HCI Mobile App Presentation Deck Outline
...
EOF

git add final/presentation_outline.md
git commit -m "Add presentation slide deck outline to final directory"
git push origin main
```

---

*Prepared by Joseph Nyori — Group 1, HCI Mobile App Assignment.*
