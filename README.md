<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

# Run and deploy your AI Studio app

This contains everything you need to run your app locally.

View your app in AI Studio: https://ai.studio/apps/drive/1q8g0pQI2RtoDlHOb-pdFBkDHqH22meiZ

## Run Locally

**Prerequisites:**  Node.js


1. Install dependencies:
   ```bash
   npm install
   ```
2. Set up your API key:
   - Copy `.env.example` to `.env.local`:
     ```bash
     cp .env.example .env.local
     ```
   - Edit `.env.local` and add your Gemini API key:
     ```
     VITE_GOOGLE_API_KEY=your_actual_api_key_here
     ```
   - Get your API key from: https://aistudio.google.com/app/apikey

3. Run the app:
   ```bash
   npm run dev
   ```
4. Open your browser at the URL shown (usually http://localhost:3000 or http://localhost:3001)

