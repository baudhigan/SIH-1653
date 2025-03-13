# Smart India Hackathon Workshop
# Date: 4/03/2025
## Register Number: 212223230028
## Name: Baudhigan D
## Problem Title
SIH 1653: Web based Selector-Applicant Simulation Software
## Problem Description
Background: Recruitment and Assessment Centre (RAC) under DRDO, Ministry of Defence carries out interviews for applications received against advertised vacancies and for promotion to next higher grade for scientific manpower inducted within DRDO. Description: The process of interviewing is a challenging task. An unbiased objective interviewing process helps identify the right talent. The basic process of an interview involves posing a set of questions by an interviewer and thereafter evaluating responses from candidates. Thus, the questions asked should be relevant and match the area/ expertise of the applicant and the responses should also be of relevance w.r.t. the question asked. Expected Solution: The proposed solution should provide experts as well as candidates a real life Board Room experience, starting with initial ice-breaking questions leading to in-depth techno-managerial (depending on the level of candidate) questions. It shall also be able to provide a quantifiable score for experts as well as the candidate for the relevancy of questions w.r.t. the area/ expertise of the applicant. Similarly, candidate responses should also be graded for relevancy w.r.t. the question asked, finally assisting in arriving at an overall score for the subject knowledge of the candidate and thus his/ her suitability against the advertised post.

## Problem Creater's Organization
Ministry of Defence

## Idea
### 1. Boardroom Simulation: 
 Develop an interactive platform where both the interviewer and the candidate are able to participate in a virtual interview setting. This would simulate a real-life boardroom experience, with tools for communication (video/audio/chat).
### 2. Automated Question Generation:
 The process should start with general, introductory questions (ice-breakers) and move into deeper (techno-managerial) questions, more specialized questions depending on the level of candidate driven by AI.
### 3. Candidate Response Evaluation:
 The candidate’s responses are analyzed in real-time using machine learning models which are trained to assess the relevance of the candidate's response to the question and the depth of knowledge displayed in the response.
### 4. Overall Performance Assessment:
 At the end of the interview, the system will generate a final score based on Relevancy and depth of responses, Correctness of answers and Communication and managerial abilities.
### 5. Analytics and Insights:
 Interviewers will have a comprehensive dashboard that shows the candidate’s performance over time, Scores for each individual question and a detailed breakdown of the candidate’s subject knowledge.


## Proposed Solution / Architecture Diagram
![Add a heading](https://github.com/user-attachments/assets/fe85f4e0-6198-459e-9aae-9f31204bb691)


## Use Cases
![Screenshot 2025-03-13 114814](https://github.com/user-attachments/assets/e2ee9992-a6ce-48c0-8d04-917100f9d487)


## Technology Stack
Frontend: React.js/Next.js, WebRTC (Video/Audio), Tailwind CSS

Backend: FastAPI/Flask, WebSockets, Celery + Redis

AI & NLP: GPT/BERT, Whisper (Speech-to-Text), spaCy/NLTK, TensorFlow

Database: PostgreSQL/MySQL, MongoDB, Elasticsearch

DevOps: Docker, Kubernetes, AWS/GCP, CI/CD (GitHub Actions)

## Dependencies
### Phase	Tasks	Time Estimate	Budget Estimate

1.. Planning & Research	Requirement gathering, defining scope, tech stack finalization	2-3 weeks	5,000 - 10,000
   
2.. UI/UX Design	Wireframes, mockups, user flows for boardroom simulation	3-4 weeks	8,000 - 15,000
   
3.. Frontend Development	Implement React-based UI, WebRTC integration	5-6 weeks	15,000 - 25,000
   
4.. Backend Development	Develop API with FastAPI/Flask, integrate WebSockets	6-8 weeks	20,000 - 30,000
   
5.. AI & NLP Integration	AI-driven question generation, response evaluation	8-10 weeks	30,000 - 50,000
    
6.. Database & Security	Setup PostgreSQL/MongoDB, secure user data	4-5 weeks	10,000 - 20,000
    
7.. Testing & Debugging	Unit testing, load testing, AI accuracy evaluation	4-6 weeks	15,000 - 25,000
    
8.. Deployment & Optimization	Cloud deployment (AWS/GCP), performance tuning	3-4 weeks	10,000 - 20,000
   
9.. Maintenance & Support	Bug fixes, updates, AI model fine-tuning	Ongoing	5,000 - 10,000/month
    
Total Estimated Time: 6-9 months
Total Estimated Budget: 100,000 - 180,000
