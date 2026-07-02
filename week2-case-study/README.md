# Case 2: Cracking Growth at Peppo: Segmenting for Scale

## I. Introduction: Peppo's Promise

In the heart of India’s buzzing foodtech scene, Peppo emerged in 2021 as a fresh alternative to the food delivery status quo. Unlike Swiggy and Zomato, Peppo didn’t just promise convenience — it promised an experience.

The product was simple: meal kits with pre-portioned ingredients, delivered in under 30 minutes, accompanied by step-by-step video guides. Targeted at urban millennials and Gen Z professionals, the brand aimed to make cooking feel joyful, effortless, and quick.

In its first two years, Peppo saw rapid adoption across Tier-1 cities like Bangalore, Mumbai, and Delhi. But by early 2024, growth began to plateau. Despite strong install numbers and marketing investments, retention beyond the second week of onboarding was falling.

Aditi Rao, the Product Manager responsible for user growth and retention, was tasked with finding out what was going wrong. Aditi believed the root problem was Peppo's poor understanding of its user base. The company had yet to implement any structured segmentation model. Instead, most growth decisions were based on anecdotal hunches and limited dashboards.

The CEO gave Aditi a clear mandate: *"Improve retention and LTV. Identify the high-value segments and double down."*

---

## II. The Problem Statement

Peppo faced three key business challenges:

* **High Drop-Offs After First Order**: $65\%$ of users never returned after their first order.
* **Expensive User Acquisition**: CAC (Customer Acquisition Cost) from paid channels had doubled in the last 3 quarters.
* **Low Lifetime Value (LTV)**: Most users made only 1–2 transactions. Very few became loyal, repeat customers.

Aditi needed to answer three critical questions:
1. Who are Peppo's highest-value users?
2. Why do they retain better than others?
3. What can we do to attract and retain more users like them?

To answer these, Aditi launched a data-driven segmentation and research strategy.

---

## III. Data Snapshot: What Aditi Knows

### 1. Demographics & Device
A dataset of 1,000 users is available with attributes such as city, age, gender, device type, platform (app/web), and first access date. The user base is predominantly:
* **Android Users**: $80\%$
* **Geography**: Tier-1 cities (Bangalore, Mumbai, Delhi, etc.)
* **Age Range**: Aged 20–44 (with Champions concentrated in the 25–34 cohort)

### 2. Acquisition Sources
* **Paid Channels**: Instagram and Google Ads are the largest traffic drivers. However, paid channels have seen a doubling of CAC, indicating they are acquiring lower-intent cohorts compared to organic/referral loops.
* **Organic/Referrals**: Accounts for a smaller volume but yields users with higher retention rates.

### 3. Behavioral Insights
The expanded behavioral dataset tracks:
* Last active date (Recency)
* Number of orders (Frequency)
* Total spend in INR (Monetization)
* Feature usage:
  - *Watched Video* (Key activation event)
  - *Saved Recipe* (Deep engagement indicator)

### 4. Loyalty Tier Program (Pilot)
A pilot loyalty tier program has been introduced to segment users based on transaction history and spend. Analysis shows:
* **Whales**: High-spend, low-engagement users who order for convenience but do not use interactive features (high churn risk).
* **Loyals**: High-spend, high-engagement users who utilize step-by-step videos and save recipes.

### 5. Survey Results
To complement behavioral and transactional data, Peppo surveyed 5,000 recent users (retained and churned) in Q1 2024. 

**Top-line findings (Friction Points & Motivations)**:
* `62%`: "Not enough recipe variety" (Primary product gap)
* `41%`: "Wanted to try something new" (Trial behavior)
* `31%`: "Too expensive" (Price sensitivity)
* `23%`: "Inspired by cooking videos" (Activation hook)
* `12%`: "Peer recommendation" (Viral loop)

---

## IV. Internal Perspectives

* **CEO**: *"We need to find our sticky users. It makes no sense to spend on everyone. Let’s focus our roadmap on the most valuable cohort."*
* **Growth Lead**: *"Instagram and Google Ads are expensive. Maybe discounting will help in early retention."*
* **Head of Ops**: *"Our logistics are better suited for family-size kits. Single-serve orders eat into margins."*
* **Aditi (PM)**: *"We’re building too broadly. We need to define our user personas, understand motivations, and validate with proper research."*

