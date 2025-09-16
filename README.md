# Universo Radio – Chatbot (Vercel Serverless) v2 (CORS)

Esta versión agrega **CORS** para que puedas llamar al endpoint desde tu web (Hostinger) sin bloqueos del navegador.

**Endpoint:** `/api/chat`  
**POST JSON:** `{ "message": "texto" }`

---

## 🚀 Pasos de uso

1. Sube este proyecto a **Vercel** (drag & drop o conecta con GitHub).
2. En **Settings → Environment Variables** agrega:  
   - `OPENAI_API_KEY`
3. Haz **Deploy** y guarda la URL:  
   - `https://TU-APP.vercel.app/api/chat`
4. Cambia tu widget en la web para que haga `fetch` a esa URL.

---

¡Namasté ✨!
