# SubReceipt — Viral Subscription Receipt Generator 🧾

A 100% client-side, zero-server-cost web application built for global traffic and high-RPM Personal Finance monetization.

## ✨ Features Included
1. **🔗 Viral URL State Sync (`?c=USD&t=classic&n=ALEX&s=...`)**
   - Every change automatically updates the URL query parameters.
   - Clicking **Share Link** lets users share their exact receipt with friends on Reddit (`r/personalfinance`), X, or Discord.
2. **📊 Global Benchmark Comparison & "Kill-Switch" Simulator**
   - Real-time comparison against the US/Global average monthly subscription spend ($91/mo).
   - Unchecking any subscription in Step 2 activates the **Kill-Switch Banner**, showing instant yearly savings and 10-year S&P 500 compound value.
3. **🚀 Zero-Cost Hosting & Monetization Ready**
   - Built-in **Privacy Policy**, **Terms of Use**, and **Affiliate Disclosure** modals required for Google AdSense and finance affiliate approval.
   - JSON-LD `WebApplication` structured data and OpenGraph/Twitter meta tags.

---

## 🌐 How to Publish for Free ($0/month Server Cost)

### Option A: Cloudflare Pages (Recommended — Unlimited Bandwidth for Free)
1. Go to [Cloudflare Dashboard](https://dash.cloudflare.com/) → **Workers & Pages** → **Create** → **Pages**.
2. Choose **Upload assets** (Direct Upload) or connect your GitHub repository.
3. Drag and drop the `sub-receipt` folder (`index.html`, `robots.txt`, `_headers`).
4. Click **Deploy site** — your app is live worldwide on Cloudflare's edge network in 30 seconds!

### Option B: Vercel / Netlify Drop
1. Go to [app.netlify.com/drop](https://app.netlify.com/drop) or [vercel.com](https://vercel.com).
2. Drag and drop the `sub-receipt` folder to publish immediately.

---

## 💰 How to Plug In Your Ad & Affiliate Links
1. **Google AdSense:**
   - Paste your AdSense `<script async src="https://pagead2.googlesyndication.com/...">` tag inside `<head>` in `index.html`.
   - Replace the top `#affiliate-top` banner with your responsive display ad unit if desired.
2. **High-Paying Finance Affiliates (Impact.com / CJ Affiliate):**
   - Search `index.html` for `#rocket-money-affiliate-url`, `#privacy-card-affiliate-url`, and `#vpn-affiliate-url` and replace them with your affiliate tracking links.
