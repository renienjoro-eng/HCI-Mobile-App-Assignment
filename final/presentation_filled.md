# HCI Mobile App Presentation Deck Outline — FILLED

**Total Duration:** 10–15 Minutes

**Format:** Slide Deck (PowerPoint / Google Slides / Markdown) + Live Balsamiq Demo

**Project:** University Student Portal Mobile App — Group 1 (BBIT 3.1 / CIT3108 / CIT4101 HCI)

---

## Slide 1: Title Slide

- **Title:** University Student Portal Mobile App – Human–Computer Interaction Project
- **Subtitle:** Prototype & Usability Evaluation Report
- **Course:** Human–Computer Interaction (HCI)
- **Presenter(s):** Group 1
  - Irene Njoroge (C027-01-0882/2024) — GitHub repo, collaborators, structure, README
  - Irene Serianai (C027-01-0848/2024) — Research questionnaire/interview guide + interviews
  - Rachael Muriithi (C027-01-0895/2024) — Problem statement, objectives, target users
  - Alex Njenga (C027-01-0830/2024) — 2 user personas + user journey
  - Francis Mwariri (C027-01-0829/2024) — Low-fidelity sketches
  - Kibet Kerich (C027-01-0917/2024) — 4–6 Balsamiq screens
  - Erickson Kibet (C027-01-2798/2024) — Information architecture
  - Brian Kirunde (C027-01-0886/2024) — Functional + usability requirements
  - Terence Kamau (C027-01-0790/2023) — Task flow diagrams + consistency review
  - Joseph Nyori (C027-01-0460/2022) — Folder organization, uploads, presentation template
