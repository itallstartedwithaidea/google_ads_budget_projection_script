# Installation & Setup Instructions

Follow these steps to install and run the **Automated Budget Projection & Performance Recommendations** script in Google Ads.

---

## 1. Google Ads Script Access

1. **Log In to Google Ads**  
   - Go to [ads.google.com](https://ads.google.com/) and open the account where you want to run this script.

2. **Navigate to Scripts**  
   - Click **Tools & Settings > Bulk Actions > Scripts**.

3. **Create a New Script**  
   - Click the **+** button to add a new script.
   - Copy and paste the entire script from your repository into the Google Ads Scripts Editor.

---

## 2. Configure the Script

Open the script and locate the `CONFIG` object near the top:

```js
const CONFIG = {
  EMAIL_RECIPIENTS: ['team@company.com'],
  SUBJECT: 'Google Ads Performance and Spend Recommendations',
  ALERT_THRESHOLD: 0.1 
};
