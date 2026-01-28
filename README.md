# Android IT Ticketing System

## Project Proposal - CSTP 2205

# Overview of the Project:

The project entails creating an IT Ticketing System for Android. This
system enables employees to submit IT support tickets through an Android
app, while IT support personnel can access, update, and resolve these
tickets. The app targets around 20 internal users and is being developed
by a team of three developers within an 8 to 12-week timeframe. The
focus is on core features to streamline delivery and reduce complexity.

# Project Scope:

### Inclusions:

\- Development of an Android app with Kotlin

\- Implementation of secure authentication

\- Functionality to create, view, and update IT tickets

\- Backend REST web service

\- Utilization of a MongoDB cloud database

\- Intuitive UI

### Exclusions: (future features)

\- Push notifications

\- File uploads

\- Web admin dashboard

\- Analytics and reporting

# System Architecture:

The system architecture is based on a client-server model. The Android
app communicates with a backend web service via HTTPS using REST APIs.
The backend manages authentication, business processes, and data
retrieval, with all data stored in MongoDB Atlas.

# **Backend Web Service**:

The backend is created using Ktor, a lightweight Kotlin web framework.
It offers RESTful endpoints for authentication and ticket management,
implementing JWT for security.

# **Database Setup:**

MongoDB Atlas serves as the database, with two primary collections:
Users and Tickets. MongoDB was chosen for its adaptability and seamless
integration with Kotlin.

# **Project Timeline**:

The project spans 8-12 weeks, divided into four 2-week sprints:

\- Sprint 1: Setup, UI and architectural planning

\- Sprint 2: Ticket creation and viewing features

\- Sprint 3: Authentication mechanisms and lifecycle management

\- Sprint 4: Testing, deployment, and documentation

\- Sprint 5 -- 6 Buffer for any spill over.

- Challenges: scheduling of story, considering dependencies

# Developer Updates:

1\. What have I contributed since the last time we met? (Contribution)

2\. What will I have contributed before the next we meet? (Next Steps)

3\. What am I stuck with that the team can help me with? (Challenges)

Bhupinder:

\- Contributions: Android UI design and navigation

\- Next Steps: Finalize ticket screens and integration

\- Challenges: Aligning API responses, Learning curve of new
technologies

Michael:

\- Contributions: Backend API development and MongoDB configuration

\- Next Steps: Implement authentication and validation

\- Challenges: Learning curve of new technologies

Salvador:

\- Contributions: Authentication system development and integration

\- Next Steps: Testing and deployment tasks

\- Challenges: Deployment setup configurations, Learning curve of new
technologies

# Tools

\- Jira Story --
https://wond3r.atlassian.net/jira/software/projects/ITS/boards/34/timeline

\- MongoDB Atlas -
mongodb+srv://xxdb_user:xx@wond3r.ffwy0co.mongodb.net/?appName=Wond3r

\- GitHub - https://github.com/bsa-13/ITTick-Wonder3

\- Back End Node.js -- Hosted at AWS LightSail
