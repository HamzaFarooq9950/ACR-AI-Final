# JobSync AI 🚀

**Final Project — Ship Your AI App**

## a. App Overview
**App Name:** JobSync AI  
**What it does:** JobSync AI is a comprehensive, Kanban-style job application tracker equipped with an AI career coach. It allows users to organize their job hunt across different stages (Wishlist, Applied, Interviewing, Offered, Rejected) while leveraging AI to automatically generate tailored cover letters and interview preparation guides based on specific job descriptions.  
**The real problem it solves:** Job seekers often apply to dozens of roles, leading to a chaotic mess of spreadsheets and forgotten deadlines. Furthermore, tailoring cover letters and preparing for specific interviews is highly time-consuming. JobSync AI centralizes the tracking process and automates the most tedious parts of the application workflow.  
**Target Audience:** Job seekers, recent graduates, and professionals looking to transition careers efficiently.

---

## b. Live Deployed URL
🔗 **[Live Demo: JobSync AI](https://jobsync-ai-demo.vercel.app)** *(Note: Example URL)*

---

## c. Features List
*   **Kanban Application Board:** Drag-and-drop interface to move applications between stages (Wishlist, Applied, Interview, Offer, Rejected).
*   **Application Detail View:** Save job descriptions, salary bands, company details, and important dates for each application.
*   **AI Cover Letter Generator:** Instantly generate a personalized cover letter matching your saved resume profile to a specific job description.
*   **AI Interview Prep:** Generate potential interview questions and strategic answering tips based on the job requirements.
*   **Analytics Dashboard:** Visual breakdown of your application success rate and pipeline health.
*   **Secure Authentication:** User accounts to keep application data private and secure.

---

## d. The AI Feature
**What it does:** The "AI Career Coach" is deeply integrated into the application detail view. When a user pastes a job description into a new application card, they can click "Generate Application Kit". The AI reads their globally saved profile/resume and the specific job description to output a highly customized cover letter and 3 tailored interview questions.

**System Prompt / Instructions:**
> "You are an expert career coach and technical recruiter. You will be provided with a user's resume summary and a target job description. 
> 
> Your task is two-fold:
> 1. Generate a concise, professional, and highly tailored cover letter (max 300 words) that bridges the user's specific past experiences with the core requirements of the job description. Do not hallucinate skills the user does not have.
> 2. Generate exactly 3 highly specific interview questions the candidate is likely to face for this exact role, along with a 1-sentence tip on how to answer each using the STAR method.
> 
> Format the output clearly with markdown headers."

---

## e. Tech Stack
*   **Frontend:** Next.js (App Router), React, Tailwind CSS
*   **Backend/Database:** Supabase (PostgreSQL, Row Level Security)
*   **Authentication:** Supabase Auth
*   **AI Model:** OpenAI `gpt-4o-mini` (via Vercel AI SDK)
*   **Hosting/Deployment:** Vercel

---

## f. Screenshots

*(Replace these placeholder links with actual image paths once in your repo)*

1. **The Kanban Board (Main Dashboard)**
![Kanban Board Placeholder](https://via.placeholder.com/800x450.png?text=Kanban+Board+Showing+Job+Stages)

2. **AI Cover Letter & Interview Prep Generator**
![AI Feature Placeholder](https://via.placeholder.com/800x450.png?text=AI+Generating+Cover+Letter+and+Prep)

3. **Application Details & Analytics**
![Analytics Placeholder](https://via.placeholder.com/800x450.png?text=Application+Details+and+Success+Analytics)

---

## g. How to Run the Project Locally

To run this project on your local machine, follow these steps:

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/jobsync-ai.git
   cd jobsync-ai
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env.local` file in the root directory and add the following keys. *(Note: Never commit your actual API keys!)*
   ```env
   NEXT_PUBLIC_SUPABASE_URL=your_supabase_url
   NEXT_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
   OPENAI_API_KEY=your_openai_api_key
   ```

4. **Run the development server**
   ```bash
   npm run dev
   ```

5. **Open the app**
   Navigate to [http://localhost:3000](http://localhost:3000) in your browser to see the application
