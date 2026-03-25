# Freelance Marketing Hub

A comprehensive workflow management system for freelance marketers.

## 🚀 Features
- **Dashboard**: Real-time stats and revenue growth chart.
- **Client CRM**: Manage leads with WhatsApp quick-connect.
- **Content Planner**: Schedule posts with AI-powered copywriting (Gemini AI).
- **Task Board**: Kanban-style task tracking.
- **Ads Tracker**: Monitor campaign performance and CPL.
- **Invoice Tracker**: Track payments and revenue.

## 🛠️ Deployment on Vercel

1. **Push to GitHub**: Push this code to your GitHub repository.
2. **Import to Vercel**: Go to [vercel.com](https://vercel.com) and import your repository.
3. **Set Environment Variables**: In the Vercel dashboard, go to **Settings > Environment Variables** and add:
   - `GEMINI_API_KEY`: Your Google Gemini API Key.
4. **Deploy**: Vercel will automatically detect the Vite project and deploy it.

## 📦 Local Development

1. Install dependencies:
   ```bash
   npm install
   ```
2. Create a `.env` file and add your `GEMINI_API_KEY`.
3. Start the dev server:
   ```bash
   npm run dev
   ```
