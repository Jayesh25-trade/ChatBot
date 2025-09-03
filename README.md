# GlycoGuide — Diabetes Care Assistant

A clean, **ChatGPT-style** web app that helps users with diabetes self-management.  
GlycoGuide provides quick guidance on blood sugar targets, medications, diet, and exercise, and can analyze uploaded report images (via your own Supabase Edge Functions).

> **UI goals:** simple, focused, and mobile-friendly.  
> **Tech goals:** 100% client-side, easy to deploy on any static host.

---

##  Features

- **Chat interface** with typing indicator and message history (in-memory)
- **Quick Actions** panel (collapsible on mobile) for one-tap prompts
- **Report upload & analysis** (image → base64 → Supabase Function)
- **Keyboard UX**: press `Enter` to send
- **Responsive design**: works great on phones, tablets, and desktops
- **Zero build step**: plain HTML/CSS/JS (no bundlers required)

---

##  Screenshots

| Chat view | Quick Actions |
|---|---|
| <img width="1918" height="931" alt="image" src="https://github.com/user-attachments/assets/3fc67413-adf8-48d9-b227-35f4b8beffbd" />|
| <img width="1914" height="977" alt="image" src="https://github.com/user-attachments/assets/9b10f52c-fe9e-4342-9e21-d474c82f8139" />|

> Put PNG/JPGs in `/docs/` and reference them, e.g. `![Chat](/docs/chat.png)`.

---

## 🧱 Tech Stack

- **Frontend:** HTML5, CSS (custom), vanilla JavaScript
- **API layer:** Supabase Edge Functions (HTTP endpoints)
- **Hosting:** Any static host (Render, GitHub Pages, Netlify, Vercel, etc.)

---



