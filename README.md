# SKY-HIRE

### 🔍 Real-time Job Aggregator & AI Skill Gap Recommender

SKY-HIRE uses UiPath Studio for automated job scraping, which collects job postings from various sources and organizes them into structured CSV files. Rather than depending on general keyword based search results, the system uses content-based filtering to match job descriptions to user profiles. Additionally, Gen AI uses the Gemini API to assess skill-job compatibility, computing a match percentage and finding skill gaps. To help users improve their qualifications, the system suggests appropriate online courses, LeetCode challenges, hands-on projects, certificates, and open-source contributions for experience depending on their skills gaps. 

---

## 📌 Features

- 🔄 **Live Job Listings** – Automatically fetched using UiPath bots.
- 🧠 **AI Recommendations** – Personalized skill enhancement suggestions using Gemini's Generative AI.
- 🔐 **Secure Authentication** – Handled with Firebase.
- 🌐 **Modern Web Stack** – Fast, scalable frontend & backend.
- 🎯 **Job Matching** – Relevant roles shown based on user preferences and profile.

---

## 🖼️ UI/UX Design

Explore the complete Figma prototype for design and UX flow:  
👉 [SKY-HIRE Figma Design](https://www.figma.com/proto/zk3pEpUvrPD0dsbbJNp8eS/SKY-HIRE?page-id=0%3A1&node-id=1-2&p=f&viewport=320%2C-313%2C0.21&t=VOqQQBZXpcu9csAd-1&scaling=scale-down&content-scaling=fixed&starting-point-node-id=1%3A2&show-proto-sidebar=1)

---

## 🛠️ Technologies Used

| Feature | Stack |
|--------|--------|
| Job Scraping | UiPath |
| Scheduling | UiPath Orchestrator |
| Frontend | React.js |
| Backend | Django |
| Authentication | Firebase |
| AI Recommendation Engine | Gemini API (Generative AI) |

---

## 🚀 Getting Started

1. **Clone the repository**  
   ```bash
   git clone https://github.com/Tejasri0608/SKY-HIRE.git
   cd SKY-HIRE

2. **Install dependencies**  
   ```bash
   npm install

3. **Start the development server**  
   ```bash
   npm run dev
