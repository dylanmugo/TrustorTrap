# TrustOrTrap – Cyber Awareness PWA  

**TrustOrTrap** is a Progressive Web Application (PWA) designed to introduce students and new users to the fundamentals of cybersecurity awareness through fun and interactive learning.  
The app delivers **three gamified experiences** to teach essential cyber safety skills, with collaboration and gamification features to keep learners engaged.  

---

##  Objectives  
- Provide a beginner friendly platform for essential cybersecurity practices.  
- Develop **three educational games** that mirror real-world cyber threats.  
- Use **gamification** (coins, levels, badges, leaderboards) to increase motivation.  
- Support **team collaboration**, allowing users to learn together.  
- Deliver a **mobile-first, responsive PWA** with strong usability.  
- Cover the **full software development lifecycle** (analysis - design -  implementation - testing - documentation).  

---

##  Core Features  

###  Authentication  
- Secure user registration and login.  
- Password hashing and session management.  
- MongoDB + JWT for authentication.  

###  Games  
| Game | Learning Outcome |  
|------|------------------|  
| **Spotting Phishing** | Identify phishing attempts vs. safe messages. Recognise common red flags in malicious communication. |  
| **Protecting a Cyber Pet** | Understand safe practices (strong passwords, avoiding bad links). Wrong choices harm the pet. |  
| **Social Media Scam Awareness** | Distinguish between real and fake social media scenarios, improving scam detection skills. |  

###  Collaboration  
- Users can form **teams/groups**.  
- Shared progress and **group leaderboards**.  
- Collaborative challenge-solving.  

###  Gamification  
- Earn **coins** for completing games.  
- Progression with **badges & levels** (e.g. *Cyber Novice → Cyber Master*).  
- **Leaderboards** for individuals and teams.  

---

##  Tech Stack  
- **Frontend:** Next.js (React) + TailwindCSS  
- **Backend:** Node.js / Express  
- **Database & Auth:** MongoDB Atlas + JWT  
- **Hosting:** Vercel (frontend + backend)  
- **Version Control:** GitHub  

---

##  Project Plan  

### Semester 1 – Prototype Development  
- Weeks 1–2: Brainstorming, research, GitHub + Overleaf setup, scope confirmation.  
- Weeks 3–4: UI mockups, wireframes, database schema design.  
- Week 5: Implement authentication (MongoDB + JWT).  
- Weeks 6–7: Build first game (*Phishing Game*).  
- Week 8: Add coin system linked to user accounts.  
- Week 9: Develop dashboard for user progress.  
- Week 10: Internal testing of prototype.  
- Weeks 11–12: Documentation and demo prep.  

**Deliverable (End of Semester 1):**  
- Login/Registration system  
- One working game (*Phishing Game*)  
- Coin system integrated  

### Semester 2 – Full Implementation  
- Add *Cyber Pet* and *Social Media Scam Awareness* games.  
- Expand gamification (levels, badges, leaderboards).  
- Implement team/group collaboration features.  
- Improve UI/UX polish.  
- Conduct testing (functional, usability, evaluation).  
- Prepare final presentation + report.  

**Deliverable (End of Semester 2):**  
- Fully working PWA with all three games  
- Gamification + collaboration features complete  
- Final report and oral defence  

---

##  Security & Accessibility  
- Secure dev practices: input validation, HTTPS, session protection, password hashing.  
- Accessibility: WCAG guidelines (colour contrast, ARIA labels, keyboard navigation).  

---

##  Testing & Evaluation  
- Functional testing of all core features.  
- Usability testing with students for feedback.  
- Evaluation of user learning improvements after gameplay.  

---

##  Deliverables  
- Use Case Diagrams, ER Diagrams, UI Wireframes  
- Prototype demo video  
- Final report + oral defence  

---

##  Getting Started  

### Prerequisites  
- Node.js (v18+)  
- npm or yarn  
- MongoDB Atlas account  

### Installation  
```bash
# Clone the repo
git clone https://github.com/your-username/trustortrap.git

# Move into folder
cd trustortrap

# Install dependencies
npm install

# Run dev server
npm run dev
