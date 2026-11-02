# TCO Route Lab (Vercel)

Static site: `public/index.html` (no build step).

## Deploy
1. Upload this folder to a GitHub repo, then Vercel > Add New > Project > Import. Framework: Other. Deploy.
   Or in a terminal: `npm i -g vercel && vercel --prod`
2. Open the resulting https://....vercel.app address.
3. In the site, open QR & SHARE: the QR now uses that real address. "Quiz QR" opens the quiz directly (#quiz).

Local preview: `npx serve public`

## Mini app
- **Installable (PWA):** open the site in Chrome/Safari > "Add to Home Screen". Works offline for the UI (map tiles need internet).
- **Telegram Mini App:** in @BotFather: /newbot (or use yours) > /newapp > choose the bot > give the https://....vercel.app URL. Share the link `https://t.me/<bot>/<app>`; add `?startapp=quiz` to open the quiz directly (or `?startapp=strategy`).
