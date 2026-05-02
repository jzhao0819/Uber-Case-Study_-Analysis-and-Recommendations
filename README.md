# Uber Case Study: Analysis and Recommendations

## Project Background
This project aims to optimize the user experience and maximize customer retention by analyzing Uber's operational data. By identifying key service attributes and pin-pointing friction points, we provide actionable strategies to improve customer satisfaction.

### Objectives
* Pinpoint and prioritize key sources of user friction and dissatisfaction.
* Optimize the overall user experience.
* Maximize customer satisfaction and loyalty.
* Increase customer retention across all user segments.

---

## Methodology
The project leverages two datasets from Kaggle: "Uber Customer Reviews (2024)" and "My Uber Drives (2016)".

### Clustering Process
1.  **Preprocessing**: Cleaned review text (lowercasing, removing punctuation & stopwords).
2.  **Feature Construction**: Transformed text using TF-IDF and integrated standardized ratings.
3.  **Clustering**: Applied K-Means algorithm (K=4).
4.  **Visualization & Interpretation**: PCA dimensionality reduction for visualization, complemented by Word Clouds and average score analysis.

---

## Cluster Profiles

| Cluster | User Type | Avg Score | Top Keywords |
| :--- | :--- | :--- | :--- |
| **C0** | Stable Users | 4.90 | ride, driver, nice, fast |
| **C1** | Silent Positives | 4.84 | good, service, experience, app |
| **C2** | Dissatisfied Complainers | 1.27 | charged, cancel, wait, refund |
| **C3** | Loyal Advocates | 4.96 | excellent, friendly, reliable |

---

## Strategic Recommendations

Based on our clustering analysis, we recommend the following tailored strategies:

* **Stable Users (C0)**: Maintain service consistency and launch a "Refer-a-Friend" program to drive organic growth.
* **Silent Positives (C1)**: Utilize in-app feedback prompts to uncover hidden dissatisfaction and invite users to participate in beta testing.
* **Dissatisfied Complainers (C2)**: Prioritize issue resolution regarding charge errors, driver behavior, and app crashes. Implement structured refund programs and targeted apology/compensation offers.
* **Loyal Advocates (C3)**: Provide VIP perks (e.g., early feature access) and feature these users in campaigns to encourage social sharing and positive reviews.

---

## Team
Liyu Tenaw, Patrick Bardsley, Ronni Lilly, Sahar Maleki, Jin Zhao
