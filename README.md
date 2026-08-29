STUDENT WORKSHEET: SDLC, AGILE, DEVOPS & GIT FOUNDATIONS Course Code / Subject: SOFTWARE ENGINEERING

Student Name: BERMIO, CARL JANN

Date: 8/29/2026 
Section: BSIT 3.5

GitHub Repository URL:

PART 1: GITHUB ONBOARDING & SETUP VERIFICATION

Part 1: GitHub Account Creation & Onboarding Objective: Set up a centralized remote repository environment for future CI/CD and GitFlow Collaboration.

Account Registration Go to github.com and click Sign Up. Enter your academic email address, create a strong password, and select a professional username (e.g., j-perminola). Complete the verification puzzle and enter the launch code sent to your email.

Profile & Security Setup Set your display name to your full name and upload a profile picture. Go to Settings > Password and authentication and enable Two-Factor Authentication (2FA) using an authenticator app or SMS.

Verification Task Click the + icon in the top right and select New repository. Name the repository sdlc-foundations-lab, set visibility to Public, check Add a README file, and click Create repository. Copy your public repository URL to submit alongside Part 2.

Task Checklist ● [ ] Created GitHub account using academic email. ● [ ] Enabled Two-Factor Authentication (2FA) in Settings. ● [ ] Created public repository named sdlc-foundations-lab with a README.md. ● [ ] Pasted public repository link in the header above.

PART 2: REAL-WORLD ENGINEERING SCENARIOS Scenario A: SDLC & Framework Selection

Context: A fintech company wants to release a new peer-to-peer payment feature. A government regulatory agency requires complete compliance auditing before release, but competitors are rapidly capturing market share. Task:

Compare Waterfall vs. Agile (Scrum) for this launch using the criteria below: Adaptability & Time-to-Market Regulatory & Compliance Risk Handling
Choose a hybrid or primary framework (e.g., Scrum vs. Waterfall vs. Spiral). Explain your reasoning in 2–3 sentences.
Framework Comparison Table

Criteria Waterfall Agile (scum) Adaptability & Time-to-Market Slow and difficult to change. The whole project is usually completed before release. Fast and flexible. Features are developed in short sprints and can be changed easily. Regulatory & Compliance Risk Handling Strong. Has detailed documentation, testing, and approval steps, which are good for government requirements. Moderate. Can meet regulations, but the team must make sure compliance and documentation are included in every sprint.

Framework Recommendation & Justification: Which primary or hybrid framework (e.g., Scrum, Waterfall, or Spiral) do you recommend for this fintech regulatory project? Explain your choice in 2–3 sentences.
Answer: I recommend a Hybrid approach using Agile (Scrum) and Waterfall. Scrum will help the team develop the payment feature quickly and make changes based on feedback, while Waterfall will be used for documentation, testing, and regulatory approval. This approach gives the company both speed and strong compliance, which are important for a fintech project.

Scenario B: DevOps & CI/CD Pipeline Breakdown Context: A team merges code, but the production app breaks during deployment because testing was done manually on individual laptops rather than in an automated pipeline. Task:

Identify where the communication and process gap occurred between Dev and Ops.

Map out the automated CI/CD pipeline stages (Plan → Code → Build → Test → Release → Deploy → ;Operate → Monitor) and state which stage would catch this bug before it reaches production.

Gap Analysis: Identify where the communication and process breakdown occurred between Dev and Ops.

Answer: The gap happened because Dev tested the code only on their own laptops, while Ops deployed it to production without automated testing. Dev and Ops did not have a shared CI/CD process to make sure the code worked correctly before deployment. 2. Pipeline Stage Identification

Pipeline Stage Identification: Fill in the missing stages of the continuous assembly line and circle/bold the stage that catches local testing bugs before production release:
Plan → Code → Build → Test → Release → Deploy → Operate → Monitor

Scenario C: Git Lifecycle & Branching Strategy

Data Movement Command Mapping
Write the standard Git command used to transfer code between each environment:

● Working Directory → Staging Area: git add

● Staging Area → Local Repository: git commit

● Local Repository → Remote Repository (GitHub): git push

● Remote Repository → Working Directory: git pull

GitFlow Collision Prevention:
Explain how utilizing Feature Branches and a Develop branch prevents two developers from overwriting each other’s code on Main. ( 2 to 3 sentences)

Answer: Feature branches allow each developer to work on their own code without directly changing the Main branch. The Develop branch combines and tests the different features first, so conflicts can be fixed before the final code is merged into Main. This helps prevent developers from accidentally overwriting each other’s work.

FINAL SUBMISSION CHECKLIST ● [ ] Part 1 checklist completely verified. ● [ ] All scenario questions answered clearly. ● [ ] Repository set to Public for grading access.
