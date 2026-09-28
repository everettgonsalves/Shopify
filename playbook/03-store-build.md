# 03: Store Build, Step by Step

Target: a store ready to take real orders by **about Oct 8, 2026**. Keep it simple. One hero product converts better than a big catalog, and every extra app slows the site.

---

## Step 0: Business basics (Day 1, about 1 hour)

- [ ] **Separate bank account and card** for the store. Get a high-limit card for Meta ad billing.
- [ ] **Business entity.** Selling as a sole proprietor is legal to start. An LLC adds liability protection. Ask an accountant; don't let this block launch.
- [ ] **EIN** (free at irs.gov) if you form an LLC, or if you want to avoid giving your SSN to vendors.
- [ ] **Bookkeeping.** At minimum, a spreadsheet of daily revenue, ad spend, print costs, and fees. File 05 has the columns.

## Step 1: Brand (Day 1–2)

**Name: SnootHug** (researched in [07-brand-and-offers.md](07-brand-and-offers.md)). The ideas first listed here were replaced: three of them already had their .com taken.

- [ ] Search the USPTO trademark database for conflicts (details in file 07).
- [ ] Buy `snoothug.com` in **your existing store**: Settings → Domains → Buy new domain. It was available for $16/yr on Sep 28.
- [ ] Check that `@snoothug` is free on TikTok and Instagram.

**Visual identity.**

- Wordmark logo: a clean serif or rounded sans. Canva is fine.
- 2 brand colors plus neutrals, e.g. warm cream and one deep accent.
- One font pair.
- Don't spend more than half a day on this. It won't be what makes or breaks you.

## Step 2: Shopify core settings

**Plan.** Basic is enough to start. Upgrade only when the lower card rates on a higher plan save more than the price difference.

**Settings → Store details**
- [ ] Legal business name, address, and support email on your domain (e.g. `help@yourbrand.com`).

**Settings → Payments**
- [ ] Turn on **Shopify Payments** and complete business verification fully. Incomplete verification is a common cause of payout holds.
- [ ] Turn on Shop Pay, Apple Pay, Google Pay, and PayPal.
- [ ] Set the **card statement descriptor to your brand name**. This prevents "I don't recognize this charge" chargebacks.

**Settings → Checkout**
- [ ] Customer contact: email or phone.
- [ ] Marketing opt-in checkbox shown and **not pre-checked**.
- [ ] Order status page: add a "What happens next" note covering proof, printing, and shipping.

**Settings → Shipping**
- [ ] One profile, **Free shipping** for the US.
- [ ] Optional: a paid "Priority" rate if your print provider offers express during December.
- [ ] US only at launch (Settings → Markets). Add Canada later only after checking duties and shipping from your provider.

**Settings → Taxes**
- [ ] Turn on Shopify Tax and collect in your home state.
- [ ] Watch economic-nexus thresholds in other states (often $100k in sales per state).
- [ ] Some print providers handle certain state tax setups. Confirm with an accountant.

**Settings → Domains**
- [ ] Connect your domain and set it as primary.

**Settings → Notifications**
- [ ] Brand the order confirmation and shipping emails.
- [ ] Add the production timeline to the order confirmation (copy in file 06).

## Step 3: Theme

- Use a **free Shopify theme** (Horizon or Dawn family). They're fast, mobile-first, and have no license cost.
- Homepage structure, built mobile-first (80%+ of your ad traffic will be on phones):
  1. **Hero:** a lifestyle image or video of a pet on its own custom blanket. Headline, "Create yours" button, and a short line under the button with the Christmas order-by date. Only show the date once your provider confirms it.
  2. **How it works:** Upload photo → Pick your style → We print and ship in X days.
  3. **Product tiles:** Blanket (hero), Canvas, Ornament, Memorial.
  4. **Review wall:** only real reviews and customer photos. Leave it out until you have them.
  5. **Guarantee block** (text in file 06).
  6. **FAQ.**
  7. **Email capture** (can also be a popup).
- Remove anything you don't need: blog, extra menus, and "Featured collection" filler.

## Step 4: Apps (keep it to 6–8)

| Job | App | Notes |
|-----|-----|-------|
| Printing and fulfillment | **Printify** (or Printful / CustomCat) | Choose a **US print provider** per product, based on your physical samples. |
| Photo upload, AI styling, live preview | **Teeinblue** (from ~$19/mo, first 100 orders free) or **Customily** (~$49/mo + fees) | **Before you pay**, confirm it connects to your chosen print provider and sends print-ready files automatically. **Turn off styles with trademarked names** (Disney, Ghibli, and similar). |
| Reviews | Judge.me | Only collect reviews **from real buyers**. Never import reviews from AliExpress or elsewhere; see Legal below. |
| Email and SMS | Klaviyo (free to 250 contacts) | Flows are in file 04. Shopify Email is acceptable if you want fewer tools. |
| Meta pixel and Conversions API | Facebook & Instagram (by Meta) app | Turn on **maximum data sharing** (Conversions API) and verify your domain in Business Manager. |
| TikTok pixel | TikTok app | Even if you only post organically at first. |
| Google | Google & YouTube app | For Merchant Center and Shopping ads later. |
| Post-purchase survey | Any free-tier "How did you hear about us?" app | Your truth check when ad-platform numbers disagree. |

