<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=26&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=600&lines=Ishpreet+Singh+Bhatia;Building+RAG+pipelines+%26+distributed+systems;CSE+%40+Chitkara+University" alt="Typing SVG" />

</div>

<br>

I'm a CS undergrad (Class of 2028) who ships full products, not just repos — front end, back end, infra, and the AI layer in between. Right now that means running a live multi-tenant SaaS in production and co-authoring a deepfake-detection paper on the side.

Not "learning full stack" — I've deployed it: a FastAPI service on EC2 talking to a vector DB, fronted by a React app on Vercel, with real users and a real production bug I had to chase down at 2 a.m.

<br>

### What I'm building

**[EmbedAI](https://embedai.page)** — turn any website into an embeddable AI chatbot. Businesses paste a URL; a 5-stage async pipeline (Playwright → BeautifulSoup → FastAPI workers → local embeddings → per-tenant Qdrant storage) ingests the site, and a zero-dependency JS widget serves streamed Groq/Llama-3.3 answers with a hybrid retrieval layer (semantic search + score thresholds + site summaries). Found and fixed a production concurrency bug where synchronous Supabase auth calls were blocking FastAPI's event loop.

**GeoAuth** — attendance verification for universities that's actually hard to cheat: DigiPIN grid-based geofencing, biometric facial verification, device fingerprinting, and time-rotating QR codes, with a concurrency-safe WebSocket layer keeping state in sync across simultaneous sessions.

### Research

Co-authoring a paper on **deepfake detection** — a hybrid pipeline pairing classical forensic features (LBP, GLCM, HOG, Markov) with deep embeddings (EfficientNet-B0), feeding SVM/XGBoost classifiers. 87–89% accuracy across 7,000+ images.

<br>

### Stack

```
Languages     C++ · Python · TypeScript · Java
Frontend      React · Vite · Tailwind · TanStack Query
Backend       FastAPI · Node.js · Express · REST + streaming APIs
Data          Supabase · Qdrant · MySQL · MongoDB
AI/ML         PyTorch · sentence-transformers · LangChain · Groq API
Infra         Docker · EC2 · Vercel · Linux
```

<br>

<div align="center">

<img height="165em" src="https://github-readme-stats.vercel.app/api?username=ishpreet-02&show_icons=true&theme=tokyonight&hide_border=true&hide_title=true&count_private=true"/>
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ishpreet-02&layout=compact&theme=tokyonight&hide_border=true&hide_title=true&langs_count=8"/>

</div>

<br>

### Solved 300+

Working through the Striver A2Z DSA sheet — 300+ problems across arrays, trees, graphs, and DP. Core CS: OS, Networks, DBMS, OOP.

<br>

<div align="center">

📫 <a href="mailto:ishpreet1247.becse24@chitkara.edu.in">Email</a> · 
<a href="https://linkedin.com/in/ishpreet-singh-bhatia">LinkedIn</a> · 
<a href="https://github.com/ishpreet-02">GitHub</a>

</div>
