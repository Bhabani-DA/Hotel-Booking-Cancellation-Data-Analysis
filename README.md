# 🏨 Hotel Booking Cancellation Analysis

## 📌 Project Overview
This project analyzes hotel booking data from City and Resort Hotels to identify key factors influencing booking cancellations. With rising cancellation rates impacting revenue and occupancy, this analysis aims to deliver actionable business insights to reduce cancellations and improve operational efficiency.

---

## 🧠 Business Problem
In recent years, **City Hotel** and **Resort Hotel** have seen **high cancellation rates**, leading to revenue loss and underutilized room inventory. The goal is to explore and analyze cancellation patterns and contributing variables to provide data-driven recommendations for reducing cancellations.

---

## 📊 Assumptions
- No significant events from **2015–2017** have skewed the dataset.
- The dataset is representative of typical hotel operations and client behavior.
- Hotels are **not currently using** any cancellation-reduction techniques.
- Booking cancellations directly correlate to **lost revenue** and room-night wastage.
- All cancellations occurred in the same year as the booking.
- The hotel will not suffer adverse effects from the strategies suggested.

---

## ❓ Research Questions
1. What are the key factors influencing hotel booking cancellations?
2. How can we minimize hotel reservation cancellations?
3. How can pricing and promotional strategies be optimized using this data?

---

## 🔬 Hypotheses
- Higher prices (ADR) lead to a higher cancellation rate.
- Longer lead times (booking far in advance) increase cancellation likelihood.
- The majority of cancellations originate from **offline travel agents**.

---

## 💾 Dataset
The project uses the "[hotel_bookings.csv](https://github.com/Bhabani-DA/Hotel-Booking-Cancellation-Data-Analysis/blob/main/hotel_bookings.csv)" dataset. Key features include:
- Hotel type (City or Resort)  
- Booking status (canceled or not)  
- Price per night (ADR)  
- Booking channel (e.g., Online TA, Offline TA/TO)  
- Lead time, waiting list days, customer demographics  

---

## 🛠️ Technologies Used
- Python (Pandas, NumPy)  
- Data Visualization: Matplotlib, Seaborn  
- Jupyter Notebook  
- Word/Docx Report Writing  

---

## 📖 Analysis & Approach
- **Exploratory data analysis:** Clean data, treat missing values, and examine trends in cancellations by price, lead time, booking channel, and more.  
- **Feature importance:** Use statistical analysis and visualizations (e.g., correlation heatmap, bar plots) to identify significant predictors.  
- **Targeted recommendations:** Link analytical results to practical, actionable hotel management strategies.  

---

## 📈 Key Insights from Data Analysis
- **Transient customers** have the highest cancellation rate (41.25%) – especially in **City Hotels**.
- **Higher prices** and **longer lead times** are strongly associated with cancellations.
- Bookings from **Online and Offline Travel Agents** show significantly higher cancellation rates than direct or corporate channels.
- **Group customers** and **corporate bookings** are more reliable and show **lower cancellation rates**.
- **City Hotels** have stable ADR and non-seasonal demand; **Resort Hotels** peak during summer months (Jul–Aug) but drop sharply in off-season.
- **Portugal, Great Britain, France, Spain, and Germany** are the top sources of non-cancelled bookings.

---

## ✅ Recommendations
-	**City hotels face higher cancellation risk despite being the most booked** — suggesting a need for targeted retention strategies for urban stays.  
-	**Price sensitivity drives cancellations** — bookings with higher ADR tend to cancel more often, highlighting the importance of dynamic pricing and value-based bundling.  
-	**Long lead times correlate with cancellations** — customers booking far in advance (median: 113 days) are more likely to cancel, indicating potential for flexible rebooking policies.  
-	**Deposit type and booking channel matter** — Non-refundable deposits and bookings via Online/Offline TA show higher cancellation rates than Direct or Corporate channels.  
-	**Seasonality and nationality influence stability** — July–August and spring/autumn months have more reliable bookings, especially from countries like Portugal, GRB, FRA, ESP, and DEU — ideal for geo-targeted marketing.  

---

## ✔️ Conclusion
City hotels receive more bookings but also face higher cancellation rates, highlighting the need for targeted retention strategies. Guests are particularly sensitive to price fluctuations, as higher Average Daily Rates often lead to increased cancellations. Bookings made far in advance show a stronger cancellation pattern, suggesting flexibility could improve early commitment. Online and Offline Travel Agent channels result in more cancellations compared to Direct and Corporate bookings, regardless of deposit type. Non-refundable deposits don't always deter cancellations, especially when agents are involved. Seasonality and geography matter too—summer and spring see more reliable bookings from countries like Portugal, the UK, and France.

---

## 📂 Project Structure
```bash
hotel_booking_analysis/
├── hotel_booking_analysis_project.ipynb  # Main Jupyter Notebook
├── Hotel_booking_Cancellation_Data_Analysis_Report.docx  # Detailed report
├── README.md                             # Project documentation
├── /images                               # Graphs and visualizations
└── dataset.csv                           # Cleaned dataset (if public)