**Don't install:** countdown-timer apps with fake timers, "X people are viewing" fake-notification apps, or review importers. They erode trust and can break FTC rules.

## Step 5: The hero product page

This page matters more than anything else in the store. Build it in this order:

**Above the fold (mobile):**
1. Image gallery with 8–10 images:
   - Pet lying on its blanket
   - Person hugging the blanket
   - Texture close-up
   - Size reference with a person on a couch
   - Before and after: phone photo → portrait
   - Gift box or unwrapping moment
   - Style options grid
   - Canvas and ornament cross-sell
2. Title: **"Custom Pet Portrait Blanket"** with a subtitle like "Their face. Your couch. Forever."
3. Star rating, **only once you have real reviews**.
4. Price: $79.95 with "Free US shipping." **No fake compare-at price.**
5. **Personalizer:** upload photo → style (Watercolor / Line Art / Pop Art / Classic) → background color → pet name.
   - Show photo tips inline, like "Good light, face the camera, eyes visible," with a good and a bad example.
6. Add-on checkbox: "Add a matching ornament +$19.95."
7. **Delivery line:** "Printed in the USA · Ships in X business days · Order by [real date] for Christmas delivery."
8. Big "Add to cart" button.
9. Guarantee strip: "Love it or we'll reprint it free."

**Below the fold:**
10. How it works (3 steps with icons).
11. What it feels like: sherpa or fleece details, size, washing instructions.
12. "The perfect gift for…" (dog mom, cat dad, grandparent, new puppy, memorial).
13. FAQ (copy in file 06).
14. Reviews with photos.

**Speed and usability:**
- Compress images.
- Test on a real phone over cellular.
- The personalizer must be usable with one thumb.

## Step 6: Other pages

- [ ] **Canvas** product page (same structure).
- [ ] **Ornament** page (mainly for search and add-ons).
- [ ] **Memorial collection.** Same products with gentle copy and memorial wording like "Forever in our hearts" and name/dates. **No discount banners, no urgency** on these pages.
- [ ] **About.** Your real story: why you started this, your pet, a real photo. Don't invent a founder story.
- [ ] **FAQ.**
- [ ] **Contact.** Email plus a 24-hour reply promise.
- [ ] **Shipping & Holiday Deadlines**, updated when your provider publishes cutoffs (usually mid-October).
- [ ] **Order tracking page.**
- [ ] **Policies** (Settings → Policies): Refund / Reprint, Privacy, Terms of Service, Shipping. Draft wording is in file 06.

## Step 7: Tracking (don't skip; ads can't learn without it)

- [ ] Meta pixel and Conversions API through the Meta app.
- [ ] Test events in Events Manager: PageView, ViewContent, AddToCart, InitiateCheckout, Purchase.
- [ ] Verify your domain in Meta Business Manager.
- [ ] TikTok pixel installed.
- [ ] Google Analytics 4 connected (Shopify's Google & YouTube app).
- [ ] UTM naming convention: `utm_source=meta&utm_medium=paid&utm_campaign=<campaign>&utm_content=<ad-name>`.
- [ ] Post-purchase survey live.

## Step 8: Legal and compliance

- **Reviews (FTC Consumer Reviews and Testimonials Rule, in force since Oct 2024).**
  - No fake reviews.
  - No buying reviews.
  - No hiding negative reviews.
  - No review importing from other sellers.
  - Violations can bring civil penalties.
- **No fake urgency or fake reference prices.**
  - Countdown timers must reflect real deadlines.
  - "Compare at" prices must be genuine former prices (FTC pricing guides and state laws).
- **Intellectual property.**
  - No Disney, Pixar, Ghibli, Marvel, sports-team, or other trademarked or copyrighted styles and characters in products or ads.
  - Don't use competitors' photos.
- **Customer photos.** Your Terms should give you a license to use uploaded photos **to make the order**. Using a customer's pet photo **in ads** needs separate, explicit permission; ask in the review request.
- **SMS.** Needs express written consent (TCPA). Use Klaviyo's compliant opt-in forms. Honor STOP.
- **Email.** CAN-SPAM: unsubscribe link and physical address in every marketing email.
- **Accessibility.** Alt text on images, readable contrast, and a personalizer that works with larger text.

## Step 9: Pre-launch QA (the day before launch)

- [ ] Place a **real order** yourself (not a test-mode order), using your own pet photo. Check:
  - the confirmation email
  - that the order reaches the print provider automatically
  - the print file quality
  - the tracking email
- [ ] Place a test order on **iPhone Safari** and **Android Chrome**.
- [ ] Try uploading a blurry photo. Does the app warn you?
- [ ] Every page loads under ~3 seconds on cellular.
- [ ] Every link and button works: footer, policies, contact.
- [ ] Meta Events Manager shows the Purchase event from your real order.
- [ ] Klaviyo welcome flow fires when you sign up through the popup.
- [ ] Support email receives mail. Send a test from a different account.
- [ ] Remove the password page.
