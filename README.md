# Beauty Clinic Automation – Make.com + Airtable

## 📌 Overview
This workflow automates **lead qualification and follow-up** for a beauty clinic.  
When a customer fills out a landing page form, the data is stored in Airtable.  
If the lead qualifies based on budget, the system sends an email to the customer and notifies the sales team.

---

## ⚙️ Workflow Steps
1. **Form Submission**
   - Customer submits info via landing page form.
   - Data goes into **Airtable**.

2. **Qualification Check**
   - If `Qualification = "qualified"` → proceed with automation.

3. **Automated Actions**
   - **Customer Email** → confirmation email sent automatically.
   - **Sales Notification** → sales team receives follow-up email.
   - **Airtable Update** → record updated with “Contacted On” timestamp.

---

## 🛠️ Tools Used
- **Make.com** – automation engine  
- **Airtable** – lead database  
- **Gmail (or Outlook)** – email communication  

---

## 📂 Files in this Repo
- `Integration_Airtable_CLEAN.blueprint.json` → Cleaned Make.com blueprint (importable)  
- `workflow.png` → Screenshot of the scenario (add your own)  
- `README.md` → Documentation  

---

## ▶️ How to Import the Workflow
1. Download `Integration_Airtable_CLEAN.blueprint.json` from this repo.  
2. Log in to [Make.com](https://www.make.com).  
3. Click **Create a new scenario**.  
4. On the top-right, click **⋯ → Import blueprint**.  
5. Upload the `.json` file.  
6. Reconnect:
   - Airtable account (replace `YOUR_AIRTABLE_CONNECTION`)  
   - Gmail/Outlook account (replace `YOUR_GOOGLE_CONNECTION`)  
   - Set your Airtable **Base ID** and **Table ID**  

---

## 🖼️ Workflow Diagram
![Workflow](https://raw.githubusercontent.com/USERNAME/REPO/main/docs/workflow.png)




---

## 📖 Workflow Explanation
This automation streamlines the **lead qualification process** for a beauty clinic.  

1. **Trigger** → When a new record is added in Airtable (from a customer form submission).  
2. **Router** → Workflow splits into two paths based on qualification:  
   - **Qualified Lead** →  
     - Sends a personalized confirmation email to the customer.  
     - Updates Airtable with the “Contacted On” date.  
   - **Follow-up Path** →  
     - Extracts customer message (via regex parser).  
     - Sends a notification email to the sales team with lead details.  
3. **Update** → Airtable record is updated with the latest contact status.  

✅ **Result:** Faster response to qualified customers and instant notification for the sales team, reducing manual work and improving conversion rate.  

---

## 🚀 Benefits
- No more manual lead entry  
- Faster follow-up to qualified customers  
- Improved sales efficiency  

---

## ⚠️ Notes
- Sensitive info (emails, connection IDs) has been replaced with placeholders for security.  
- Replace placeholders with your own **connections, base IDs, and table IDs** after importing.  
