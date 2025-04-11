# ELISSA: Empowering Informed Choices for Menstrual Products 🌸

![Project Elissa](https://github.com/user-attachments/assets/e2af5a7d-f8b3-4b5c-b438-bfb6ec646583)


**ELISSA** is a data-driven platform that applies unsupervised learning and NLP to help users make better, more personalized choices about menstrual products. Built around the core pillars of **transparency**, **well-being**, and **sustainability**, ELISSA bridges the gap between consumer needs and product information.

---

## 🌍 Context & Problem

Despite the wide availability of menstrual hygiene products, the market suffers from:

- ❌ **Lack of transparency** about materials and health impacts
- 🌱 **Limited sustainability information**
- 🤯 **Information overload** without personalization
- 🧾 **4 million people** in France affected by period poverty in 2022 (vs 2M in 2021)
- 🌍 **13% of household waste** comes from menstrual protection
- 🇫🇷 France recently made products free for women under 25; other countries (Scotland, UK) have done the same, signaling market evolution.

These stats indicate a shift in consumer demand toward **affordable**, **sustainable**, and **personalized** menstrual solutions.

---

## 💡 The ELISSA Solution

ELISSA addresses these issues by:

- Scraping thousands of Amazon product reviews to uncover hidden user insights
- Using NLP and ABSA to detect sentiment around key features (comfort, composition, eco-friendliness, etc.)
- Allowing users to explore products through an MVP website tailored to their preferences

---

## 📊 Key Findings (from EDA and Survey)

### 📈 Market Trends

- **Top Used Products in France**: Tampons, single-use towels, menstrual cups, and panties
- **Growth in Sustainable Options**: Usage of menstrual panties, washable towels, and cups has steadily increased since 2015
- **Emerging Interest**: Over **48% of surveyed users** are actively looking for **environmentally friendly alternatives**

### 🗣️ User Preferences (from Survey)

Over 100 surveyed respondents emphasized:

| Category     | User Focus                                                                 |
|--------------|-----------------------------------------------------------------------------|
| 🌱 Environment | Sustainability, eco-friendly materials, waste reduction                    |
| ⚙️ Usability   | Comfort, absorption capacity, design, insertion method                     |
| 💸 Market     | Price sensitivity, brand loyalty, openness to new product types            |
| 🧬 Physiology | Safe composition, organic materials, unbleached cotton, allergen avoidance |

> 🔎 Insight: While 70% were satisfied with their current products, nearly half were **actively seeking more sustainable options**.

---

## 🔍 Technical Workflow

**Data Pipeline:**

1. **Data Collection**: Scraped Amazon product reviews for top menstrual products
2. **Exploratory Data Analysis (EDA)**: 
   - Sentiment trends over time
   - Keyword clustering and frequency
   - Product segmentation
3. **NLP Processing**:
   - Tokenization, lemmatization, and stopword removal
   - Word cloud and topic modeling
4. **Aspect-Based Sentiment Analysis (ABSA)**:
   - Identified key aspects (e.g., comfort, sustainability)
   - Mapped sentiment scores to aspects per product

---

## 🧠 Business Insights

- 💡 **Opportunity**: There is an unmet need for a **comparative product platform** that aligns with user values like eco-responsibility, affordability, and health.
- 🛍️ **Target Users**: Eco-conscious consumers, Gen Z/Millennials, and underserved demographics (e.g., low-income women, students)
- 🤝 **Value Proposition**:
  - Personalized suggestions based on real user feedback
  - Environment-focused product ranking
  - Transparent, data-driven recommendations

---

## 🛠️ Tech Stack

- **Languages**: Python
- **Libraries**: Pandas, Matplotlib, Seaborn, NLTK, spaCy
- **ML Techniques**: Topic modeling, ABSA
- **Web Hosting**: Vercel (for MVP)

---

## 🚀 Future Roadmap

- [ ] Enhance ABSA model accuracy (fine-tuning PyASBA)
- [ ] Collect data from additional platforms (blogs, Reddit, forums)
- [ ] Add user login, filtering options on website
- [ ] Implement a price-comparison engine
- [ ] Enable user-generated reviews & community support forum

---

## 🤝 Want to Contribute?

This was a personal project, but if you're interested in collaboration (e.g., frontend, UX, dataset contributions), feel free to open an issue or fork the repo. Let's grow ELISSA together 🌱
