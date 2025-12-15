# LinkedIn Job Email Automation

This n8n workflow automates sending LinkedIn job postings via email.  

## Workflow Details
- **Trigger:** Cron node (daily or weekly)  
- **Scraper:** Apify actor to get relevant job listings  
- **Storage:** Google Sheets (optional for logging)  
- **Email:** Gmail / SMTP node to send job updates  
- **Function Node:** Formats job data for email  

## Usage
1. Import the `linkedin-job-email-workflow.json` file into n8n.  
2. Connect your Google Sheets, Gmail, and Apify accounts.  
3. Adjust the Cron schedule and email recipients.  
4. Run the workflow to send job updates automatically.
