# Google Ads Automated Budget Projection & Recommendations

**Short Description (under 300 characters):**  
Automated budget projection and performance recommendations for Google Ads. This script forecasts monthly spend, conversions, and CTR, providing data-driven spend adjustments to optimize results.

---

## Features
- **Dynamic Date Calculations:**  
  - Automatically detects the current date, days elapsed in the month, and days remaining.

- **Projected Performance:**  
  - Estimates month-end metrics (spend, clicks, impressions, conversions, CTR).

- **Actionable Spend Recommendations:**  
  - Suggests incremental budget increases (e.g., +5%, +10%) and the potential impact on clicks and conversions.

- **Email Reporting:**  
  - Sends a well-formatted HTML email to the configured recipients, summarizing current vs. projected performance.

- **Easy Configuration:**  
  - Set up alert thresholds, recipients, and email subject in the `CONFIG` object at the top of the script.

## Usage Outline
1. **Main Execution:**  
   - Calculates today’s date, determines days in the current month, and retrieves MTD stats.
2. **Metrics Calculation:**  
   - Derives key performance indicators (CTR, CVR) and projects month-end values.
3. **Recommendations:**  
   - Applies incremental percentage increases to predict how additional spend could impact clicks & conversions.
4. **Email Report:**  
   - Compiles the data into an HTML table and sends it to your specified contacts.

## License
Choose a license that suits your preference (MIT, Apache, etc.). If none is specified, it defaults to “All Rights Reserved.”

