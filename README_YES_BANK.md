
# 🏨 Hotel Booking Analysis - Exploratory Data Analysis (EDA)

This repository contains an exploratory data analysis (EDA) project on hotel bookings aimed at uncovering the key factors that influence booking confirmations and cancellations. The insights derived from this project can help improve hotel pricing strategies, customer targeting, and inventory management.

## 📌 Project Overview

- **Project Type:** Exploratory Data Analysis (EDA)
- **Contributor:** Nikhil Negi
- **Dataset Size:** ~119,000 records, 32 columns
- **Data Source:** [Hotel Bookings Dataset](https://www.sciencedirect.com/science/article/pii/S2352340918315191)  
- **GitHub Repository:** [Hotel Booking Project](https://github.com/Negi270804/Hotel-Booking-Project.git)

## 🎯 Business Objective

To assist hotel management in:
- Improving booking retention
- Reducing cancellation rates
- Enhancing customer segmentation
- Optimizing room pricing and inventory planning

---

## 🧾 Problem Statement

Analyze hotel booking data to identify patterns and correlations between booking features and cancellation behavior using visual storytelling and statistical summaries.

---

## 🔍 Key Steps Performed

1. **Data Cleaning:**
   - Removed duplicate rows (~31,994)
   - Handled missing values (e.g., `children`, `country`, `agent`, `company`)
   - Converted month names to numeric format

2. **Feature Engineering:**
   - Created `total_stay` feature by summing weekday and weekend stays

3. **Data Visualization:**
   - Pie Charts, Bar Graphs, Histograms, Box Plots, KDE Plots, Heatmaps, Pair Plots
   - Visual correlation analysis to identify key influencing features

---

## 📊 Insights Gained

- **Booking Status:** Most bookings are confirmed, but cancellations are significant and often tied to higher room prices.
- **Hotel Type:** City hotels face more cancellations compared to resort hotels.
- **Customer Loyalty:** Repeated guests are much less likely to cancel.
- **Market Segments:** Online and offline channels have the highest cancellation rates.
- **Room Type & ADR:** Room type A is most popular. Higher ADR values are linked to more cancellations.
- **Seasonality:** ADR is highest during mid-year (peak seasons).
- **Stay Duration:** Shorter stays have higher cancellation tendencies.

---

## 📈 Visualizations Included

- Pie Chart: Booking Confirmation vs Cancellation
- Bar Chart: Hotel Type vs Booking Status
- Histogram: Adults per Booking
- Countplot: Booking Status by Market Segment
- Boxplot: ADR vs Booking Status
- KDE Plot: ADR Distribution by Booking Status
- Line Chart: ADR Trend by Month
- Correlation Heatmap
- Pair Plot of Key Variables

---

## ✅ Tools & Technologies Used

- **Languages:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
- **Platform:** Google Colab

---

## 🧠 Business Recommendations

- Focus on loyalty programs to retain repeated guests.
- Adjust pricing strategies, especially for high-cancellation channels.
- Promote longer stays via discounts or bundled offers.
- Use market-specific strategies to target low-cancellation segments like corporate or aviation.

---

## 📂 Project Structure

```
Hotel-Booking-Project/
├── Hotel Bookings Dataset.xlsx
├── Hotel_Booking_EDA.ipynb
├── README.md
```

---

## 🤝 Acknowledgements

Special thanks to:
- **Winnovation** for providing industry guidance.
- **Abhisek Mishra** for sharing valuable knowledge on LinkedIn.

---

## 📬 Connect with Me

📧 **Nikhil Negi**  
🔗 [LinkedIn](https://www.linkedin.com/in/negi270804)  
📁 [GitHub](https://github.com/Negi270804)

---
