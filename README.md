
# 🕵️‍♂️ Google Maps Business Scraper with Contact Extraction

This n8n workflow automates the process of **scraping business information from Google Maps** and **extracting contact details** from their websites using **Apify** and **Firecrawl**.  
It was implemented as a **practice project** to explore data automation, web scraping, and API integrations in n8n.

---

## 🚀 Features

- 🔍 Search for businesses by keyword and location on Google Maps  
- 🧠 Extract structured business data via **Apify Actors**  
- 🌐 Visit business websites and extract contact info using **Firecrawl API**  
- 🧩 Loop through all results automatically  
- 📤 Output cleaned data for further use (e.g., CSV, Airtable, or database)

---

## 🧰 Tech Stack

- **n8n** – Workflow automation  
- **Apify API** – Google Maps business scraping  
- **Firecrawl API** – Web content and contact extraction  
- **HTTP Request Nodes** – API integrations  
- **Function Nodes** – Data transformation and control flow  

---

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/PelcastreA27/scrapping_n8n_GooigleMaps_3rd.git
   cd <repo-name>
   ```

2. **Import the workflow into n8n**
   - Open your n8n instance (local or cloud)
   - Go to **Workflows → Import from File/URL**
   - Paste the workflow URL or upload the JSON file

3. **Configure environment variables**
   - Set your API credentials in n8n:
     - `APIFY_TOKEN`
     - `FIRECRAWL_API_KEY`

4. **Run the workflow**
   - Trigger manually or schedule it using a Cron node
   - Review the results in your chosen output format

---

## 🧩 Example Use Cases

- Collecting contact info for marketing leads  
- Researching competitors by category and location  
- Building local business directories  
- Practicing API-based automation and data parsing  

---

## 📄 License

This project is for **educational and non-commercial use**.  
Use responsibly and comply with the terms of service of all integrated APIs.

---

## ❤️ Made with love by [Anselmo](https://github.com/PelcastreA27)
