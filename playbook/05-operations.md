# 05: Operations, Numbers, and Routines

## 1. How an order flows

```
Customer uploads photo + picks style ──► Personalizer app makes the print file
        │
        ▼
Order placed in Shopify ──► (first 100 orders: YOU check the photo, 2 min each) ──► Sent to print provider
        │                                                                              │
        ▼                                                                              ▼
Klaviyo "What happens next" email                        Printed in the US (1–3 business days) ──► Tracking sent to Shopify
                                                                                                        │
                                                                                                        ▼
                                                               Shipped email ──► Delivered ──► Review request (+ photo-use permission)
```

- **Checking photos by hand at the start** catches blurry photos, cropped ears, the wrong pet, and typos in names. If a photo is bad, email the customer within 12 hours with a template (file 06) asking for a better one. This is much cheaper than a reprint and a bad review.
- **Setting in Printify or Printful:** hold orders for manual approval at first, then switch to auto-approve once your error rate is under about 2%.
- **Deadline:** send every order to production within 24 hours.

## 2. Customer service

| Situation | Response |
|-----------|----------|
| "Where's my order?" | Reply within 12h with the tracking link and the expected date. |
| Print defect or damage | Ask for a photo, then **reprint for free right away**. Don't argue over one blanket. |
| "It doesn't look like my dog" | Offer a re-style or re-crop and reprint. The personalizer's preview cuts these down a lot. |
| Customer wants a cancellation | Allowed until it's sent to production. After that, offer a re-style or credit. |
| Package delayed near Christmas | Email them proactively **before** they ask. Offer the printable gift reveal card. |

- **Reply-time goal:** under 12 hours, 7 days a week in Nov–Dec.
- Put a support email and phone or chat on the site. Shopify Inbox is free.

## 3. Preventing chargebacks and payout holds

- Card statement shows your brand name (Settings → Payments).
- Tracking numbers sync to every order automatically.
- Clear production-plus-shipping timelines shown before purchase, not only after.
- Answer disputes fast in Shopify with evidence: the order, the approved preview, tracking, delivery confirmation, and emails.
- Keep chargebacks **well under 1%** (Shopify's risk flag) and below Visa's 1.5% threshold (North America, since March 2026).
- If Shopify asks for documents during a volume spike, respond the same day with your fulfillment partner, invoices, and tracking. Fast, complete answers shorten holds.

## 4. Holiday deadlines

- Print providers publish holiday cutoffs **around mid-October**. Last year's priority cutoffs for blankets were about **Dec 12**.
- As soon as they're published:
  - Put them on the Shipping page, the product page delivery line, and a site banner.
  - Set **your** deadline **1–2 days before** the provider's to leave room for photo checks.
- After your cutoff:
  - Switch product page text to "Arrives in January · Includes a printable gift reveal card to give on Christmas Day."
  - Send the card automatically. It can be a simple PDF from the order confirmation or a Klaviyo email.

## 5. Your numbers

### Daily tracking sheet (5 minutes a day, same time)

| Date | Revenue | Orders | Avg order value | Meta spend | Google/TikTok spend | Total ad spend | MER (Revenue ÷ ad spend) | Cost per purchase (Meta) | Print costs | Fees | **Profit** | Sessions | Conversion % | Notes |
|------|---------|--------|-----------------|------------|---------------------|----------------|--------------------------|--------------------------|-------------|------|------------|----------|--------------|-------|

`Profit = Revenue − Print costs − Fees − Total ad spend − 3% reprint reserve`

### Targets

| Number | Break-even | Target | Great |
|--------|-----------:|-------:|------:|
| MER (all revenue ÷ all ad spend) | 2.2 | **3.0** | 4.0+ |
| Meta cost per purchase | $37 | **$32** | ≤ $25 |
| Store conversion rate | – | **2.0%** | 3%+ (top 20% of stores) |
| Avg order value | – | **$80** | $90+ |
| Email and SMS share of revenue (Nov–Dec) | – | **20%** | 30%+ |
| Reprint rate | – | **< 3%** | < 1.5% |
| Chargeback rate | – | **< 0.5%** | < 0.3% |

### When a number is off, check this first

- **Conversion below 1% but good ad click rate:** problem on the product page or at checkout. Test the page on your phone. Is the personalizer slow? Is the price or shipping a surprise? Are there no reviews yet?
- **Lots of add-to-carts but few purchases:** checkout friction or sticker shock. Check shipping display and payment options, and the abandoned-checkout flow.
- **Low click rate across all ads:** weak hooks. Film new concepts, not new text.
- **Good cost per purchase but low profit:** order value too low. Push the ornament add-on and bundle, or raise the price by $5–10 and test.

## 6. Weekly routine (Sunday, 60–90 minutes)

1. Fill in the week's totals: revenue, spend, MER, profit.
2. List the top 3 and bottom 3 ads. What do the top 3 have in common (hook, format, creator, angle)?
3. Plan **5–10 new creatives** for the week, mostly variations on the winning angle plus 1–2 new angles.
4. Read every customer email and review from the week. Copy phrases customers actually use into your ads and product page.
5. Check the reprint and chargeback rates.
6. Check cash: payout balance, next print-provider charges, next Meta charges.
7. Choose one thing to test on the site this week, e.g. a new hero image, a price test, or a new style option.

## 7. January decision

In the first week of January, answer these with numbers:

1. What were total profit and MER for Q4?
2. What was the cost per purchase in November versus October?
3. What share of revenue came from email, SMS, and organic?
4. Which angle made the most money: gift, memorial, or self-purchase?

- If Q4 made money **and** the memorial or self-purchase angles held a cost per purchase ≤ $37, build for:
  - Valentine's Day
  - Mother's Day ("dog mom," May 9, 2027)
  - memorials all year
  - more products: pillow, mug, framed print, pet ID tag
- If not, keep the store, list, and pixel data, and test the next product using the same process from file 01.
