# LSAT Coach (Next.js 14)

An MVP LSAT practice + mentor chat app. Includes:
- Original LR/RC drill items (no copyrighted content)
- Streaming mentor chat via OpenAI Responses API
- Optional web search relay (/api/search via Tavily)
- Preloaded Feb‑170 plan button in chat

## Quickstart

```bash
npm install
cp .env.example .env.local
# edit .env.local and set OPENAI_API_KEY (and TAVILY_API_KEY if using search)
npm run dev
```

Open http://localhost:3000

## Deploy

Push this repo to GitHub and import into Vercel. Add your env vars in Vercel Project Settings.
