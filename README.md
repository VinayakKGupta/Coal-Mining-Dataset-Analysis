# Coal-Mining-Dataset-Analysis

Made 4 reports of employee, sales, customers, equipments  performance using Power BI and DAX.

1) Identified a $10.76M potential revenue uplift by determining the optimal equipment maintenance window (1–2 years) using DAX and BI to maximise operational efficiency.


<img width="890" height="489" alt="image" src="https://github.com/user-attachments/assets/3f072042-beaa-4dc5-9b1f-e27941b7a4b0" />


DaysSinceLastMaintenance 
→ MaintBucket Classification 
→ Avg Tonnes (Current Bucket) 
→ Avg Tonnes (1–2 Years Baseline) 
→ Tonnes Uplift per Extraction (Base − Current) 
→ Avg Extractions per Month 
→ Monthly Tonnes Uplift 
→ Avg Unit Price 
→ Revenue Uplift

2) Uncovered top-performing extraction sites through monthly ore and ore-type analysis, with New Laura Shaft, Matthewstad Mine, and Easy Tommy Shaft collectively producing over $5M tonnes.



<img width="890" height="498" alt="image" src="https://github.com/user-attachments/assets/02fb891e-9646-4444-b810-6035a6e4b8c2" />

3) Recognised $53.4M in revenue loss from overdue client payments using Power BI and DAX, and analysed client profitability to highlight high-value accounts for improved revenue management.
   
<img width="886" height="492" alt="image" src="https://github.com/user-attachments/assets/5bd73817-41b9-4c17-bfae-1144c1f3b676" />

Late payment cost represents the financial loss a business incurs when customers do not pay invoices on time. In this model, a 15% factor is applied to overdue revenue as a proxy for the cost of delayed cash flow, including financing costs, missed investment opportunities, and increased risk of non-payment. This means that for every dollar of overdue revenue, the business effectively loses 15 cents in value, impacting overall profitability and operational efficiency.

Total Revenue 
→ Filter Overdue Invoices (PaymentStatus = "Overdue") 
→ Overdue Revenue 
→ Apply 15% Cost Factor 
→ Cost of Late Payments

4) Assessed employee efficiency using productivity metrics segmented by department and site to identify top performers.

<img width="879" height="489" alt="image" src="https://github.com/user-attachments/assets/e3805a49-e463-447c-a00f-8ad222698978" />

