# Full Stack AI Image Editor with Next JS, Fabric.js, Tailwind, ImageKit, Shadcn UI Tutorial 🔥🔥

<img width="1470" alt="Landing Page" src="https://raw.githubusercontent.com/Lovely1236/Cresta/main/public/preview.png"/>

🔗 **Live Demo**: [Cresta on Vercel](https://cresta-4u.vercel.app)

[![Next.js](https://img.shields.io/badge/Next.js-13-black?logo=next.js)](https://nextjs.org/)
[![Fabric.js](https://img.shields.io/badge/Fabric.js-Canvas-blue)](http://fabricjs.com/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3.0-38B2AC?logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Clerk](https://img.shields.io/badge/Auth-Clerk-orange)](https://clerk.com/)
[![Convex](https://img.shields.io/badge/Backend-Convex-purple)](https://convex.dev/)
[![ImageKit](https://img.shields.io/badge/Images-ImageKit-green)](https://imagekit.io/)
[![Vercel](https://img.shields.io/badge/Deployed-Vercel-black?logo=vercel)](https://vercel.com/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

## ✨ Features
- 🎨 **Canvas Editing** – Built on Fabric.js for powerful image manipulation  
- 🤖 **AI Integration** – Smart editing & enhancements (extendable)  
- 🔑 **Authentication** – Secure login/signup powered by Clerk  
- ☁️ **Cloud Storage** – Images stored & optimized with ImageKit  
- ⚡ **Real-time Backend** – Convex for data and serverless functions  
- 💻 **Modern UI** – Responsive, clean design with TailwindCSS + Shadcn
---

## 🚀 Tech Stack
- **Frontend:** Next.js, React, TailwindCSS, Shadcn UI  
- **Image Editing:** Fabric.js  
- **Backend:** Convex (serverless backend)  
- **Authentication:** Clerk  
- **Image Hosting:** ImageKit  
- **Deployment:** Vercel  

---
## ⚙️ Installation & Setup

1️⃣ Clone the repo
```bash
git clone https://github.com/Lovely1236/Cresta.git
cd Cresta
```
2️⃣ Install dependencies
```
npm install
```

### Make sure to create a `.env` file with following variables -

```
# Deployment used by `npx convex dev`
CONVEX_DEPLOYMENT=

NEXT_PUBLIC_CONVEX_URL=

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up

CLERK_JWT_ISSUER_DOMAIN=

# Imagekit
NEXT_PUBLIC_IMAGEKIT_PUBLIC_KEY=
NEXT_PUBLIC_IMAGEKIT_URL_ENDPOINT=
IMAGEKIT_PRIVATE_KEY=

# Unsplash
NEXT_PUBLIC_UNSPLASH_ACCESS_KEY=
```
---
📂 Project Structure

Cresta/
│── app/            # Next.js app directory
│── components/     # Reusable UI components
│── context/        # Global React context
│── convex/         # Convex backend functions
│── hooks/          # Custom React hooks
│── lib/            # Utilities & helpers
│── public/         # Static assets
│── .env.local      # Environment variables
│── next.config.mjs # Next.js config
│── middleware.js   # Clerk auth middleware

---
🤝 Contributing
*Contributions are welcome!
1)Fork the repo
2)Create a new feature branch
3)Commit your changes
4)Push and open a Pull Request

---

###📜 License
This project is licensed under the MIT License – free to use, modify, and distribute.
