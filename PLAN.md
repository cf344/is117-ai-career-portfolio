# IS117 Portfolio Plan

**Milestone:** Plan — due November 17, 2026, 8:30 a.m. Eastern  
**Status:** Plan recorded; Version B implemented November 18, 2026, with student-reported functional checks. Version A and Version B are implemented; Version A testing, peer A/B comparison, and final launch selection remain pending.

## Reader, goals, and research evidence

My main readers are recruiters, potential employers, classmates, and other visitors interested in my work. I am studying Enterprise AI at NJIT and want to show what I am learning through real projects, not just a list of skills.

My [career research](docs/career-research.md) compares Adobe's Machine Learning Engineer internship with Lingaro's Data Scientist (Generative AI) role. The listings highlight Python, machine learning, data, and AI applications. Those findings help me decide what evidence to show in my portfolio. I will not claim that I have skills or completed projects I cannot demonstrate.

## Step 1 — Compare two approaches and choose

**Option A: Simple one-page portfolio.** Put my introduction, skills, projects, and résumé on one scrolling page. This would be easier to build and navigate, but it could leave too little space to explain my work.

**Option B: Project-focused portfolio.** Use a homepage to introduce me, with clear sections or pages for my projects, career interests, résumé, and professional links. Visitors could explore real work and see what I learned.

**My decision: Option B.** I want the website to show what I can actually do instead of just listing skills. As an Enterprise AI student at NJIT, I want to highlight my programming, data analysis, and web development work. A project-focused design should help future employers understand my progress. This is my design decision, not a tested visitor preference.

## Step 2 — Five user stories, essential features, and observable checks

These are **planned checks**, not results.

### Story 1 — Learning about me
**As a visitor**, I want to read a short introduction so I can understand the student's background, major, and career interests.

- **Essential feature:** An About Me section introducing me as an Enterprise AI student at NJIT.
- **Observable check:** Open the homepage on a computer and a phone and confirm the introduction is easy to find and read.

### Story 2 — Exploring my projects
**As a recruiter or visitor**, I want to explore projects so I can see skills supported by actual work.

