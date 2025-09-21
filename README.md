🏨 **Hotel Bookings Analysis**
📌 **Project Overview**

This project performs Exploratory Data Analysis (EDA) on a hotel bookings dataset to identify key trends, cancellation patterns, customer behavior, and provide actionable recommendations for hotel management.

The analysis focuses on:

Booking cancellations and their drivers

Seasonal and monthly booking trends

Impact of lead time, day of week, and special requests

Guest segmentation (domestic vs international, customer types)

📊** Dataset**

Source: Based on public hotel booking dataset

Records: ~119,000 bookings

Key fields: Booking dates, arrival dates, length of stay, customer details, ADR (Average Daily Rate), cancellations, and special requests.

🛠️ **Methodology**

**Data Preprocessing**

Handled missing values (mean/median/mode)

Corrected data types

Removed duplicates

Treated outliers appropriately

**Exploratory Data Analysis (EDA)**

Booking trends by month and customer type

Cancellation patterns by lead time, day of week, and special requests

Distribution of ADR across customer segments

**Visualization**

Created bar charts, line graphs, and scatter plots using Seaborn and Matplotlib

Highlighted patterns in cancellations, customer behavior, and seasonal demand

🔑 **Key Insights**

Higher lead time = higher cancellations, while last-minute bookings are more committed.

Weekends (Fri-Sat) see higher cancellations compared to weekdays.

Guests with special requests cancel less frequently, indicating stronger commitment.

International guests stay longer and cancel less compared to domestic guests.

💡 **Recommendations**

Implement stricter cancellation policies for long lead-time bookings.

Offer discounts for non-cancellable/early bookings to encourage commitment.

Upsell personalized services (special requests) to reduce cancellations.

Promote longer-stay offers for international guests.

🛠️ **Tools & Technologies**

Language: Python

Libraries: Pandas, Seaborn, Matplotlib

Environment: Jupyter Notebook
