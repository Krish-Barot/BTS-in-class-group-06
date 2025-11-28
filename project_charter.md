# Project Charter  
**Project Name:** BTS-in-class-group-05  

---

## 1. Introduction  
This project aims to develop a platform that connects individuals and small businesses with skilled tradespeople for services such as plumbing, electrical work, carpentry, and more. By bridging the gap between clients and service providers, the platform will simplify the process of finding trusted professionals and allow skilled workers to expand their reach and credibility.

---

## 2. Overview  

### Objectives  
- To build an intuitive web platform that connects users seeking trade services with qualified tradespeople.  
- To enable users to browse, post, and manage service requests efficiently.  
- To provide tradespeople a way to showcase their expertise through profiles, listings, and reviews.  
- To implement secure authentication and account management for both users and providers.  
- To ensure a responsive and dynamic user experience through seamless frontend and backend integration.  

### Technologies  
- **Frontend:** React.js  
- **Backend:** Node.js with Express.js  
- **Database:** MongoDB  
- **Tools:** Git/GitHub for version control, Postman for API testing  

---

## 3. Milestones  

| Sprint | Milestone | Description |
|--------|------------|-------------|
| **Sprint 1** | Basic Trade Browsing & Display | Users can browse available trades and view listings. |
| **Sprint 2** | Trade Creation & Listing Management | Users can create and manage their trade listings. |
| **Sprint 3** | Detailed Trade Information Display | Users can view detailed trade information from the backend. |
| **Sprint 4** | Trade Modification & Updates | Users can edit and update their own trade listings. |
| **Sprint 5** | Trade Management & Cleanup | Users can delete outdated or unwanted trade listings. |
| **Sprint 6** | Advanced Trade Filtering | Users can filter trades by category or other preferences. |
| **Sprint 7** | Search & Discovery Enhancement | Users can search listings using keywords. |
| **Sprint 8** | User Profile & Final Deployment | Final user testing, bug fixes, and deployment. |

### 3.1 Work Breakdown Structure (WBS)
<img width="581" height="631" alt="wbs" src="https://github.com/user-attachments/assets/902365eb-0302-473c-bb94-c12cf80cb14e" />


### 3.2 Requirements Traceability Matrix (RTM)

| **Requirement ID** | **Requirement** | **Deliverable ID** | **Deliverable** | **Status** |
|--------------------|-----------------|--------------------|-----------------|-------------|
| RQ1 | The system shall allow users to create an account and log in securely. | D1 | User Authentication Module | Completed |
| RQ2 | The system shall allow users to post, edit, and delete trade listings. | D2 | CRUD Trade Listing Feature | In Progress |
| RQ3 | The system shall provide filtering and search functionality. | D3 | Search and Filter Module | Planned |
| RQ4 | The system shall display a user profile with listings and reviews. | D4 | User Profile Dashboard | Planned |
| RQ5 | The system shall be deployed on a live server for testing and feedback. | D5 | Deployed Web Application | Not Started |


---

## 4. Deliverables  

1. A responsive web application built with React, Node.js, and MongoDB.  
2. Functional user authentication (signup/login).  
3. Trade listing features (create, read, update, delete).  
4. Search and filter functionalities for listings.  
5. User profile management and dynamic dashboard.  
6. Documentation including setup guide and user instructions.  
7. Final deployed version on a hosting platform (e.g., Vercel/Render).

### 4.1 Gantt Chart
<img width="3352" height="912" alt="image" src="https://github.com/user-attachments/assets/e2228a21-b7e9-48b0-b881-f8fea7c4224f" />


---

## 5. Preliminary Budget  
Assumptions (Scrum Framework):

Team of 3 members

1. Developer Krish Barot(Backend): $35/hr
2. Developer Nish Patel(Frontend): $30/hr
3. Testing Ashutosh Verma(CI/CD and deployment): $25/hr

Weekly Sprint: 10 hours per person
8 Sprints Total

### 5.1 Personnel Cost Per Sprint

| Role          | Hours/Sprint | Rate (CAD) | Cost/Sprint |
|---------------|--------------|------------|--------------|
| Developer Krish Barot(Backend)   | 10           | $35/hr     | $350         |
| Developer Nish Patel(Frontend)   | 10           | $30/hr     | $300         |
| Developer Ashutosh Verma(CI/CD and deployment)   | 10           | $25/hr     | $250         |
| **Total Personnel Cost per Sprint** | **30 hrs** | — | **$900** |

### 5.2 Total Personnel Cost

| Item                | Amount |
|---------------------|--------|
| Cost per Sprint     | $900   |
| Number of Sprints   | 8      |
| **Total Personnel Cost** | **$7,200 CAD** |

### 5.3 Fixed Costs

| Item    | Qtd | Cost/Item          | Total Cost        |
|---------|-----|---------------------|-------------------|
| Hosting | 1   | $4.99 CAD/month     | $59.88 CAD/year   |
| Domain  | 1   | $12.99 CAD/year     | $12.99 CAD/year   |
| **Total Fixed Costs** | — | — | **$72.87 CAD/year** |

### 5.4 Contingency

Assuming a 10% contingency applied to personnel cost:

| Item              | Amount        |
|-------------------|---------------|
| Personnel Cost    | $7,200 CAD    |
| Contingency Rate  | 10%           |
| **Contingency Amount** | **$720 CAD** |


### 5.5 Total Estimated Cost

| Category               | Cost           |
|------------------------|----------------|
| Total Personnel Cost   | $7,200 CAD     |
| Fixed Costs            | $72.87 CAD     |
| Contingency            | $720 CAD       |
| **Grand Total**        | **$7,992.87 CAD** |

---

## 6. Organization and Stakeholders  

### Stakeholder Matrix
<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/ebcc9129-d4e1-4e58-bad1-fc5c7f466166" />


### Communications Plan
| Information                       | Owner                   | Audience              | Schedule      | Channel                       |
| --------------------------------- | ----------------------- | --------------------- | ------------- | ----------------------------- |
| Project Status Updates            | Project Manager         | Sponsor, Dev Team, QA | Bi-weekly     | Sprint Review + Email         |
| Development Updates               | Scrum Master            | Development Team      | Daily         | Standups + GitHub Issues      |
| Platform Updates for Tradespeople | Backend/Frontend Leads  | Tradespeople          | Monthly       | Email Newsletter              |
| End User Release Notes            | Product Owner           | End Users             | Every Release | In-app Notification + Website |
| System / Deployment Status        | DevOps / CI-CD Engineer | Dev Team, QA          | As Needed     | Slack / Teams                 |


---

## 7. Risks, Assumptions, and Constraints  

---



