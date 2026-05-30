# Kibaba · Private Investor Briefing
### Ndovu Wealth — Multi-Asset Special Fund

A self-contained HNW investor intake form and briefing registration page, designed for the **Kibaba Private Investor Briefing — Monday 1 June 2026**.

Live at: `https://yourusername.github.io/kibaba-briefing`

---

## Repository Structure

```
kibaba-briefing/
├── index.html      ← Main form (10-step HNW intake + registration)
├── style.css       ← All styles (Ndovu brand, layout, animations)
└── README.md       ← This file
```

---

## Setup in 3 Steps

### Step 1 — Activate email submissions (Web3Forms)

Submissions are handled by [Web3Forms](https://web3forms.com) — free, no backend required.

1. Visit **https://web3forms.com**
2. Enter your email address (`nwafubwa@ndovu.co`)
3. Copy the **Access Key** sent to your inbox
4. Open `index.html`, find this line (~line 990):
   ```js
   const W3F_KEY = 'YOUR_ACCESS_KEY_HERE';
   ```
5. Replace `YOUR_ACCESS_KEY_HERE` with your actual key
6. Save the file

> Every submission will then arrive in your inbox with the full investor profile, and the registrant will automatically receive a personalised confirmation email with session details.

---

### Step 2 — Upload to GitHub

1. Create a free account at **https://github.com**
2. Click **New Repository**
   - Name: `kibaba-briefing`
   - Visibility: **Public**
   - Click **Create repository**
3. Click **Add file → Upload files**
4. Drag and drop all three files:
   - `index.html`
   - `style.css`
   - `README.md`
5. Click **Commit changes**

---

### Step 3 — Enable GitHub Pages

1. Go to your repository → **Settings**
2. Scroll to **Pages** (left sidebar)
3. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
4. Click **Save**
5. Wait ~60 seconds, then visit:

```
https://yourusername.github.io/kibaba-briefing
```

---

## What the Form Does

| Step | Content |
|------|---------|
| 01 | Contact details (name, mobile, email, location) |
| 02 | Investor standing — with free-text "Other" |
| 03 | Current portfolio holdings — multi-select + "Other" |
| 04 | Live return calculator — capital input, top-ups (monthly/quarterly/annual), projections across all 5 strategies |
| 05 | Wealth Horizon — target wealth × target year → animated chart + 3-tab scenario analysis (time to goal / top-up needed / capital only) |
| 06 | Fund topics of interest — multi-select + "Other" |
| 07 | Investment readiness + capital range |
| 08 | Goals and risk disposition — with free-text "Other" |
| 09 | Session booking — pre-selected Monday 1 June, Mon–Fri calendar, 8 AM–6 PM time slots, virtual or in-person |
| 10 | Summary review → **Submit** → success screen with Google Calendar + .ics invite |

---

## On Submission

**You receive** (at `nwafubwa@ndovu.co`):
- Full investor profile: name, mobile, capital range, readiness, wealth target, session format, time, topics

**Registrant receives** (auto-reply from Web3Forms):
- Personalised confirmation with session date, time, format
- Ndovu investment portal link
- Advisor contact details

**Both parties get:**
- Google Calendar link (one-click)
- Downloadable `.ics` file (Apple Calendar / Outlook)

---

## Customisation

| What to change | Where |
|---|---|
| Your email address | Web3Forms dashboard |
| Advisor phone number | Search `+254 707 462 764` in `index.html` |
| Investment portal link | Search `6Q4ZC6A3` in `index.html` |
| Session date | Search `1 June 2026` in `index.html` |
| Fund return rates | Search `FUNDS_KES` / `FUNDS_USD` in `index.html` |

---

## Tech Stack

- **Pure HTML + CSS + Vanilla JS** — no frameworks, no build step, no dependencies
- **Web3Forms** — email submission + auto-reply (free tier: 250 submissions/month)
- **Google Fonts** — Cormorant Garamond + DM Sans (loaded via CDN)
- **GitHub Pages** — free static hosting

---

## Brand

- **Navy** `#071120` · **Blue** `#1A4A9A` · **Orange** `#E85C1A` · **White** `#FFFFFF`
- Typography: Cormorant Garamond (serif headings) + DM Sans (body)
- Hero image: embedded as base64 in `style.css` — no external image CDN required

---

## Contact

**Ndovu Wealth Limited** · CMA Regulated  
nwafubwa@ndovu.co · +254 707 462 764  
[portal.ndovu.co/auth/registration?code=6Q4ZC6A3](https://portal.ndovu.co/auth/registration?code=6Q4ZC6A3)

---

> *All projected returns shown in this form are target rates and are not guaranteed. Investment capital is at risk. The Kibaba Multi-Asset Special Fund is regulated by the Capital Markets Authority of Kenya (CMA). This form is for qualification and booking purposes only and does not constitute financial advice.*
