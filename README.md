# AIC Yumbisye Township — Church Website

## 📁 File Structure
```
/
├── index.html              ← Homepage
├── css/
│   └── style.css           ← Design system (all styles)
├── pages/
│   ├── about.html          ← About Us + Vision/Mission/Timeline
│   ├── ministries.html     ← All 9 ministries
│   ├── sermons.html        ← Sermon archive
│   ├── events.html         ← Events & announcements
│   ├── gallery.html        ← Masonry photo gallery
│   ├── youtube.html        ← YouTube channel embed
│   └── contact.html        ← Contact form + map
└── vercel.json             ← Vercel config
```

## 🚀 Deploy to Vercel (30 seconds)

### Option A – Drag & Drop
1. Go to https://vercel.com/new
2. Drag the entire project folder onto the page
3. Click **Deploy** — done!

### Option B – GitHub (best for ongoing updates)
1. Push folder to GitHub
2. Import at https://vercel.com/new
3. Every `git push` auto-deploys ✅

### Option C – CLI
```bash
npm i -g vercel
cd aic-yumbisye
vercel
```

---

## 📊 Analytics

### Vercel Analytics (already embedded)
The site already has `<script defer src="/_vercel/insights/script.js">` in every page.
Just go to your Vercel Dashboard → **Analytics** tab → click **Enable** (free).

### Google Analytics (optional, deeper data)
1. Create account at https://analytics.google.com
2. Get your `G-XXXXXXXXXX` Measurement ID
3. Add before `</head>` in every HTML file:
```html
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

---

## ✏️ Quick Customisations

| What | Search for |
|---|---|
| Pastor name | `Pastor James Mutua` |
| Phone | `+254 700 000 000` |
| Email | `info@aicyumbisye.org` |
| WhatsApp | `wa.me/254700000000` |
| YouTube ID | `UCGUDxsDWmpTShlr178S-XfQ` |
| Map location | `maps/embed?pb=` → replace iframe src |
| Sermon dates/titles | `pages/sermons.html` |
| Event dates | `pages/events.html` |
| Gallery photos | Replace Unsplash URLs with real photos |

## 🌐 Custom Domain
Vercel Dashboard → your project → **Settings** → **Domains** → Add your domain.
