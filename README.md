# DisasterPredict AI 🌍🚨

**Final Project — Ship Your AI App**

## a. App Overview
**App Name:** DisasterPredict AI  
**What it does:** DisasterPredict AI is a real-time environmental monitoring and early-warning web application. It allows users to input localized environmental data (or fetch it via location) to predict the likelihood of imminent natural disasters, specifically focusing on floods and severe storms.   
**The real problem it solves:** Many vulnerable communities lack access to localized, easy-to-understand disaster early-warning systems. Traditional weather apps provide data but do not interpret the immediate risk or provide tailored safety protocols. DisasterPredict AI translates raw environmental data into actionable risk assessments and survival protocols for everyday people.  
**Target Audience:** Residents in high-risk climate zones, local community leaders, and emergency response volunteers.

---

## b. Live Deployed URL
🔗 **[Live Demo: DisasterPredict AI](https://disasterpredict-ai-demo.vercel.app)** *(Note: Replace with your actual live URL)*

---

## c. Features List
*   **Real-Time Risk Dashboard:** A clean, color-coded dashboard displaying the current disaster threat level (Low, Moderate, High, Severe).
*   **Location-Based Analysis:** Users can input their city or coordinates to fetch immediate environmental parameters.
*   **AI Threat Assessor:** Processes current weather/seismic variables to predict specific disaster probabilities.
*   **AI Survival Guide Generator:** Automatically generates a step-by-step, localized emergency action plan based on the predicted disaster type.
*   **Historical Data View:** A chart showing recent environmental anomalies in the selected region.
*   **Emergency Contact Hub:** Quick-access list to local emergency services.

---

## d. The AI Feature
**What it does:** The "AI Threat Assessor & Guide" acts as the core engine. When a user submits their local data (temperature, precipitation rate, soil moisture, etc.), the AI evaluates this against historical disaster patterns. It then outputs a calculated risk summary and a customized, 3-step survival plan tailored to the exact threat (e.g., flash flooding vs. hurricane).

**System Prompt / Instructions:**
> "You are an expert meteorologist, environmental scientist, and emergency response coordinator. You will be provided with real-time environmental data for a specific location.
> 
> Your task is to:
> 1. Analyze the data and predict the most likely natural disaster threat (if any), providing a clear reasoning in 2-3 sentences.
> 2. Generate a 'Threat Level' rating (Low, Moderate, High, Severe).
> 3. Provide exactly 3 highly actionable, immediate safety instructions for residents in that area to prepare for this specific threat.
> 
> Output the response in a clear, urgent but calm tone using markdown formatting. Do not hallucinate data; base your assessment strictly on the parameters provided."

---

## e. Tech Stack
*   **Frontend:** Next.js, React, Bootstrap / Tailwind CSS
*   **Backend:** Node.js / Next.js API Routes
*   **Data Sourcing:** OpenWeather API (or similar environmental data API)
*   **AI Model:** OpenAI `gpt-4o-mini` (or your chosen model via API)
*   **Hosting/Deployment:** Vercel

---

## f. Screenshots

*(Replace these placeholder links with your actual image paths from your GitHub repo)*

1. **Main Dashboard & Location Input**
![Dashboard Placeholder](https://via.placeholder.com/800x450.png?text=Main+Dashboard+and+Location+Entry)

2. **AI Threat Assessment Analysis**
![AI Analysis Placeholder](https://via.placeholder.com/800x450.png?text=AI+Predicting+Disaster+Likelihood)

3. **Emergency Survival Action Plan**
![Action Plan Placeholder](https://via.placeholder.com/800x450.png?text=AI+Generated+Survival+Instructions)

---

## g. How to Run the Project Locally

To run this project on your local machine, follow these steps:

1. **Clone the repository**
   ```bash
   git clone [https://github.com/yourusername/disasterpredict-ai.git](https://github.com/yourusername/disasterpredict-ai.git)
   cd disasterpredict-ai
