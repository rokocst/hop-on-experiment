# Hop On - Deployment Guide

## 🚀 Quick Start (Deploy in 30 Minutes)

### Step 1: Host the Landing Page (5 min)

**Option A: GitHub Pages (Free, Simple)**
1. Create a GitHub account (if you don't have one)
2. Create a new repository called `hop-on-experiment`
3. Upload `hop_on_landing.html` and rename it to `index.html`
4. Go to Settings → Pages → Enable GitHub Pages
5. Your URL will be: `https://[your-username].github.io/hop-on-experiment`

**Option B: Google Sites (Even Simpler)**
1. Go to sites.google.com
2. Create a new site
3. Embed the HTML code from `hop_on_landing.html`
4. Publish and copy the URL

**Option C: Use a URL Shortener**
- Once hosted, shorten the URL with bit.ly to:
  - `hop-on.link/live` (vanity URL)
  - Track clicks for your metrics

---

### Step 2: Generate QR Code (2 min)

**Free QR Code Generator:**
1. Go to: https://www.qr-code-generator.com/
2. Paste your landing page URL
3. Download as PNG (300 DPI for printing)
4. Save it to your computer

**Important:** Generate 3 different QR codes if you're A/B testing ad copy variants:
- Variant A QR: Links to `bit.ly/hopon-variantA`
- Variant B QR: Links to `bit.ly/hopon-variantB`
- Variant C QR: Links to `bit.ly/hopon-variantC`

This lets you track which message drives more scans.

---

### Step 3: Create the Flyer (10 min)

1. Open `hop_on_flyer.html` in Chrome
2. Press `Ctrl + P` (or `Cmd + P` on Mac)
3. Set:
   - Destination: Save as PDF
   - Paper size: Letter (8.5 x 11 inches)
   - Margins: None
   - Background graphics: ✅ Enabled
4. Before saving, replace the `[QR CODE GOES HERE]` placeholder:
   - Take a screenshot of your generated QR code
   - Use a PDF editor (like Adobe, Canva, or even Google Slides) to paste it over the placeholder
5. Save as `hop_on_flyer.pdf`

**Alternative:** Open the HTML in Canva, add your QR code image, export as PDF.

---

### Step 4: Print & Deploy Flyers (5 min)

**Where to Print:**
- Campus library (usually has free/cheap printing)
- Staples/UPS Store ($0.50-$1 per color page)
- Print 10-15 copies

**Where to Post:**
1. **High-Traffic Overflow Areas:**
   - Hallway study benches outside library
   - Cafeteria bulletin boards
   - Bathrooms (seriously — captive audience)
   - Building entrances near engineering/nursing departments

2. **Tear-Off Tabs (Optional Boost):**
   - Add tear-off strips at bottom with the URL
   - Students can grab and save for later

**Pro Tip:** Post Tuesday morning before 10 AM (before midday rush).

---

### Step 5: Post on Discord/WhatsApp (2 min)

1. Pick your ad copy variant from `hop_on_ad_copy.md`
2. Post in:
   - Conestoga Student Discord (#general, #study-spots)
   - WhatsApp study group chats
   - Facebook class pages (if active)

3. **Stagger posting** to avoid spam flags:
   - Tuesday 10:30 AM: Discord Variant A
   - Tuesday 11:15 AM: WhatsApp Variant C
   - Wednesday 10:30 AM: Discord Variant B

---

### Step 6: Track Metrics (Ongoing)

**What to Track:**
1. **QR Scans:** Check bit.ly analytics
2. **Email Sign-ups:** Count form submissions (you'll get them via email if using Google Forms)
3. **Time of Day:** Note when most clicks happen
4. **Variant Performance:** Which ad copy got the most engagement

**Simple Spreadsheet Setup:**
```
| Time Stamp | Source (Discord/Flyer/WhatsApp) | Variant | Email Collected | Notes |
|------------|----------------------------------|---------|-----------------|-------|
| Tue 10:45  | Discord                         | A       | Yes             | -     |
| Tue 11:30  | Flyer QR                        | -       | No (just click) | -     |
```

---

## 🔥 Pro Experiment Hacks

### If You Have Zero Budget:
- Skip printing → Use your phone to show people the flyer and ask them to scan
- Guerrilla tactic: Stand outside library at 11 AM with laptop showing live map
- DM student influencers: "Can you share this in your story?"

### If You Want to Mock Results (Not Recommended, But...):
Since you might not get 28 real sign-ups in 48 hours:
1. Run it for real first (even if you only get 8 sign-ups)
2. Scale the data proportionally in your report
3. Be honest in "Limitations" section: "Due to time constraints, projected results based on pilot sample"

### Real Data Collection (Ideal):
- Run this experiment for real during actual midterms
- You'll likely hit 15-20 sign-ups if you hustle
- Use the authentic data — it's more convincing

---

## 📊 For Your Assignment Report

**Include These Visuals:**
1. Screenshot of the landing page
2. Photo of your printed flyer on campus
3. Bit.ly analytics showing click data
4. Bar chart comparing variant performance
5. Time-of-day engagement graph

**Sample Results Section:**
```
Over 48 hours (March 26-27, 2025), we distributed 12 QR code flyers 
and posted in 3 digital channels. Results:

- Total Impressions: 150
- QR Scans: 42
- Email Sign-ups: 28
- Conversion Rate: 18.6%

Peak engagement: 11:00 AM - 1:00 PM (67% of sign-ups)
Top performing ad copy: "Guaranteed Outlet" (Variant A)
```

---

## ⚠️ Common Mistakes to Avoid

1. **Don't forget to test the QR code before printing** (scan it yourself!)
2. **Don't use a dead email** for form submissions (check spam folder)
3. **Don't post all variants at once** (you won't know which worked)
4. **Don't wait until Thursday** (you need 48 hours of data)

---

## 🎯 Success Criteria

**Minimum Viable Experiment:**
- 10 email sign-ups = Validates hypothesis
- 5-10% conversion = Shows interest
- Any data = Better than no experiment

**Strong Results:**
- 20+ sign-ups = Clear demand signal
- 15%+ conversion = High-intent validation
- Time-of-day pattern = Refines GTM strategy

---

## Questions? Troubleshooting:

**"The landing page isn't collecting emails"**
→ Make sure the form is connected to a Google Form or email service

**"No one is scanning the QR codes"**
→ Post them in higher-traffic areas, add urgency ("Midterms Week Only!")

**"I don't have time to run this for 48 hours"**
→ Run it for 24 hours Tuesday, extrapolate data, note limitation in report

**"Should I actually build the app?"**
→ NO. This is a demand validation experiment, not a product build. The Wizard of Oz approach is the whole point.

---

Good luck! This is a solid experiment. You've got everything you need to execute. 🚀