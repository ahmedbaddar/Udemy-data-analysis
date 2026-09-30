# 📊 Udemy Courses Performance Analysis & Business Strategy

A comprehensive data-driven analysis of the **Udemy Courses Dataset**, evaluating course enrollments, pricing strategies, content duration, and social proof dynamics to identify high-performing **"Star Products"** and inform marketing and content acquisition decisions.

---

## 📌 Executive Summary

This project analyzes historical performance data from Udemy courses across multiple categories (such as Web Development, Business Finance, Graphic Design, and Musical Instruments) to discover key revenue drivers and student conversion catalysts. By examining parameters like subscriber counts, pricing tiers, review volumes, and course duration, the analysis translates quantitative insights into actionable business strategies for maximizing **Return on Ad Spend (ROAS)** and driving instructor supply expansion.

---

## 🔑 Key Findings & Dataset Insights

1. **Top-of-Funnel vs. Premium Conversion:**
   * Free courses serve as a high-volume lead magnet to attract initial traffic to the Udemy platform.
   * Premium-priced, comprehensive "Bootcamps" ($150–$200) in high-demand domains like Web Development drive top-tier revenue and high overall enrollment counts.

2. **Duration & Content Structure:**
   * Course duration is **not a linear predictor** of subscriber counts. 
   * While average courses range between 1.5 and 15 hours, top-performing **"Star Products"** feature longer formats ranging from **20 to 43 hours**. Paying learners prioritize thorough, end-to-end subject coverage over brevity.

3. **Social Proof as the Primary Conversion Catalyst:**
   * A strong positive correlation exists between review volume (`num_reviews`) and total enrollments (`num_subscribers`). High review counts lower price sensitivity and serve as the main catalyst for paid conversion.

4. **Audience Segmentation:**
   * Over **90% of total paid enrollments** belong to **"All Levels"** (5.24M subscribers) and **"Beginner Level"** (2.31M subscribers). Intermediate and Expert tiers represent niche market segments.

---

## 🎯 Strategic Action Plan

### 1. Targeted Marketing & Ad Spend Allocation (Top 10 Star Products)
Allocate performance marketing budgets toward established, high-performing Udemy courses with proven Social Proof to maximize ROAS and lower Customer Acquisition Costs (CAC):

1. **The Web Developer Bootcamp** (*Web Development* | 27,445 Reviews | 121,584 Subscribers)
2. **The Complete Web Developer Course 2.0** (*Web Development* | 22,412 Reviews | 114,512 Subscribers)
3. **Angular 4 (formerly Angular 2) - The Complete Guide** (*Web Development* | 19,649 Reviews | 73,783 Subscribers)
4. **JavaScript: Understanding the Weird Parts** (*Web Development* | 16,976 Reviews | 79,612 Subscribers)
5. **Modern React with Redux** (*Web Development* | 15,117 Reviews | 50,815 Subscribers)
6. **Learn and Understand AngularJS** (*Web Development* | 11,580 Reviews | 59,361 Subscribers)
7. **Learn and Understand NodeJS** (*Web Development* | 11,123 Reviews | 58,208 Subscribers)
8. **Angular 2 with TypeScript for Beginners: The Pragmatic Guide** (*Web Development* | 8,341 Reviews | 40,070 Subscribers)
9. **Pianoforall - Incredible New Way To Learn Piano & Keyboard** (*Musical Instruments* | 7,676 Reviews | 75,499 Subscribers)
10. **Build Responsive Real World Websites with HTML5 and CSS3** (*Web Development* | 7,106 Reviews | 43,977 Subscribers)

### 2. Content Acquisition & Supply Expansion
* **Focus on "Zero-to-Hero" Bootcamps:** Prioritize instructor acquisition efforts toward comprehensive, all-inclusive curricula targeted at "Beginner" and "All Levels" entry points.
* **Incentivized Feedback Loops:** Encourage instructors to implement post-course evaluations and offer ethical incentives (e.g., coupons for future courses) to rapidly build Social Proof.
* **Promotional Pricing Tactics:** Leverage limited-time discounts on premium-listed courses ($150–$200) to create purchase urgency while maintaining platform and course credibility.

---

## 🛠️ Project Structure & Tech Stack

* **Language:** Python 3.x
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `plotly`, `matplotlib`, `seaborn`
* **Static Export:** `kaleido`

