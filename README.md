# Valuations
Intrinsic Equity Valuations using DCF models.<br>

![Logo_of_BİM](https://github.com/hamzahalhalabi1/Valuations/assets/80872291/3cbca5af-a263-4d94-9018-be87b36c7170)<br>
<img width="496" alt="Screenshot 2024-01-24 192350" src="https://github.com/hamzahalhalabi1/Valuations/assets/80872291/d5c62715-49d9-4fdf-b11a-d2d1ffb1d47a">
<img width="164" alt="Screenshot 2024-01-24 192402" src="https://github.com/hamzahalhalabi1/Valuations/assets/80872291/b89185de-5cd4-4339-b52f-49af9d6e3488"><br>
<img width="185" alt="Screenshot 2024-01-24 194303" src="https://github.com/hamzahalhalabi1/Valuations/assets/80872291/40c53789-74a7-495a-8113-f8ca3c27988f">
<img width="365" alt="Screenshot 2024-01-24 194802" src="https://github.com/hamzahalhalabi1/Valuations/assets/80872291/9a7a8882-9e36-47c6-ae8d-2fd233e0870f"><br>
**Stock price 01/23/2024: 361TL**<br>
**Company description & Valuation story:** <br>
In 2022, the retail industry faced both opportunities and challenges due to high inflation. The sharp decline in consumer purchasing power led to increased demand for high discount retailing and private-label products. Despite challenges such as the depreciation of the country's currency, rising investment costs, and climbing operational expenses, BİM successfully gained new customers across all strata, expanding its market share. Factors like the escalation of electricity and fuel expenses, as well as two minimum wage increases, contributed to rising personnel expenses and adversely affected profit margins.
Despite these challenges, BİM demonstrated social responsibility by consistently standing by customers with its "everyday low price" policy. The company, with 9,760 stores, maintained progress in store openings, adding 1,021 new stores in 2022. BİM's commitment to efficiency improvements and competitive pricing allowed it to create added value for the country, reflecting gains in the face of higher costs. The company's resilience was evident as it navigated through the complexities of a period marked by declining consumer purchasing power.
Looking forward, the largest supermarket retail chain in Türkiye, BİM, faces significant risk in its operations in Turkey due to inflation. While being the cheapest retailer poses challenges with a small profit margin, the company has managed to offset this through various strategies. With operations also in Morocco and Egypt, albeit on a smaller scale, the focus remains on the Turkish market. Despite a negative growth rate, the company's stock is at an all-time high, reflecting investor confidence. Analysts anticipate potential future improvement in the economy, which could positively impact BİM's income as inflation prices stabilize. The expectation is that the economy will recover, leading to increased growth and improved financial performance for the company in the foreseeable future.<br>

Market Data<br>
The risk-free rate that will be used for the Turkish Lira is the 10-year government bond rate of 26.6%. 
Risk premium can be calculated by adding the mature market risk premium of 4.6% to the country risk premium of Turkey of 9.51% which is the result of default spread because Turkey’s bonds are not AAA rated. Equity risk premium will be 14.11%. <br>
Beta<br>
Ther is two ways to get the Beta of our company. <br>
Regression β<br>
Using the fluctuation of the stock compared to the market index BISTTUM we can find the following:<br>
![image](https://github.com/hamzahalhalabi1/Valuations/assets/80872291/23c58083-f1f1-40bc-ba4b-9f0ad3268675)<br>
![image](https://github.com/hamzahalhalabi1/Valuations/assets/80872291/27917a95-dd3f-410c-b75f-f1a327f8eddb)<br>
![image](https://github.com/hamzahalhalabi1/Valuations/assets/80872291/17ae3264-7681-4a96-a9a1-626e0b91f435)<br>

Bottom-up β<br>
![image](https://github.com/hamzahalhalabi1/Valuations/assets/80872291/61be4c05-2679-45fc-ac24-9a13c2db63eb)<br>

On the other hand, the bottom-up beta calculates the beta intrinsically based on the company’s revenues. Since Bim is in the retail industry only, we have our weight completely from this market. Because we are using the average of the industry, we must unlever beta based on the debt-to-equity ratio, because financial leverage is crucial for the riskiness as having more debt can increase the risk for a company. <br>

Discount rates<br>
Because we are going to do a firm DCF we need to find the weighted average cost of capital(WACC) and to find it we need both the cost of equity and cost of debt.<br>
![image](https://github.com/hamzahalhalabi1/Valuations/assets/80872291/ea75c182-24dd-4d93-9ee4-1fbbfbb30726)<br>
I used a slightly different variations to find the COE by either using a regression or bottom-up beta or by adding the country’s default spread. <br>

Cost of debt<br>
![image](https://github.com/hamzahalhalabi1/Valuations/assets/80872291/1a3dc895-0a6d-42dc-b643-03517e1492a5)<br>
I used 3 different ways to find the cost of capital. Either by using the trailing 12 months, previous year or the synthetic rating. Bim mad a statement that as of December 31, 2022, the company has no short-term interest free financial debt so I was not able to find the cost of debt using the bond rate. <br>
Cost of capital<br>
![image](https://github.com/hamzahalhalabi1/Valuations/assets/80872291/c5062613-f13e-4376-a566-d1437fa2c0b3)<br>
All the different discount rates are using the same debt and equity ratios it just the difference of cost of equity and cost of capital.<br>

Free cash flow to firm<br>
![image](https://github.com/hamzahalhalabi1/Valuations/assets/80872291/1fa4bdb2-3b0b-4df9-8282-954d1e9b5f3b)<br>
*The method is straight forward and has no alteration on R&D or lease.<br>
FCFF & PV <br>
![image](https://github.com/hamzahalhalabi1/Valuations/assets/80872291/cd2ee0bc-4b4a-4f24-b5e5-46a1f51bd3d1)<br>
Using the accumulated cost of capital to discount the FCFF we can find the present value of the company after 10 years. <br>

Growth:<br>
The growth for the present year is found by multiplying the reinvestment rate by the return-on-investment capital. ROIC has decreased significantly the past 3 years, and the reinvestment rate were decreasing because of the Capital Expenditure. My assumption is that the company is converting all the money to other types of capital to avoid losing the value over time.<br>
![image](https://github.com/hamzahalhalabi1/Valuations/assets/80872291/e12b6cb9-a316-4f20-8367-c58daa4ee5df)<br>

Story to numbers:<br>
Implementing a 2-stage DCF model<br>
![image](https://github.com/hamzahalhalabi1/Valuations/assets/80872291/b09d3aa9-363f-49c0-9e6e-6a88ef248242)<br>
Unlike the previous year 2023 had a negative growth rate mainly because of inflation however I am assuming if that is true it will regain the growth again in the upcoming years and retain a growth rate of about 10% to 14% for the upcoming 5 years. It will not have a higher growth like the one happened between 2020/2021 and 2021/2022 because inflation probably cause the numbers to be pumped up.  As we reach the terminal year, we decrease the growth to 12% (average before inflation) which is the risk-free rate for the 10-year Turkish bond I am expecting to become after 10 years. Effective tax rate will converge to the marginal tax rate too and I gave my trust that BIM has more than the average Sales to capital Ratio as it is the biggest market in Turkiye. <br>
![image](https://github.com/hamzahalhalabi1/Valuations/assets/80872291/ca0fb8fd-dff3-4629-98e1-41bfb18e3212)<br>
These figures stem from my assumptions I made. The revenue trends over time mirror the anticipated revenue expansion, the operating margins adjust towards the specified target, and the tax rate will vary if its designated it to do so. The projected reinvestment is calculated utilizing the sales to capital ratio for the initial decade and relies on a reinvestment rate in stable growth (g/ROC).<br>
![image](https://github.com/hamzahalhalabi1/Valuations/assets/80872291/1a5fd423-d555-4979-ac39-0f2a5b1e4f9d)<br>
This represents the result of the valuation. It involves the discounting of cash flows at the cost of capital to determine the value of operating assets. This value is then modified based on the probability that the company may not succeed. We incorporate cash and non-operating assets, while deducting debt and minority interests, to arrive at the equity value.<br>

Assumptions:<br>
-	In stable growth, I will assume that your firm will have a cost of capital similar to that of typical mature companies (risk-free rate + 4.5%)<br>
-	The firm will earn a return on capital equal to its cost of capital after year 10. I am assuming that whatever competitive advantages you have today will fade over time.<br>
-	I will assume that your firm has no chance of failure over the foreseeable future.<br>
-	I will assume that today's risk-free rate will prevail in perpetuity. If you override this assumption, I will change the risk-free rate after year 10.<br>
Valuation output<br>
![image](https://github.com/hamzahalhalabi1/Valuations/assets/80872291/c15f7724-6615-44ed-bb5d-58632a222b7c)<br>
![image](https://github.com/hamzahalhalabi1/Valuations/assets/80872291/b6fae20a-0412-4614-9689-4ad8b4c6e563)<br>
After conducting the DCF we find the estimated value of the share to be 365.73 which is a little below the actual price. In this case a buy recommendation is advised.<br>
![image](https://github.com/hamzahalhalabi1/Valuations/assets/80872291/7f6b81c7-c0d8-4de1-b693-f4f276d06a13)<br>

Recources Used:<br>
https://english.bim.com.tr/Categories/654/annual-reports.aspx<br>
https://pages.stern.nyu.edu/~adamodar/New_Home_Page/home.htm<br>
https://www.denizyatirim.com/Uploads/Deniz_Yat_r_m_2024_Strateji_Raporu_5472.pdf<br>
https://www.investing.com/<br>
https://finance.yahoo.com/<br>
