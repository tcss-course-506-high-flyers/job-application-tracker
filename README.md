## Job Application Tracker

A full-stack web application for tracking job applications, managing progress, and staying organized during the job search process.

---

### Team-3

**Team:** High Flyers  

**Members:**
- Boma (client-side)
- Aden (db-and-security)
- Darrell (server-side)

---

### Project

We are building **Option 3: Job Application Tracker** from the Week 4 lecture. The app allows users to log and manage their job applications, automatically pulls in company context from an external API, tracks application stages, and supports follow-up reminders.

---

### The User

This app is for active job seekers who are applying to multiple companies at once, such as students, recent graduates, or professionals transitioning careers. They need a centralized, low-friction way to track applications, follow up on opportunities, and understand their progress across different companies. Their goal is to stay organized, avoid missed opportunities, and clearly see their job pipeline at a glance.

---

### The MVP

Version 1 will support the following core features:

- GitHub OAuth login  
- Add a job application (company name, role, date applied, notes)  
- Auto-fetch basic company info via API and cache it per company  
- Track application stage (Applied → Interview → Offer → Rejected / Accepted)  
- Move applications between stages with a simple UI  
- Basic follow-up reminder flagging (e.g., "no update in 7 days")  

We will prioritize a working end-to-end flow (login → add application → update stage) before adding additional polish or UI enhancements.

---

### External APIs

**Primary:** Clearbit Company API — provides company logo, description, and industry data by domain name. We are aware of free-tier limits and will minimize calls through caching.  

**Backup:** API Ninjas Company Lookup or manual entry fallback. If API limits become restrictive, users can manually input company data, and it will be stored locally in our system.

---

### Why This Project

We chose the Job Application Tracker because it offers a strong balance between technical challenge and real-world usefulness. This is genuinely an application all of us might use. The project allows us to practice OAuth authentication, API integration with fallback strategies, relational data modeling, and interactive UI design. The workflow of tracking application stages also ensures meaningful client-side interactivity rather than static pages. Overall, this project aligns well with the skills we want to build and results in something we could confidently present.

---

README v1.0 — Week 4 setup (subject to revision)
