# n8n-seo-audit-workflow
Automated on-page SEO audit using n8n. This workflow analyzes meta tags, headings, keywords, broken links, and page speed, then generates structured SEO reports in CSV/JSON format. A no-code/low-code solution for automating SEO checks and improving website optimization.

On-Page SEO Audit Automation (n8n)

This project automates on-page SEO auditing using n8n workflows. It extracts website data, checks SEO health (meta tags, keywords, headings, links, performance, etc.), and generates structured reports automatically.

🚀 Features

Automated meta tag and keyword checks

Detects missing or duplicate title/description tags

Audits headings (H1–H6) for SEO compliance

Finds broken links and missing attributes (alt tags, canonical, etc.)

Option to export results as CSV/JSON reports

Fully automated with n8n workflow JSON

🛠️ Tech Stack

n8n (workflow automation)

APIs (Google PageSpeed Insights, SEO analyzers, or custom parsers)

JavaScript/Python functions inside n8n (optional for extra logic)

CSV/JSON output

📂 Project Structure

workflow.json → n8n workflow export

README.md → documentation

samples/ → example reports (CSV/JSON)

docs/ → workflow screenshots & usage guide

⚡ How to Use

Import workflow.json into your n8n instance

Update credentials/API keys (if required)

Run the workflow and provide target URLs

Get the audit results in CSV/JSON format

📧 [See example SEO audit output](/sample-seo-audit.md)
