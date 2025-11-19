
<img src="https://github.com/user-attachments/assets/b36ffb09-538d-4ff5-a78e-a4e928536d80" width="800" /> 

# 🚀 Blocs – Real-Time Collaborative Whiteboard

**Blocs** is a real-time, collaborative whiteboard application built with **Next.js 14, Convex, Liveblocks,** and **Clerk.**
It allows teams to brainstorm, sketch, design, and collaborate visually — all inside a fast, fluid, and intuitive interface.

🔗 **Live Demo:** https://blocs-board.vercel.app/

📦 **GitHub Repo:** https://github.com/SherrinaR/Blocs

<br>


## ✨ Features

### 🛠️ Whiteboard Tools
- Create a whiteboard **from scratch**
- Add Rectangles, Ellipses, Text, and Sticky Notes
- Pencil drawing for freeform sketching
- Layer controls (bring forward / send backward)
- Color customization

### 🎯 Productivity Enhancements
- Undo & Redo
- Keyboard shortcuts
- Favoriting boards
- Smooth and intuitive UI with TailwindCSS + ShadcnUI

### 🤝 Real-Time Collaboration
- Designed for teams
- **Live user cursors,** presence indicators, and conflict-free editing
- Backed by **Liveblocks + Convex** for lightning-fast sync
- Persistent storage with Convex real-time database

### 🔐 Authentication & Teams
- Powered by **Clerk**
- User accounts, organizations, and invites
- Access control and secure permissions

<br>


## 🧱 Tech Stack
| Layer | Technology |
|---|---|
| Frontend | Next.js 14 (App Router) |
| Collaboration Engine | Liveblocks |
| Database | Convex (real-time, reactive) | 
| Auth & User Mgmt | Clerk | 
| Styling | TailwindCSS, ShadcnUI | 
| Deployment | Vercel | 
	
<br>
<!--
📸 Screenshots
(Add screenshots here once available — UI, whiteboard tools, multiplayer view, etc.)
-->
<br>

## 🚀 Getting Started
### 1. Clone the repository
```
git clone https://github.com/SherrinaR/Blocs.git
cd Blocs
```
### 2. Install dependencies
```
npm install
```
### 3. Set environment variables

Create a `.env.local` file with required keys:
```
NEXT_PUBLIC_CONVEX_URL=
NEXT_PUBLIC_LIVEBLOCKS_PUBLIC_KEY=
CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
```

<!-- 
(Add any additional variables needed by Convex or Clerk)
-->
### 4. Start the dev server
```
npm run dev
```

Your app will be available at:
```
http://localhost:3000
```
<br>


## 📁 Project Structure
```
app/
  board/[boardId]/
  api/
  _components/
convex/
public/
```

- app/ – Next.js routes & UI
- convex/ – Convex backend logic
- public/ – static assets
- components/ – reusable UI parts


<br>


## 🧪 Future Enhancements (Roadmap)

🧲 Snap-to-grid

📌 More shape types

🖼️ Image upload

🎥 Realtime board playback

📄 Export board (PNG / PDF)


<br>

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repo

2. Create a feature branch

3. Submit a pull request

<br>



## 📝 License

This project is licensed under the MIT License © 2025 [@SherrinaR](https://github.com/SherrinaR)

<br>


## ⭐ Support the Project

If you like Blocs, consider giving the repository a star ⭐ on GitHub — it helps others discover it!
	
	
 
	
