# Smart India Hackathon Workshop
# Date:
## Register Number:212224040365
## Name:Vishal S 
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
1. Virtual Board Room Simulation
Develop an AI-driven virtual interview platform that simulates a real-life boardroom experience.
Include an interactive interface for candidates and experts, ensuring a structured and professional interview process.
2. AI-Based Question Generation & Relevancy Check
AI algorithm to generate relevant ice-breaking, technical, and managerial questions based on the candidate’s expertise.
Dynamic question selection based on the candidate’s responses to previous questions.
Ensure unbiased and structured questioning.
3. Automated Candidate Response Evaluation
AI/NLP-based assessment of candidate responses for relevance, depth, and correctness.
Grading mechanism to score responses based on technical accuracy and communication clarity.
4. Expert-Driven Customization & AI Assistance
Experts can manually set questions, or AI can suggest relevant questions based on job roles.
AI-assisted scoring to support experts in making objective assessments.
5. Quantifiable Scoring System
Assign weights to different question categories (basic, technical, managerial, etc.).
Generate a final score reflecting the candidate's subject knowledge and suitability.
6. Bias Reduction & Fair Evaluation
AI-driven cross-validation of questions and answers to reduce bias.
Ensure consistency in interview evaluations across different candidates.
7. Interview Recording & Analysis
Store and analyze interviews for review and training purposes.
Provide insights for continuous improvement of the interview process.
8. User-Friendly Dashboard for Experts & Candidates
Real-time performance tracking for candidates.
Expert panel dashboard for reviewing scores, feedback, and AI-generated insights.
## Proposed Solution / Architecture Diagram
![Screenshot 2025-03-06 211130](https://github.com/user-attachments/assets/fac91bf4-7170-4d13-817d-d38aab526ed0)
## Use Cases
![Screenshot 2025-03-06 212318](https://github.com/user-attachments/assets/a29d4193-0f4d-4925-8334-24eb881e44d2)
## Technology Stack
```
1. Frontend (User Interface)
Purpose: Interactive UI for selectors (experts) and applicants (candidates).
Tech Stack:

React.js / Next.js – Fast, component-based UI with server-side rendering capabilities.
Tailwind CSS / Material UI / Bootstrap – For a clean and responsive design.
WebRTC / Socket.io – For real-time video/audio-based interviews.
Chart.js / Recharts / D3.js – For data visualization (scoring, performance insights).
2. Backend (Business Logic & APIs)
Purpose: Handling interview logic, AI scoring, and data processing.
Tech Stack:

Node.js (Express.js) / FastAPI (Python) – Lightweight, fast, and scalable backend.
Python (for AI/ML processing) – NLP-based response evaluation.
Redis – For caching real-time data to improve performance.
3. AI/ML Components
Purpose: Automate question relevance, response evaluation, and bias detection.
Tech Stack:

NLP Models (BERT / OpenAI GPT / SpaCy) – For response analysis.
Scikit-learn / TensorFlow / PyTorch – For ML-based scoring models.
LangChain / OpenAI API – For dynamic question generation.
Fairness-Aware ML Models – To reduce bias in evaluations.
4. Database (Storage & Retrieval)
Purpose: Store user profiles, interview questions, scores, and responses.
Tech Stack:

PostgreSQL / MySQL – For structured interview data (candidate details, questions, scores).
MongoDB – For unstructured data storage (responses, AI logs).
Elasticsearch – For fast searching of interview records.
5. Video & Audio Integration
Purpose: Enable virtual boardroom-style interviews.
Tech Stack:

WebRTC / Agora / Twilio – For real-time video and audio communication.
FFmpeg – For recording and processing interview sessions.
6. Authentication & Security
Purpose: Secure access to the platform.
Tech Stack:

OAuth 2.0 / JWT – For secure user authentication.
AWS Cognito / Firebase Auth – For easy authentication handling.
Role-Based Access Control (RBAC) – For different user types (selectors, candidates, admins).
7. Cloud & Deployment
Purpose: Host and scale the application.
Tech Stack:

AWS (EC2, S3, RDS) / Google Cloud / Azure – Cloud hosting.
Docker & Kubernetes – For containerization and scalability.
Nginx / Traefik – Load balancing and reverse proxy.
8. DevOps & Monitoring
Purpose: Continuous deployment and system monitoring.
Tech Stack:

GitHub Actions / Jenkins – For CI/CD automation.
Prometheus & Grafana – For monitoring system health.
Sentry / LogRocket – For real-time error tracking.
9. Reporting & Analytics
Purpose: Generate insights from interviews.
Tech Stack:

Power BI / Metabase / Apache Superset – For analytics and reporting.
Python (Pandas, NumPy) – For data processing and visualization.
```
## Dependencies
```
Frontend:
React.js / Vue.js / Angular – UI framework
Tailwind CSS / Bootstrap – Styling
Axios / Fetch API – API requests
Backend:
Node.js (Express.js) / Django / Flask / Spring Boot – Server-side logic
GraphQL / REST API – Data communication
Database:
PostgreSQL / MySQL – Relational DB
MongoDB / Firebase – NoSQL option
Auth & Security:
JWT / OAuth2 / Firebase Auth – Authentication
Bcrypt / Argon2 – Password hashing
AI & Simulations (if needed):
TensorFlow.js / PyTorch – AI models
OpenAI API / LangChain – AI-driven interactions
Deployment & DevOps:
Docker / Kubernetes – Containerization
AWS / Google Cloud / Firebase – Hosting
Nginx / Apache – Web server
```
