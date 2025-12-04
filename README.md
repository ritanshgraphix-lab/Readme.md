# SkillSwap Hub
### COM4113 – Tech Stack Assignment  
Leeds Trinity University

---

## 1. Overview
SkillSwap Hub is a front-end web application that allows users to share learning resources, create user profiles, explore community posts, use AI tools, and interact through comments, ratings, and bookmarks.

The platform demonstrates:
- Front-end development skills using HTML, CSS, JavaScript  
- Data handling using LocalStorage  
- UI/UX planning, responsive design, and layout structuring  
- Documentation skills including timeline, sitemap, and full report  

This prototype is fully client-side and does not require any backend server.

---

## 2. Project Structure

SkillSwapHub/ │── index.html │── login.html │── signup.html │── comments.html │── styles.css │── script.js │── README.md │── Sitemap.png │── stylish_Sitemap.png │── Timeline.png │── Full report.pdf │── screenshots/

---

## 3. Features

### 3.1 Core Features (MVP)
- User registration and login using LocalStorage  
- Profile creation with Base64 image upload  
- Resource posting system  
- Explore page with live search and category filtering  
- Bookmarking and rating system  
- Comments system stored locally  
- AI Tools page auto-populated from JavaScript  
- Fully responsive UI layout  

### 3.2 Additional Enhancements
- Glassmorphism design  
- Gradient animated background  
- Page fade-in transitions  
- Modular JavaScript logic  
- Visual timeline and sitemap diagrams  

---

## 4. Technology Stack

### Front-End Technologies
- HTML5  
- CSS3  
- JavaScript (ES6)

### Data Storage
The project uses **LocalStorage** to store:
- `userAccount`  
- `profileData`  
- `resources`  
- `comments`  
- `bookmarks`  
- `ratings`

These values update dynamically as the user interacts with the platform.

### Tools Used
- Visual Studio Code  
- Live Server  
- Browser Developer Tools  
- FileReader API for image uploads  

---

## 5. System Functionality

### 5.1 Authentication
User signup and login are stored in LocalStorage:

userAccount = { name, email, password, skills }

### 5.2 Profile System
Profile data is saved as:

profileData = { name, skills, bio, photo(Base64) }

### 5.3 Resource Structure
Resources follow this structure:

{ title, description, category, link, rating, bookmarked }

### 5.4 Comments Structure

{ resourceIndex, text, time }

### 5.5 AI Tools
AI tools are loaded from a predefined JavaScript array.

---

## 6. Real-World Application Example
A platform like SkillSwap Hub can be applied in real-world learning environments.

### Example: Community-Based Learning Portal
Educational institutions, training centres, and online communities can use such a system to allow learners to:
- Share high-quality resources  
- Exchange skills (e.g., coding, baking, art, design)  
- Access AI tools (AI code assistants, AI design tools)  
- Collaborate on learning goals  

Real-world platforms with similar structure include Skillshare, Coursera forums, GitHub discussions, and Reddit educational communities.  
SkillSwap Hub demonstrates how a lightweight version of such platforms can be built using front-end technologies.

---

## 7. Sitemap
A visual sitemap is included:

Sitemap.png stylish_Sitemap.png

---

## 8. Development Timeline
A visual timeline of the project is included:

Timeline.png

### Timeline Summary

| Week | Work Completed |
|------|----------------|
| Week 1 | Research and requirement analysis |
| Week 2 | Planning, wireframing, tech stack selection |
| Week 3 | HTML page structure and layout |
| Week 4 | CSS styling, animations, responsive design |
| Week 5 | JavaScript functionality (search, rating, bookmarks, comments) |
| Week 6 | Testing, optimisation, final documentation |

---

## 9. Installation & Usage

### Step 1 – Clone or Download
```bash
git clone <repository-url>

Step 2 – Run the Project

Open:

index.html

or use VS Code Live Server.

Step 3 – No Dependencies Required

The project runs entirely inside the browser.


---

10. Legal & Ethical Considerations

No sensitive user data stored

Uses LocalStorage for prototype purposes only

Users must share legal/copyright-free content

Accessibility considerations implemented where possible

Ethical use of AI clearly declared



---

11. Future Improvements

Backend integration using Node.js and MongoDB

JWT-based authentication

Cloud-hosted image uploads

Real-time comments

User dashboards

Pagination for resource lists

AI-based personalised recommendations



---

12. AI Usage Statement

AI assistance was used only for documentation enhancement and structural improvements.
All coding and implementation of the platform were completed manually by the student.


---

13. References

Full APA references can be found in:

Full report.pdf
