# SkinLedger 🧴📊

> **An Explainable AI Platform for Personalized Skin Intelligence and Beauty Finance Analytics**  
> *A unified decision-support platform integrating dermatological image analysis, automated shelf inventory management, and cosmetic financial accountability.*

---

## 📋 Executive Summary

**SkinLedger** is an end-to-end decision-support platform designed to solve the structural disconnect between skincare purchasing habits, product efficacy, and personal finance[cite: 1, 3, 5]. Consumer research indicates that individuals across diverse age groups and spending levels frequently purchase cosmetics based on social media trends rather than verified skin compatibility or existing inventory[cite: 1, 3, 6, 7]. This pattern leads to three major compounding issues:

1. **Mismatched Purchases:** Irritation, breakouts, and financial loss caused by products unsuitable for the user's specific skin profile[cite: 1, 6].
2. **Duplicate & Idle Stock:** Accumulation of near-identical products with overlapping active ingredients, leading to product expiration and shelf wastage[cite: 1, 6].
3. **Invisible Spend-to-Outcome Mapping:** Lack of quantitative feedback connecting cumulative cosmetic expenditure to visible skin health improvements[cite: 1, 6].

SkinLedger bridges this gap by combining computer vision, explainable AI (XAI), content-based recommendation logic, and personal finance analytics into a single consolidated framework[cite: 1, 3, 5, 22].

---

## ⚙️ Core System Modules

SkinLedger is architected into **five interconnected core modules**[cite: 3, 5]:

* **🔍 Skin Intelligence (Explainable AI):** Performs computer-vision-based facial image processing with confidence-scored outputs[cite: 1, 3, 18, 19]. In the Phase I baseline, it utilizes HTML5 Canvas pixel sampling (RGB, Brightness, Saturation rules)[cite: 20, 29]; in planned production, it incorporates a fine-tuned CNN classifier paired with **Grad-CAM** heatmaps to surface the exact visual regions driving predictions.
* **📸 AI Vanity Audit:** Provides product tracking by logging purchase dates, category tags, and usage events[cite: 1, 3, 25, 27]. Automatically identifies duplicate category purchases, flags expired products, and isolates idle stock (items unlogged for 30+ consecutive days)[cite: 1, 3, 21, 25, 27].
* **💰 Beauty Finance Analytics:** Evaluates spending efficiency using key unit-economics indicators including **Cost Per Use**, **Beauty ROI**, **Cost Per % Improvement**, and cumulative duplicate loss[cite: 1, 3, 21, 25, 27].
* **🎯 Recommendation Engine:** Employs content-based filtering to suggest suitable, budget-compliant products tailored to the user's skin profile while cross-checking existing inventory to prevent redundant spending[cite: 1, 3, 21, 22].
* **📈 Integrated Dashboard & SkinLedger Score:** Visualizes skin progress timelines, routine consistency, financial metrics, and a single weighted composite score[cite: 1, 3, 22, 23, 26].

---

## 📐 Mathematical Models & Composite Metrics

### 1. Beauty Finance Metrics

To establish financial accountability, SkinLedger calculates the following quantitative indicators[cite: 3, 21]:

* **Cost Per Use:**
  $$\text{Cost Per Use} = \frac{\text{Purchase Price}}{\text{Total Logged Uses}}$$

* **Beauty ROI (Return on Investment):**
  $$\text{Beauty ROI} = \frac{\text{Skin Improvement } \%}{\text{Purchase Price}} \times 1000$$

* **Cost Per % Skin Improvement:**
  $$\text{Cost Per } \% \text{ Improvement} = \frac{\text{Purchase Price}}{\text{Skin Improvement } \%}$$

### 2. The Composite SkinLedger Score

The **SkinLedger Score** is a weighted composite index evaluating four essential dimensions of personal care management[cite: 1, 3, 22]:

$$\text{SkinLedger Score} = (0.40 \times \text{Skin Health}) + (0.20 \times \text{Routine Consistency}) + (0.20 \times \text{Budget Efficiency}) + (0.20 \times \text{Product Suitability})$$

| Component | Weight | Analytical Focus |
| :--- | :---: | :--- |
| **Skin Health** | **40%** | Predicted skin-condition suitability score and visual analysis confidence[cite: 1, 3, 22]. |
| **Routine Consistency** | **20%** | Logged frequency of application against recommended routine structures[cite: 1, 3, 22]. |
| **Budget Efficiency** | **20%** | Cost-per-use and Beauty ROI measured against category benchmarks[cite: 1, 3, 22]. |
| **Product Suitability** | **20%** | Ingredient-to-skin match score subject to duplicate and conflict penalties[cite: 1, 3, 22]. |

---


