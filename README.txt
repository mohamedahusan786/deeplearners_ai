━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
  LearnAI — Your AI Micro-Learning Platform
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

FILES IN THIS FOLDER
────────────────────
learnai-landing.html    → Public homepage (show this to the world)
learnai-login.html      → Sign up / Sign in page (Firebase Auth)
learnai-onboarding.html → AI quiz that builds a personal learning path
learnai-player.html     → Course player with AI tutor (Aiko)

USER FLOW
────────────────────
Landing page → Login → Onboarding quiz → Course player

BEFORE YOU DEPLOY
────────────────────
1. Go to firebase.google.com → create a free project
2. Enable Authentication → Email/Password + Google
3. Create a Firestore Database (test mode)
4. Go to Project Settings → Your apps → Web app → copy config
5. Open learnai-login.html in a text editor
6. Find the firebaseConfig block and replace YOUR_API_KEY etc.
   with your actual values

DEPLOY TO NETLIFY (easiest)
────────────────────
1. Go to netlify.com/drop
2. Drag this entire folder onto the page
3. Done — you get a free live URL in 60 seconds
4. Add your netlify URL to Firebase authorized domains

DEPLOY TO VERCEL
────────────────────
1. Create a GitHub repo, upload these files
2. Go to vercel.com → New Project → import repo → Deploy

SUPPORT
────────────────────
Built with Claude (claude.ai)
Firebase free tier — supports up to 10,000 logins/month
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
