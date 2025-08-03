# UX Funnel Analysis Dashboard (Power BI)

## 📘 Project Overview
This dashboard analyzes a 5-stage digital banking funnel to uncover key behavioral drop-offs and evaluate recovery opportunities. Using Power BI, it combines interactive visualizations, simulated recovery modeling, and KPI tracking to help product and UX teams pinpoint where users are disengaging — and project the impact of regaining them.

The funnel stages analyzed include:
**Landing → Sign Up → KYC → Link Account → Transaction**

---

## 📊 Key Features

- **Funnel Drop-Off Analysis**  
  Visualizes user count and percentage drop-offs at each stage.  
  > 📉 *Largest drop: Link → Transaction (52.05%)*

- **Recovery Rate Simulation**  
  Interactive slider allows users to simulate recovery of a portion of lost users.  
  > 📈 *Recovered users and projected transactions adjust dynamically.*

- **Funnel Completion Rate**  
  Gauge visual shows the % of users completing the full journey.  
  > *Current: ~19.9%*

- **First Significant Drop Indicator (FSDI)**  
  Flags the earliest funnel stage where drop-off exceeds 20%, helping prioritize UX interventions.

- **Segment Filters**  
  Analyze drop-offs by **device type** (mobile/desktop) and **visit day** (weekday/weekend)

---

## 📌 Core Metrics & Interpretations

| Metric                        | Value      | Interpretation |
|------------------------------|------------|----------------|
| Funnel Completion Rate       | 19.9%      | Only ~1 in 5 users reach the final step (Transaction) |
| Largest Drop-Off             | 52.05%     | Users abandon most between **Link** and **Transaction** |
| First Significant Drop       | Sign Up → KYC | Indicates early onboarding friction |
| Simulated Recovered Users    | 10–22      | Varies with slider; shows how many users might convert if recovered |
| Projected Transactions       | Up to 221  | Combines current completions + recovered users |
| Estimated Revenue (Optional) | ₹551,500+  | Based on recovered users × ₹2500 per transaction |

---

## 💡 Key Takeaways

- **Transaction stage is a major bottleneck**: Over half of users who link their accounts abandon before transacting. Likely due to UX friction or trust barriers.
  
- **Mid-funnel friction begins early**: The FSDI flags a 24% drop between Sign Up → KYC, pointing to onboarding fatigue or documentation hesitations.

- **Mobile users convert less efficiently**: Mobile device filters reveal steeper drop-offs, especially post-KYC. This suggests a need for mobile-first design improvements.

- **Recovery modeling quantifies opportunity**: Even modest recovery (e.g., 10%) boosts projected completions and revenue significantly, demonstrating the business case for UX investment.

---

## 📂 Repository Contents

- `UX_Funnel_Analysis.pbix`: Main Power BI dashboard file  
- `UX_Funnel_Overview.pdf`: Static exported view of the dashboard  
- `visuals/`: Screenshots of key charts and metrics  
- `README.md`: Project summary, interpretation, and insights

---

## 📸 Sample Visuals

*Funnel Drop-Off Breakdown by Stage*

![Funnel Chart](visuals/funnel_chart.png)

*Recovery Simulation Slider with Projected Transactions*

![Recovery Simulation](visuals/recovery_slider.png)

---