- **Essential feature:** A Projects section with accurate descriptions and GitHub links for my three IS117 projects: the [Off Hours T-shirt website](https://github.com/cf344/is117-brand-studio), the [Market Timeline Persuasion group project](https://github.com/cf344/market-time-line-persuasion) (shared team project; my role: team leader), and this [AI career portfolio](https://github.com/cf344/is117-ai-career-portfolio).
- **Observable check:** Open each project link and confirm it leads to the right repository; compare descriptions with the actual work. The group repository URL and README were verified; confirm individual team members' full names and GitHub usernames before submitting the group roster.

### Story 3 — Viewing my résumé
**As an employer**, I want to view or download a résumé so I can learn about the student's education, experience, and skills.

- **Essential feature:** A clearly labeled résumé link to a readable public PDF. A portfolio-focused copy has been prepared as `IS117_Portfolio_Resume.pdf`; it is uploaded to the repository and linked from the website's résumé section (`docs/index.html`).
- **Observable check:** Open the résumé on a computer and phone and confirm the PDF loads and its text is readable.

### Story 4 — Finding professional profiles
**As a recruiter**, I want to find GitHub and LinkedIn so I can explore the student's work and professional background.

- **Essential feature:** Clearly labeled links to my [GitHub profile](https://github.com/cf344) and my [LinkedIn profile](https://www.linkedin.com/in/clara-fesal-35174b450/) (link provided November 17, 2026).
- **Observable check:** Follow both links and confirm they open the correct profiles. Both public profile links are now included in the site. Their live destinations and mobile accessibility still need to be tested by the student.

### Story 5 — Understanding my career goals
**As a visitor**, I want to understand the student's AI career interests and how projects connect to those goals.

- **Essential feature:** A Career Interests section about AI, machine learning, and data science, linked to my [Adobe and Lingaro research](docs/career-research.md).
- **Observable check:** Open the section and research link; verify the claims match the research and do not exaggerate my experience.

## Implementation progress

- **Projects section added to `docs/index.html` (November 17, 2026):** Three project cards now describe Off Hours Brand Studio, the collaborative Market Timeline Persuasion project, and the AI Career Portfolio, each with a GitHub repository link. Descriptions emphasize learning and documented work, not unverified professional experience.
- **Still to verify:** Open the deployed site on desktop and phone, find the Projects section, open all three repository links, and confirm the descriptions match the repositories. Do not record these new checks as passed before testing.

## Test observations

### Résumé link — desktop/browser check (November 17, 2026)

- **Test:** Open the published portfolio, follow the Résumé navigation link, then open **View Résumé (PDF)**.
- **Observed result (student-reported):** The résumé PDF opened and its text was readable.
- **Status:** Passed for the browser/device used by the student; a separate mobile link/navigation check was subsequently reported as passed.
- **Next check:** On a phone, open the published portfolio, find the Résumé section, tap **View Résumé (PDF)**, confirm the PDF opens and is readable without awkward horizontal scrolling, and report the result.

### Mobile portfolio check (November 17, 2026)

- **Test (student-reported):** Opened the published portfolio on a phone and tried the available links.
- **Observed result:** Everything worked and all links tested were accessible from the phone.
- **Status:** Passed for the mobile checks reported by the student. This does not verify any future features or links not yet published.

### Projects section — published website check (November 17, 2026)

- **Test (student-reported):** Opened the published portfolio website, located the Projects section, and followed each of the three GitHub project links.
- **Observed result:** The Projects section was visible, all three project cards appeared, and each GitHub link worked.
- **Status:** Passed for the published-site visibility and link checks reported by the student. Descriptions and mobile layout of the new section have not been separately verified.
- **Deployment note:** The student observed a successful GitHub Pages build and deployment run #12 before testing the updated site.

### Professional Profiles — published website check (November 17, 2026)

- **Test (student-reported):** Opened the published Professional Profiles section and followed its GitHub and LinkedIn links.
- **Observed result:** GitHub opened the correct `cf344` profile and LinkedIn opened the correct public profile.
- **Status:** Passed for both profile links on the browser/device tested. Mobile testing of these newly added profile links is not separately confirmed.

### Peer review — GitHub Issue #1 (November 17, 2026)

- **Feedback received:** Reviewer praised navigation and career comparisons, reported a 404 on the résumé link, and recommended more spacing between text-heavy sections. The review did not include a full mobile test.
- **Decision and changes:** Updated the résumé link to the PDF in the repository and increased section and paragraph spacing in `docs/index.html`.
- **Evidence:** [Peer-review issue #1](https://github.com/cf344/is117-ai-career-portfolio/issues/1); [website fix commit](https://github.com/cf344/is117-ai-career-portfolio/commit/70ac35a2806ae90e1682ac39cd5f892dc1c9d45d).
- **Retest history (student-reported):** The spacing looked more readable (**passed**). The first replacement résumé link still failed because GitHub's PDF preview did not display correctly. I then switched the website link to a direct PDF download and renamed it **Download Résumé (PDF)** ([fix commit](https://github.com/cf344/is117-ai-career-portfolio/commit/c0ef8de89943c3a055112d9e3b790efc6ca84886)).
- **Final retest (student-reported):** From the published portfolio, the updated résumé link downloaded the PDF and the student opened it successfully (**passed**). Both reviewer suggestions have been addressed and retested by the student. Reviewer retry/confirmation has been requested; this is not a claim that the reviewer has retested.

## Visual direction and honest persuasion

I want a clean, modern, professional site that still feels personal. I plan to use consistent colors, readable fonts, clear navigation, and project cards. I will carry forward the decision to show **evidence of work** rather than make unsupported claims. I am still learning, so project descriptions should explain my actual contributions and what I learned. I will not present future work as completed.

## Open questions and next steps

- Group project repository confirmed: [cf344/market-time-line-persuasion](https://github.com/cf344/market-time-line-persuasion). Its README identifies Clara (team leader), Mishal, Aryanna, and Tas; verify full names and GitHub usernames for each member before submitting the group roster.
- LinkedIn status (November 17, 2026): I supplied my public LinkedIn URL and added it alongside my GitHub profile to the live site's Professional Profiles section. **Verified:** Both links opened the correct profiles in the student's published-site test. **Remaining:** optional mobile retest of these newly added links.
- A portfolio-friendly one-page résumé PDF has been prepared from my existing résumé, focusing on NJIT education, relevant technical skills and projects, work experience, and transferable skills. **Uploaded:** `IS117_Portfolio_Resume.pdf` is on the repository's `main` branch. **Linked:** `docs/index.html` now points Download Résumé (PDF) to the direct GitHub PDF download URL. **Latest retest:** The site now links to the direct PDF download and labels it Download Résumé (PDF). The student downloaded and opened the PDF successfully from the published website (**passed**).
- Decide the specific page layout, colors, and navigation; build the portfolio.
- Run the planned checks on desktop and mobile, recording actual outcomes.
- Request classmate feedback through GitHub issues; for each issue, record my decision, linked change or reason for deferral, verification, and reviewer retry before closing.
- Keep the existing research and planning record updated; submit repository, documentation, deployed-site (when available), and feedback evidence links in Canvas.

## AI assistance

ChatGPT helped organize and draft this plan and its test ideas using my existing career research. I selected Option B and am responsible for checking the accuracy of my work, making decisions, and recording actual test results.

## Build — Version B implementation and test (November 18, 2026)

- **Working version:** [Project-focused portfolio Version B](https://cf344.github.io/is117-ai-career-portfolio/version-b.html).
- **Source:** [docs/version-b.html](docs/version-b.html); [implementation commit](https://github.com/cf344/is117-ai-career-portfolio/commit/5c156389501538e596ce7e5ebea1473e20fb6368).
- **Design:** Responsive project-focused layout with an introduction, three project cards, career interests, résumé PDF, and GitHub/LinkedIn links. Group work is explicitly labeled in progress. Original research homepage was preserved for comparison.
- **Student-reported check — project links:** All three project links opened correctly (**passed**).
- **Student-reported check — résumé:** PDF downloaded and opened (**passed**).
- **Student-reported check — mobile:** Version B layout worked on the student's phone (**passed**).
- **Scope:** These are the student's observations, not an independent reviewer retry or automated accessibility audit.
- **Remaining:** Create and test a working Version A; ask a classmate to perform the same task in both versions; record feedback and a reasoned launch decision; request reviewer retry on any resolved issues. Existing résumé peer-review issue #1 remains open pending independent reviewer confirmation.

**AI use:** ChatGPT helped implement Version B and record these student-reported results; the student performed the checks.

## Build — Version A implementation (November 18, 2026)

- **Working version:** [Simple one-page portfolio Version A](https://cf344.github.io/is117-ai-career-portfolio/version-a.html).
- **Source:** [docs/version-a.html](docs/version-a.html); [implementation commit](https://github.com/cf344/is117-ai-career-portfolio/commit/2bfc14a43b421a61912acfd83641966f7650b665).
- **Design:** Minimal light-background single scrolling page with About, Skills, Projects, Career, Résumé, and Profiles sections. The same project repositories and résumé resource are available as in Version B, with a simpler presentation.
- **Status:** File committed; student browser/mobile checks and peer comparison have not yet been reported. Do not mark these as passed until observed.
- **Comparison task for reviewer:** In each version, find the Off Hours project repository and download the résumé. Record whether each task succeeds, navigation clarity, and which version is easier to use; report through a GitHub issue.
- **Next:** Student tests Version A, classmate attempts both versions, and the student records feedback, linked changes, retests, and a reasoned launch choice.

**AI use:** ChatGPT helped implement Version A and draft the comparison plan; actual test results must be recorded by the student and reviewer.

## Version A deployment retest — November 18, 2026

- **Problem observed:** Student reported a 404 / Page Not Found when opening the newly created Version A link.
- **Change made:** Added direct Version A and Version B navigation links to the published research homepage, triggering a new Pages deployment ([commit](https://github.com/cf344/is117-ai-career-portfolio/commit/02bb7057c76d90b28a43ea95193ea19207fc3029)). Version B source was not modified.
- **Student-reported retest:** “all work” after the change; Version A now opens successfully (**passed**).
- **Limits:** This confirms the reported deployment issue was resolved. Separate Version A checks for each project link, résumé download, and phone layout have not been individually reported, and peer A/B testing is still pending.

## A/B peer-review request — November 18, 2026

- **Issue opened:** [#2 — Compare Portfolio Version A vs Version B](https://github.com/cf344/is117-ai-career-portfolio/issues/2).
- **Same tasks in both versions:** Find the Off Hours GitHub repository and download/open the résumé PDF.
- **Reviewer asked to report:** Whether both tasks worked in each version, navigation clarity, preference with reason, and a specific improvement.
- **Status:** Feedback requested; no classmate results received or independently verified yet. After feedback, document the decision, any linked change, student retest, and reviewer retry before closing.
