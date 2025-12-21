# 🤖 Automated Resume Submission using n8n

This project automates the entire job application process using **n8n**, from fetching the latest job listings to sending your resume automatically and tracking each submission in a Google Sheet. It eliminates manual effort and ensures consistent, timely applications with complete reporting.

---

## 📘 Project Overview

The **Automated Resume Submission** workflow in n8n performs the following tasks automatically:

1. **Fetches new job listings** from the web.  
2. **Extracts and cleans job data** for relevant information.  
3. **Retrieves official company emails** using verified sources.  
4. **Sends personalized emails** with your resume attached.  
5. **Logs all application details** to Google Sheets.  
6. **Generates and sends a daily summary report** to the user.

This automation runs on a scheduled interval (every 2 hours) and processes all newly posted jobs within the last 24 hours.

---

## ⚙️ Features

- 🔁 **Fully automated job application flow**  
- 🧠 **Smart filtering** to avoid duplicate or previously applied jobs  
- 📧 **Email verification and retrieval** using Hunter.io  
- 📄 **Automatic email sending with resume attachment**  
- 📊 **Live tracking via Google Sheets**  
- 📬 **End-of-day summary report via email**

---

## 🧩 Workflow Steps

### 1. **Job Fetching from Apify**
Automatically gathers the latest job postings from online job boards to keep the system updated with new opportunities.

### 2. **Email Retrieval via Hunter.io**
Finds verified company email addresses to ensure that each job application reaches the correct contact.

### 3. **Resume Sending via Gmail**
Sends a customized email with your resume attached directly to the company email, ensuring professional outreach.

### 4. **Job Data Logging**
Records every job application (company name, email, date, and status) into a connected Google Sheet for tracking and analysis.

### 5. **Report Generation & Notification**
Creates a summary report of all jobs applied to and emails it to the user automatically for daily updates.

---

## 🛠️ Tools & Integrations

| Tool / Service | Purpose |
|----------------|----------|
| **n8n** | Workflow automation platform |
| **Apify** | Job data scraping / fetching |
| **Hunter.io** | Email discovery and verification |
| **Google Sheets** | Data logging and tracking |
| **Google Drive** | Resume storage |
| **Gmail API** | Email automation and notifications |

---

## 📅 Automation Schedule

- The workflow runs automatically **every 2 hours**.
- Ensures all new jobs posted within the last **24 hours** are fetched and applied to.

---

## 🚀 How It Works

1. The workflow starts and fetches job listings.  
2. Each job is cleaned, filtered, and checked against existing records.  
3. Company domains are identified, and valid emails are retrieved.  
4. The system sends resumes to verified company emails.  
5. All activity is logged and summarized in a report emailed to the user.

---

## 📈 Output

- **Google Sheet Log** → Tracks all jobs with sent status.  
- **Email Summary Report** → Sent to the client daily with full application history.  
- **Automated Applications** → Delivered directly to company inboxes.

---

## 🧠 Benefits

- 100% hands-free job application process.  
- Reduces manual errors and missed opportunities.  
- Maintains a structured and accessible job application history.  
- Provides continuous updates and transparency.

---

## 🧾 Future Enhancements

- Add AI-based job matching and resume customization.  
- Integrate LinkedIn API for automatic job fetching.  
- Include sentiment analysis on job descriptions for prioritization.

---

## 👤 Author

**[Your Name]**  
Automation Developer | n8n Workflow Enthusiast  
📧 [Your Email]  
🌐 [Your GitHub / Portfolio Link]

---

## 🪪 License

This project is licensed under the **MIT License** — feel free to use, modify, and share with attribution.

---

> _Built with ❤️ using n8n — The power of automation made simple._