- **GitHub Repository:** [https://github.com/renienjoro-eng/HCI-Mobile-App-Assignment](https://github.com/renienjoro-eng/HCI-Mobile-App-Assignment)

---

## Slide 2: Project Overview & Problem Statement

- **Background:** University students need to access different services during their studies — course registration, fee statements, academic results, and student profile information. Finding these services can be difficult or take too much time; students may need to use different systems or go through several steps before they find the information they need.
- **Problem Statement:** University students may have difficulty accessing important university services quickly and easily. Finding information about fees, results, courses, and student profiles can be confusing and time-consuming. Therefore, there is a need for a simple University Student Portal Mobile App that allows students to access important university services from their smartphones in one place.
- **Proposed Solution:** A centralized mobile application that brings common student services together in one simple and intuitive interface, designed using HCI principles and prototyped in Balsamiq. The prototype emphasizes simple navigation, clear information architecture, consistency, and touch-friendly interaction.

---

## Slide 3: Target Users & Research Methodology

- **Target User Group:**
  - University students (primary)
  - New students
  - Continuing students
  - Students registering for courses
  - Students checking fees and academic results
- **User Research Approach:**
  - **Method:** Short student interviews (10–15 minutes each)
  - **Participants:** 5 university students (P01–P05), all completed
  - **Location:** University campus / online
  - **Research questions:**
    - How do you currently access university services?
    - What problems do you experience when accessing these services?
    - Which university service do you use most often?
    - How easy is it to find the information you need?
    - Would you prefer to access university services through a mobile app?
    - Which features would you like to have in the mobile app?
    - What would make the app easy to use?
    - What problems have you experienced with university systems?
    - Would notifications be useful to you?
    - What is one thing you would improve about the current system?
- **Key Research Findings:**
  - 4 out of 5 students found accessing university services difficult.
  - 5 out of 5 students wanted to view fees using the app.
  - 5 out of 5 students wanted to view academic results.
  - 4 out of 5 students wanted course registration.
  - 3 out of 5 students wanted a student profile feature.
  - 3 out of 5 students wanted notifications.
  - All 5 students preferred a mobile application over the current system.
  - Students preferred several university services in one app with simple, clear navigation.

---

## Slide 4: User Personas

- **Persona 1 (Primary) — Brian Kamau (New Student):**
  - **Background:** 20 years old, BBIT programme, 2nd year.
  - **Goals:** Register for courses quickly; check examination results; view his fee statement; receive important university announcements.
  - **Needs:** A single platform for accessing student services; simple course registration; easy access to academic results and fee information; notifications about important university activities.
  - **Pain Points:** Has to use different systems or visit offices to access some services; sometimes struggles to know whether course registration was successful; delayed access to important academic information.
  - **Technology Habits:** Uses a smartphone every day; frequently uses mobile applications for communication, education, and online services; prefers self-service applications rather than visiting offices.
  - **Quote:** *(insert representative quote)*

- **Persona 2 (Secondary) — Mary Wanjiku (Continuing Student):**
  - **Background:** 22 years old, Bachelor of Business Administration, 4th year.
  - **Goals:** Monitor her fee balance; check examination results; access academic information remotely; receive updates about graduation and university activities.
  - **Needs:** Quick access to financial information; reliable academic records; notifications for important deadlines; a convenient way to access university services from anywhere.
  - **Pain Points:** Sometimes needs to visit university offices to obtain information; difficulty keeping track of different university announcements; waiting for assistance when she needs information urgently.
  - **Technology Habits:** Uses a smartphone regularly; comfortable using mobile banking, social media, and educational applications; prefers mobile services that are quick and easy to understand.
  - **Quote:** *(insert representative quote)*

---

## Slide 5: Functional & Usability Requirements

- **Core Functional Requirements (from Requirements doc):**
  - Student Login
  - Student Profile Management
  - Course Registration (browse, select, review, confirm)
  - View Registered Courses
  - View Fee Statement
  - View Academic Results
  - Easy Navigation
  - Notifications
  - Search Function
  - Logout
- **Mobile Usability Requirements (from Requirements doc):**
  - Simple Navigation, Consistency, Simple Interface, Readability
  - Touch-Friendly Controls, Fast Response, Error Prevention
  - Ease of Learning, Minimal Steps, Accessibility
  - User Feedback, Responsive Design
- **User Needs (from Research, ranked):**

  | User Need | Importance |
  |---|---|
  | Easy access to fees | High |
  | Easy access to results | High |
  | Simple course registration | High |
  | Easy navigation | High |
  | Student profile management | Medium |
  | Notifications | Medium |
  | Clear confirmation messages | Medium |

---

## Slide 6: Information Architecture & Task Flow

- **Information Architecture:**

  ```text
  University Student Portal
  ├── Login
  ├── Dashboard
  │   ├── Course Registration
  │   │   ├── Browse Courses
  │   │   ├── Select Courses
  │   │   ├── Review Selection
  │   │   └── Registration Confirmation
  │   ├── Fee Statements
  │   │   └── Fee Details
  │   ├── Academic Results
  │   │   └── Results Details
  │   └── Student Profile
  │       └── Edit Profile
  └── Mobile Navigation
      ├── Home
      ├── Courses
      ├── Fees
      ├── Results
      └── Profile
  ```

- **Core Task Flows (from Task Flows doc):**

  **Brian — Course Registration:**

  ```text
  START → Open Student Portal → Login → Dashboard → Course Registration
  → View Available Courses → Select Required Courses → Review Selected Courses
  → Confirm / Register → Registration Successful → View Registered Courses → END
  ```

  | Stage | User Action | User Goal | Experience |
  |---|---|---|---|
  | 1. Open App | Opens the student portal | Access university services | Easy |
  | 2. Login | Enters username and password | Access account | Easy |
  | 3. Dashboard | Selects Course Registration | Find registration service | Positive |
  | 4. View Courses | Views available courses | Choose required courses | Positive |
  | 5. Select Courses | Selects courses for the semester | Complete registration | Easy |
  | 6. Review | Checks selected courses | Avoid mistakes | Positive |
  | 7. Confirm | Taps Register/Confirm | Submit registration | Easy |
  | 8. Confirmation | Receives confirmation message | Know registration succeeded | Positive |
  | 9. View Courses | Opens registered courses | Confirm final registration | Positive |

  **Mary — Checking Fee Statement:**

  ```text
  START → Open Student Portal → Login → Dashboard → Fee Statement
  → View Current Fee Statement → Review Fees Paid & Outstanding Balance
  → Save / Download Statement → Receive Relevant Fee Notification → END
  ```

  | Stage | User Action | User Goal | Experience |
  |---|---|---|---|
  | 1. Open App | Opens the student portal | Access account | Easy |
  | 2. Login | Enters login details | Access student services | Easy |
  | 3. Dashboard | Selects Fee Statement | Find financial information | Positive |
  | 4. View Statement | Opens current fee statement | Check balance | Easy |
  | 5. Review | Checks fees paid and outstanding balance | Understand financial status | Positive |
  | 6. Save/Download | Saves the statement | Keep a record | Easy |
  | 7. Notification | Receives relevant fee notification | Stay informed | Positive |

---

## Slide 7: Initial Sketches & Low-Fidelity Wireframes

- **Early Concepts (from Francis Mwariri's sketches):** 12 low-fidelity sketches covering Splash Screen, Login Screen, Student Dashboard, Course Registration, Browse Courses, Select Courses, Review Course Selection, Registration Confirmation, Fee Statements, Academic Results, Student Profile, and Edit Profile.
- **Design Decisions:** Layouts chosen to prioritize mobile navigation, clear information hierarchy, touch-friendly controls, and consistency. Standardized terminology across documentation (see Slide 12): use "Student Portal" for the app/portal, "Dashboard" for the main landing screen, "Course Registration" for Brian's service, and "Fee Statement" for Mary's service; confirmation terminology standardized to "Registration Successful" / "confirmation message".

![Low-fi wireframe page 1](screens/lowfi-page-01.png)
![Low-fi wireframe page 2](screens/lowfi-page-02.png)

---

## Slide 8: Balsamiq High-Fidelity Prototype Overview

- **Interactive Prototype Overview:** 12+ linked mobile screens built in Balsamiq, including splash, login, dashboard, course registration, browse courses, select courses, review selection, registration confirmation, fee statements, academic results, student profile, and edit profile. Evidence: `wireframes/hight fidelity.pdf`.
- **Mobile Navigation:** Navigation bar, back buttons, and gesture-friendly touch elements designed for smartphone screens. Navigation between Home, Courses, Fees, Results, and Profile.
- **The 3 Core User Scenarios:**
  - **Scenario 1 — Course Registration:** Browse available courses → select required courses → review selection → confirm registration → receive confirmation → view registered courses.
  - **Scenario 2 — Checking Fee Statements:** Login → fee statement → view current balance → review fees paid & outstanding balance → save/download statement → receive fee notification.
  - **Scenario 3 — Checking Academic Results:** Login → academic results → select academic period → view results → return to dashboard.

![High-fi prototype page 1](screens/hifi-page-01.png)
![High-fi prototype page 2](screens/hifi-page-02.png)

---

## Slide 9: Live Demo / Scenario Walkthrough

- **Format:** Embed short GIF/Video or transition to interactive Balsamiq walk-through.
- **Step-by-step demonstration** of the 3 user scenarios operating seamlessly across linked screens using `wireframes/hight fidelity.pdf`.
- **Walkthrough flow:**

  ```text
  Login → Dashboard → Course Registration → Browse → Select → Review → Confirm → Registration Successful → Dashboard
  Login → Dashboard → Fee Statements → View Balance → Review → Save/Download → Notification → Dashboard
  Login → Dashboard → Academic Results → Select Period → View Results → Dashboard
  ```

---

## Slide 10: Usability Testing & Findings

- **Testing Setup:** At least 5 representative user testing sessions. Each user completes the 3 core scenarios.
- **Evaluation Metrics:** Task completion rate, user errors, time-on-task, and user satisfaction feedback.
- **Usability Observations (from consistency review):**
  - Documentation is broadly consistent for the proposed university student portal mobile app.
  - The two personas, their goals and pain points, the two user journeys, and the HCI/user-centered design responses support the same self-service portal concept.
  - Terminology standardization improves clarity: "Student Portal" / "Dashboard" / "Course Registration" / "Fee Statement" / "Registration Successful".
  - No major contradictions identified in the supplied documentation.
- **Key Usability Issues Identified:** Top 3 usability bottlenecks to be completed after testing (template placeholder — fill after session).

---

## Slide 11: Design Iterations (Before & After)

- **Iterative Refinement:** Visual comparison showing Balsamiq screens before and after user feedback. Evidence: `iterations/before/` and `iterations/after/`.
- **Applied HCI Principles (from consistency review):**
  - Centralized dashboard instead of scattered services
  - Digital self-service instead of visiting offices
  - Registration confirmation to remove uncertainty
  - Online fee statement instead of office visits
  - Push notifications for important announcements
  - Simple and consistent interface with standardized terminology
  - Larger, touch-friendly buttons and clear confirmation dialogs
  - Improved navigation consistency

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
  | Terence Kamau | Task flow diagrams + consistency review |
  | Joseph Nyori | Folder organization, upload tracking, presentation template |

- **GitHub Repository Structure:**

  ```text
  HCI-Mobile-App-Assignment/
  ├── README.md
  ├── docs/
  │   ├── University_Student_Portal_Requirements.docx
  │   ├── University_Student_Portal_Task_Flows_and_Consistency_Review.docx
  │   ├── User Personas and User Journey.docx
  │   └── coordination/
  ├── research/
  │   ├── HCI RESEARCH AND QUESTIONNARE.docx
  │   └── supporting-evidence/
  ├── wireframes/
  │   ├── Low fidelity Page 1.png
  │   ├── Low Fidelity Page 2.png
  │   ├── Low Fidelity wireframe sketches.pdf
  │   └── hight fidelity.pdf
  ├── usability-testing/
  ├── iterations/
  │   ├── before/
  │   └── after/
  ├── final/
  │   ├── final-prototype/
  │   ├── presentation/
  │   └── final-report/
  └── presentation_outline.md
  ```

---

## Slide 13: Conclusion & Q&A

- **Key Takeaways:**
  - A centralized, intuitive, and accessible student portal prototype built using HCI principles.
  - User research with 5 students confirmed demand for a mobile portal — all 5 preferred a mobile app.
  - Two personas (Brian Kamau, Mary Wanjiku) grounded the design in real user goals and pain points.
  - Documentation is broadly consistent across personas, journeys, task flows, and HCI responses.
  - Standardized terminology ("Student Portal", "Dashboard", "Course Registration", "Fee Statement", "Registration Successful") improves clarity.
- **Future Work:** Potential feature additions — real university system integration, secure authentication, real-time results and fees, online payment, push notifications, and accessibility improvements.
- **Q&A:** Thank you! We welcome your questions.

---

## Source Documents (all in repo)

| File | Author | Content |
|---|---|---|
| `docs/University_Student_Portal_Requirements.docx` | Brian Kirunde | Functional + usability requirements |
| `docs/University_Student_Portal_Task_Flows_and_Consistency_Review.docx` | Brian Kirunde | Task flows (Brian + Mary) + terminology standardization |
| `docs/User Personas and User Journey.docx` | Alex Njenga | Personas + user journeys + HCI connection |
| `research/HCI RESEARCH AND QUESTIONNARE.docx` | Group 1 | Research method, findings, user needs, participant summary |
| `wireframes/Low Fidelity wireframe sketches.pdf` | Francis Mwariri | Low-fidelity sketches |
| `wireframes/hight fidelity.pdf` | Kibet Kerich | Balsamiq prototype |

---

*Filled by Joseph Nyori from the group's uploaded documents. Original team files untouched.*
