STUDENT WORKSHEET: SDLC, AGILE, DEVOPS & GIT FOUNDATIONS 

Course Code / Subject: SOFTWARE ENGINEERING
Student Name: BERMIO, CARL JANN
Date: 8/29/2026 
Section: BSIT 3.5

GitHub Repository URL: https://github.com/423005329/sdlc-foundations-lab

PART 1: GITHUB ONBOARDING & SETUP VERIFICATION

Part 1: GitHub Account Creation & Onboarding 
Objective: Set up a centralized remote repository environment for future CI/CD and GitFlow Collaboration.

1. Account Registration Go to github.com and click Sign Up. Enter your academic email address, create a strong password, and select a professional username (e.g., j-perminola). Complete the verification puzzle and enter the launch code sent to your email.

2. Profile & Security Setup Set your display name to your full name and upload a profile picture. Go to Settings > Password and authentication and enable Two-Factor Authentication (2FA) using an authenticator app or SMS.

3. Verification Task Click the + icon in the top right and select New repository. Name the repository sdlc-foundations-lab, set visibility to Public, check Add a README file, and click Create repository. Copy your public repository URL to submit alongside Part 2.

Task Checklist 
● [ ] Created GitHub account using academic email. 
● [ ] Enabled Two-Factor Authentication (2FA) in Settings. 
● [ ] Created public repository named sdlc-foundations-lab with a README.md. 
● [ ] Pasted public repository link in the header above.

PART 2: REAL-WORLD ENGINEERING SCENARIOS Scenario A: SDLC & Framework Selection

Context: A fintech company wants to release a new peer-to-peer payment feature. A government regulatory agency requires complete compliance auditing before release, but competitors are rapidly capturing market share. 

Task:
1. Compare Waterfall vs. Agile (Scrum) for this launch using the criteria below:
   - Adaptability & Time-to-Market
   - Regulatory & Compliance Risk Handling
2. Choose a hybrid or primary framework (e.g., Scrum vs. Waterfall vs. Spiral). Explain your reasoning in 2–3 sentences.

Framework Comparison Table

Criteria                                           Waterfall                                  Agile (scum) 
Adaptability & Time-to-Market   Less flexible because requirements are usually decided at the beginning of the project. Changes later in the process can be difficult and costly.	Highly flexible because the team can adjust requirements and priorities after each sprint based on feedback.
Regulatory & Compliance Risk Handling    

2. Framework Recommendation & Justification: Which primary or hybrid framework (e.g., Scrum, Waterfall, or Spiral) do you recommend for this fintech regulatory project? Explain your choice in 2–3 sentences.
   
Answer: I recommend a hybrid method that combines agile (Scrum) with Waterfall. Scrum will enable the team to swiftly create the payment feature and adapt according to feedback, whereas Waterfall will be employed for documentation, testing, and obtaining regulatory approval. This method provides the organization with both rapidity and robust compliance, which are crucial for a fintech initiative.

Scenario B: DevOps & CI/CD Pipeline Breakdown Context: A team merges code, but the production app breaks during deployment because testing was done manually on individual laptops rather than in an automated pipeline. Task:

1. Identify where the communication and process gap occurred between Dev and Ops.

2. Map out the automated CI/CD pipeline stages (Plan → Code → Build → Test → Release → Deploy → ;Operate → Monitor) and state which stage would catch this bug before it reaches production.

1. Gap Analysis: Identify where the communication and process breakdown occurred between Dev and Ops.

Answer: The communication and process breakdown because Dev tested the code only on their own laptops, while Ops deployed it to production without automated testing. Dev and Ops did not have a shared CI/CD process to make sure the code worked correctly before deployment. 

2. Pipeline Stage Identification: Fill in the missing stages of the continuous assembly line and circle/bold the stage that catches local testing bugs before production release:
   
Plan → Code → Build → Test → Release → Deploy → Operate → Monitor

Scenario C: Git Lifecycle & Branching Strategy

1. Data Movement Command Mapping

Write the standard Git command used to transfer code between each environment:

● Working Directory → Staging Area: git add

● Staging Area → Local Repository: git commit

● Local Repository → Remote Repository (GitHub): git push

● Remote Repository → Working Directory: git pull

2. GitFlow Collision Prevention:
Explain how utilizing Feature Branches and a Develop branch prevents two developers from overwriting each other’s code on Main. ( 2 to 3 sentences)

Answer: Feature branches enable every developer to work on their individual code without altering the Main branch directly. The Develop branch integrates and tests the various features initially, allowing conflicts to be resolved before the final code merges into Main. This prevents developers from unintentionally erasing one another’s efforts.

FINAL SUBMISSION CHECKLIST ● [ ] Part 1 checklist completely verified. ● [ ] All scenario questions answered clearly. ● [ ] Repository set to Public for grading access.
