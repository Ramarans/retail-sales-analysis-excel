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
