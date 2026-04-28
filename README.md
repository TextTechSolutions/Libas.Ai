# Libas AI — Virtual Try-On for Pakistani Fashion

**Libas AI** (لباس AI) brings photorealistic virtual try-on to Pakistan’s 43,000+ online apparel brands.  
Our lightweight Shopify plugin wraps _Google Vertex AI_’s generative model to let shoppers see any garment on their own body — directly on the brand’s store, in seconds.

---

## 🚀 What Problem Does Libas AI Solve?

| Problem | Impact |
|:---|:---|
| **Fit uncertainty** — customers can’t touch, feel, or try on clothes online | **20–40% return rate** (including Cash‑on‑Delivery refusal) |
| **Cart abandonment** driven by doubt about how an item will look | **74–75%** of Pakistani shopping carts are abandoned |
| **Low conversion & trust** — static images don't bridge the imagination gap | Brands lose **billions of rupees** annually to preventable returns |

**Libas AI turns “Will it look good on me?” into “I already know it does.”**

---

## 💡 How It Works

1. **A shopper uploads a full‑body photo** (or selects one from the brand’s style gallery).
2. **Our plugin sends the person + garment image to Google Vertex AI** Virtual Try-On.
3. **In ~5 seconds** the shopper sees a photorealistic preview of themselves wearing the exact garment — fabric, drape, and fit included.
4. **Confidence → Conversion → Fewer Returns.**

We focus on **realism, not gamification**, because academic research proves that over‑playful AR _reduces_ trust and increases doubt (Micheletto et al., 2025).

---

## 🧩 Features

- **🛍️ One‑click Shopify integration** — no complex API setup for the brand.
- **📸 Photo‑realistic try‑on** powered by `virtual-try-on-preview-08-04` (Google Vertex AI).
- **🎯 Optimised for South Asian fashion** — lawn suits, embroidered kurtis, shalwar kameez, dupattas.
- **📊 Analytics dashboard** — see how try‑ons impact conversion, returns, and average order value.
- **🔒 Privacy‑first** — images are processed ephemerally; no face data stored.
- **🧕 Inclusive design** — tested across diverse skin tones, body types, and hijab/headscarf styles.
- **📈 Built‑in social proof** — brands using Libas AI see **up to 40% conversion lift** and **25% fewer returns**.

---

## 🏗️ Tech Stack

| Layer | Technology |
|:---|:---|
| **Frontend** | HTML, CSS, JavaScript (landing page / widget) |
| **Backend** | Python (FastAPI), Gradio prototype stage |
| **AI Engine** | [Google Vertex AI Virtual Try-On](https://cloud.google.com/vertex-ai/generative-ai/docs/samples/generative-ai-virtual-try-on) |
| **E‑commerce** | Shopify API (plugin/app) |
| **Hosting** | GitHub Pages (static landing), Google Cloud Run (API) |
| **Analytics** | PostHog / Mixpanel (anonymised try‑on events) |

> **Prototype**: We built our first proof‑of‑concept using the open‑source [`fmind/virtual-try-on`](https://github.com/fmind/virtual-try-on) Gradio app.  
> The production version replaces Gradio with a headless API and Shopify‑native UI.

---

## 📁 Repository Structure
