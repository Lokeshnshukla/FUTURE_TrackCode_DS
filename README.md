# FUTURE_TrackCode_DS-
Data Science &amp; Analytics Internship - Task 1
<br>

<br>
<br>
- Total_customer = DISTINCTCOUNT(orders[CustomerID])
<br>
<br>
- Total_orders = DISTINCTCOUNT(orders[order_id])
<br>
<br>
- Total_revenue = SUMX(orders,orders[Sales]*Orders[Quantity])
 <br>
 <br>
- Total_return = CALCULATE(SUMX(orders,orders[Sales]*Orders[Quantity]),Orders[Retur]="No")
<br>
<br>
- Total_sale = Calculate(SUMX(orders,Orders[Sales]*Orders[Quantity]),Orders[Retur]="Yes")
 <br>
 <br>
- Total_quantity = SUM(Orders[Quantity])
<br>
<br>
- AOV = Divide([Total_revenue],[Total_orders],0)
<br>
<br>
<img width="667" height="55" alt="image" src="https://github.com/user-attachments/assets/b2b0760a-1f12-4900-8e5d-7524093eee40" />

<br>
<br>

<br>
<br>
<br>
<img width="775" height="436" alt="image" src="https://github.com/user-attachments/assets/504b5e76-79ed-4fb2-997a-383a8e30721f" />
