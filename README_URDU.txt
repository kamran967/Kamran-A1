Kamran A1 V2 — Real AI Brain

Files:
- index.html = GitHub Pages mobile app
- manifest.json = install/PWA info
- worker.js = secure AI backend

اہم: OpenAI API key کو index.html میں نہ ڈالیں۔ worker.js کو Cloudflare Worker میں deploy کریں اور OPENAI_API_KEY کو Secret کے طور پر رکھیں۔ پھر Worker URL کو Kamran A1 میں ⚙️ Settings میں ڈالیں۔

Model: gpt-5.6-luna
Optional Worker variable: ALLOWED_ORIGIN = آپ کے GitHub Pages کا URL

Voice V1 کی طرح browser Speech Recognition پر چلتی ہے۔