---

## V. Key Insights & Segmentation Analysis

Using the dataset of 1,000 users, we performed RFM and Behavioral analysis:

### 1. RFM (Recency, Frequency, Monetization) Segmentation
* **Champions & Loyal Users**: Together make up the top **one-third** of the user base. They are highly active, order frequently, and spend the most.
* **Lost Users**: Confirm the $65\%$ first-order drop-off issue. They have low frequency and high recency (dormant for a long time).

### 2. Behavioral "Aha Moment"
* Users who engage with **both video play AND recipe saving** have the highest order frequency and lifetime value.
* Watching the first step-by-step cooking video is Peppo's core **activation moment** (or "Aha!" moment).

---

## VI. Strategic Recommendations & Actions

Based on the analysis, Peppo should target two primary user segments:

### Priority 1: "Video-First Millennial" (Age 25–34, Android App, Engaged)
* **Who they are**: Tech-savvy young professionals using the Android app who watched at least one video. They represent the core of the Champions cohort.
* **Actions**:
  1. **Onboarding Experiment**: Gate the onboarding flow with a quick, engaging 30-second "watch and cook" video.
  2. **Save Prompt**: Prompt users to save the recipe immediately after video completion to build retention hooks.
  3. **Expand Variety**: Add $10-15$ new recipes weekly to address the $62\%$ "not enough variety" survey feedback.

### Priority 2: "Whales" (High Spend, Low Engagement)
* **Who they are**: Price-insensitive users with above-median spend who order meal kits but don't watch videos or save recipes. High risk of churning to food delivery apps.
* **Actions**:
  1. **Targeted Engagement**: Run push campaigns recommending recipes tailored to their purchase history.
  2. **Loyalty Program**: Auto-enroll them in the premium loyalty tier to increase switching costs.
  3. **Qualitative Research**: Conduct interviews with 10 Whales to understand their friction with interactive features.

---

### What to Deprioritize (Ruthless Focus)

| Decision | Rationale |
| :--- | :--- |
| **No Tier-2 Expansion** | Retention in Tier-1 is unsolved. Expanding to Tier-2 now will compound the drop-off issues at higher CAC. |
| **No Blanket Discounts** | Discounts attract price-sensitive, low-intent users, worsening LTV/CAC ratios. |
| **Retain Single-Serve Kits** | We must verify if single-serve kits feed the "Video-First Millennial" (single/young couple) cohort before cutting them. |

---

### Recommended Experiments

| Experiment | Hypothesis | Primary Metric |
| :--- | :--- | :--- |
| **Onboarding Video Gate** | Forcing/guiding a first video view increases activation and retention | 30-day Retention Rate |
| **Post-Video Save Prompt** | Prompting to save a recipe increases repeat orders | Reorder Rate ($2^{\text{nd}}$ order %) |
| **Recipe Catalog Expansion** | Offering more recipe variety reduces churn | Monthly Active Users (MAU) |
| **Family-Kit Pricing Test** | Price-insensitive Whales will absorb higher prices for family-size options | Gross Margin per Order |

---

## Appendix: Survey Questionnaire

### Peppo User Survey (2024 Edition)

1. **How often do you cook meals at home in a typical week?**
   - 0 times
   - 1–2 times
   - 3–4 times
   - 5+ times

2. **What motivated you to try Peppo?**
   - Save time cooking
   - Try something new
   - Learn to cook better
   - Inspired by video content
   - Peer recommendation

3. **What prevented you from reordering after your first experience?**
   - Limited recipe options
   - Price too high
   - Complicated cooking steps
   - Delivery issues
   - Other (please specify)

4. **How satisfied were you with the overall product experience?**
   - Very satisfied
   - Somewhat satisfied
   - Neutral
   - Somewhat dissatisfied
   - Very dissatisfied

5. **Which of the following features did you use?**
   - Step-by-step video walkthrough
   - Saved a recipe
   - Shared your experience with others
   - Redeemed an offer/coupon

6. **Would you recommend Peppo to a friend or colleague?**
   - Yes
   - No