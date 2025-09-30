# Tim Veedahl — Data & Healthcare Analytics Portfolio

**Healthcare & Digital Analytics — Epic Cogito • GA4 • Power BI • SQL**  
_Madison, WI (Open to remote)_

---

## 👋 About
I build clean, reliable dashboards and data pipelines that turn clinical and digital data into actionable insight. My focus is reproducible reporting (Power BI, SQL) and modern web analytics (GA4, GTM), supporting population health and value-based care initiatives.

📧 **Email:** youremail@example.com  
🔗 **LinkedIn:** [linkedin.com/in/yourprofile](#)

[📄 Download Resume](resume.pdf)

---

## 🧩 Core Skills
- Epic Cogito / Clarity / RADAR
- SQL (Redshift, Postgres, T-SQL)
- Power BI (DAX, Data Modeling)
- GA4, GTM, Looker Studio, BigQuery
- Python (Pandas) — for ETL & analysis
- Data Visualization & Dashboard Design
- Population Health Analytics
- Reporting Automation

---

## 📊 Featured Projects

### 1. **Population Health Dashboard — Power BI**
**Tools:** Power BI • SQL • DAX • Epic Cogito  
Built a provider-level dashboard visualizing readmissions, care gaps, and risk stratification. Used SQL against a Clarity-like dataset and modeled measures in Power BI using DAX.

[🔍 View Case Study](#)

---

### 2. **GA4 Funnel & Attribution — Looker Studio**
**Tools:** GA4 • GTM • Looker Studio • BigQuery  
Implemented GA4 and GTM tracking for a DTC e-commerce site. Created funnel visualizations and an attribution summary in Looker Studio using BigQuery exports.

[📈 View Dashboard](#)

---

### 3. **Epic Cogito Reporting Example**
**Tools:** Epic Cogito • SQL • Power BI  
Sample Epic Cogito-derived report showing utilization trends and RADAR-style visualizations. Includes anonymized SQL snippets and report specs.

[📄 Download Snippets](#)

---

### 4. **Mini GA4 Audit (Template)**
**Tools:** GA4 • GTM • Looker Studio  
A short audit checklist and Looker Studio template for small business clients to assess their tracking setup.

[📎 Get Template](#)

---

## 🧠 Technical Skills Summary

| Category | Tools / Focus |
|-----------|----------------|
| Data Analytics | Power BI, SQL, Epic Cogito, Clarity |
| Digital Analytics | GA4, GTM, Looker Studio, BigQuery |
| Visualization | Power BI, Looker Studio, DAX, Chart Design |
| Programming | Python (Pandas, Jupyter) |
| Domain Expertise | Healthcare Analytics, Population Health, EHR Data |

---

## 💡 Example SQL Snippet
```sql
-- Example: cohort counts by month
SELECT
  date_trunc('month', encounter_date) AS month,
  patient_count
FROM (
  SELECT encounter_date::date, COUNT(DISTINCT patient_id) AS patient_count
  FROM encounters
  WHERE encounter_date >= '2024-01-01'
  GROUP BY encounter_date::date
) t
ORDER BY month DESC;
```

---

## 💼 Work With Me
Interested in a freelance GA4 audit, Power BI dashboard, or Epic Cogito reporting project?  
I offer short engagements with clear deliverables and full documentation.

📧 [Email Me](mailto:youremail@example.com)

---

© **Tim Veedahl** — Built for analytics portfolios • Hosted on GitHub Pages
