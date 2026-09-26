# retail-sales-analysis-excel
Excel analysis of 35 retail orders: nested IF segmentation, pivot summaries, charts and conditional formatting. Found 31% of booked sales lost to cancellations and returns.


**Data sheet: cleaned orders with IF segmentation and conditional formatting**

- **Blue columns (A–R):** the original 35 orders, cleaned. Names are trimmed, discount is stored as a percentage, and Gross Sales, Discount Amount and Net Sales are formulas.
- **Green columns (S–X):** new columns I built with IF / nested IF and AND/OR:
  - *Realised Sales* = 0 if the order was cancelled or returned
  - *Order Value Band* = High / Medium / Low
  - *Discount Band* = Under 10% / 10–14% / 15%+
  - *Order Outcome* = Completed / In Transit / Lost
  - *Rating Check* = Excellent / Good / Poor / Missing
  - *Customer Priority* = Key Customer / Win Back / Follow Up / Regular
- **Colours:** red bold rows are lost orders, light blue rows are above-average sales, the rating column has a red-to-green colour scale, and Net Sales has data bars.

<img width="1789" height="747" alt="data" src="https://github.com/user-attachments/assets/6e05c863-5491-4082-878b-3482b17d875b" />




**Pivot summary: key figures and sales by category, city, channel and discount band**

- **Key figures:** 35 orders with INR 102,459 in booked sales. Only INR 71,014 was actually realised, so **30.7% was lost** to cancellations and returns.
- **By category:** Electronics brings the most sales (34%) but also loses the most money (INR 14,095, 41% of its sales). Beauty has the highest share lost (44%).
- **By city:** Pune lost **70%** of its booked sales, far more than any other city. Hyderabad lost the least (14%).
- **By sales channel:** Online orders make up 68% of sales but lose more (33%) than store orders (25%).
- **By discount band:** Bigger discounts did not reduce losses. 4 of 12 orders with 15%+ discount were still lost, compared with 3 of 12 under 10%.

All tables use SUMIFS, COUNTIFS and AVERAGEIFS linked to the Data sheet, so they update automatically when the data changes. Missing ratings (0) are left out of the averages.


<img width="1740" height="1064" alt="pivot" src="https://github.com/user-attachments/assets/4ee01fa8-3c83-41b1-a379-68311636ca70" />



<img width="1387" height="498" alt="insights" src="https://github.com/user-attachments/assets/91bb0738-6fe7-40aa-b142-bdabe42bc8a1" />

