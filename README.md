**1)	Project overview**<br />
-----------------------------
*Main business question: Where should we invest next: product expansion or channel expansion?*<br />

This project analyzes retail revenue data from 2022–2024 to support strategic investment decisions. Using Power BI, I evaluate product category performance and sales channel dynamics (Online vs In-store) to identify where future growth opportunities lie and where investments should be optimized or prioritized.<br /><br />
 
**2)	North Star Metrics and Dimensions**<br />
----------------------------------------------
**•	Revenue:** Total revenue from product sales within different categories and line items<br />
**•	Year-over-year (YoY) revenue growth**<br />
**•	Percentage revenue change (2022-2024)**<br />
**•	Transaction date:** Yearly or quarterly figures<br />
**•	Product category:** Beverages, Butchers, Computers and electronic accessories, Electronic household essentials, Food, Furniture, Milk Products and Patisserie<br />
**•	Channel:** In-store and Online<br /><br />

**3)	Data Quality & Preparation**
---------------------------------
The original dataset used for this project was not ready for analysis and contained several common real-world data quality issues.<br />

Before any exploratory data analysis (EDA) or dashboarding, the dataset was cleaned and standardized to ensure reliable insights.<br />

All data quality issues identified, and the actions taken to resolve them are fully documented in the “Issues log” tab of the *retail_store_sales.xlsx* file.<br />

This log provides transparency on:<br />
•	The issue detected<br />
•	The quantity of rows in which the issue is witnessed<br />
•	An indication of whether the issue is solvable (“Yes” or “No”)<br />
•	The corresponding resolution on how the issue is handled with, or why the issue cannot be resolved<br /><br />

**4) Summary of Insights**<br />
--------------------------------
**Channel level insights:**<br />
•	Online channel significantly outperformed In-store sales in 2022<br />
•	In 2023 and 2024, Online and In-store sales show similar revenue performance<br />
•	Both channels grew in similar fashion from 2023 to 2024 indicating channel saturation<br />

Implication: Channel expansion alone is unlikely to be the strongest growth lever<br />

**Product Portfolio Insights:**<br />
High Revenue + High Growth (Scale / Invest)
-	Beverages
-	Furniture
-	Food<br />

High Revenue + Low Growth (Mature / Defend)
-	Butchers
-	Electronic Household Essentials<br />

Low Revenue + High Growth (Emerging Opportunities)
-	Computers and electronic accesories<br />

Low Revenue + Low Growth (Deprioritize / Exit)
-	Milk products
-	Patisserie<br />

**Revenue Volatility Analysis (Risk Lens)**
The most volatile product categories based on YoY revenue growth:<br />

Category *Tabspace**Tabspace*	  2023 YoY *Tabspace**Tabspace*	 2024 YoY<br />
Beverages *Tabspace**Tabspace*  -12.3% *Tabspace**Tabspace*	   +33.1%<br />
Butchers *Tabspace**Tabspace*   -25.9% *Tabspace**Tabspace*	   +12.3%<br />
Food *Tabspace**Tabspace*	      +18.5% *Tabspace**Tabspace*	   -2.5%<br /><br />


**5) Recommendations & Next Steps**
----------------------------------
*Answer to main business question: The data indicates that future investment should prioritize product expansion over channel expansion*<br />

**•	Prioritize product expansion over channel expansion:** Online and In-store channels have converged in performance since 2023, limiting incremental upside from further channel-focused investment.<br />
**•	Invest selectively in high-growth product categories:** Beverages, Furniture, and Food combine strong revenue contribution with growth momentum, while Computers and electronic accessories represent promising emerging opportunities.<br />
**•	Optimize mature categories, don’t overinvest:** Butchers and Electronic Household Essentials should focus on efficiency and margin protection rather than aggressive growth.<br />
**•	Deprioritize low-impact categories:** Patisserie and Milk Products show limited scale and growth and are unlikely to generate meaningful returns.
