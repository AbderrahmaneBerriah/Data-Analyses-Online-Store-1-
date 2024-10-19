Project Overview

This project focuses on customer segmentation using RFM (Recency, Frequency, Monetary) analysis and K-Means clustering, applied to an online retail dataset. The aim is to categorize customers based on their purchasing behavior, enabling businesses to tailor marketing strategies effectively.

Data Preprocessing
Dataset: Online retail data, including purchase information such as product descriptions, quantities, prices, and customer details.

Data Cleaning: Removed invalid records, such as negative quantities, prices, and missing customer IDs. Non-standard stock codes were also filtered to maintain data integrity.

RFM Analysis
Recency: Calculated as the number of days since the customer's last purchase.
Frequency: Counted the number of unique invoices per customer.
Monetary Value: Total spending per customer, computed from the sum of invoice totals.

K-Means Clustering
Data Scaling: Used StandardScaler to normalize RFM values for clustering.
Cluster Optimization: Identified optimal cluster count using inertia and silhouette score plots.
Cluster Labels: Assigned labels like Dormant, VIP, and Occasional based on cluster behavior.

Outlier Handling: Removed extreme outliers based on RFM features.

Visualizations
3D Scatter Plot: Displayed customer segmentation by RFM features.
![3D scatte Plot](https://github.com/user-attachments/assets/5825b0cd-217c-4b05-95f9-f9bfb91c69c7)

Violin Plots: Showed distributions for each cluster's performance in Recency, Frequency, and Monetary Value.
![Violin Plot](https://github.com/user-attachments/assets/f9ca1341-8e16-455d-ad53-ef52d147a42a)

Cluster Performance: Analyzed cluster behavior, focusing on key features

![Customers segmentation](https://github.com/user-attachments/assets/4693764c-e882-4a3b-9f3e-873cd3ad6c54)

bar graphs for customer segment performance.

![Monthly sales trends](https://github.com/user-attachments/assets/01387d6a-9cdd-47ce-b3e0-9784be62c060)

Conclusion

The business experienced steady growth in both revenue and customer traffic throughout 2011, with significant seasonal peaks in October and November likely driven by holiday promotions. November was the standout month, showing the highest sales and customer engagement. However, the sharp decline in December suggests a drop in demand post-holiday, indicating potential reliance on seasonal promotions. To maintain consistent growth and reduce the impact of such drops, the business should consider strategies to retain customers and sustain sales after peak periods. Additionally, while sales quantities grew during some months, promotions may have led to lower revenue growth, pointing to the need for balancing volume and profitability.
