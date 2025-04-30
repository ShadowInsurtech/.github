### 💀Shadow Insurtech💀

Welcome to **Shadow Insurtech**, where cutting-edge cloud microservices and AI converge to transform the insurance lifecycle. Our modular, serverless platform empowers agencies and brokers to:

- **Automate Lead Generation & Enrichment**  
  Harvest and profile prospects from NCCI, social networks, public records, and web directories.  

- **Streamline Underwriting & Proposals**  
  Drive biBERK quote automation, ACORD PDF generation, and smart policy recommendations.  

- **Accelerate Email & SMS Workflows**  
  Leverage GPT-powered triage, templating, Mailgun routing, and SMS notifications.  

- **Deliver Real-Time Insights**  
  Orchestrate data pipelines with Pub/Sub, analyze screenshots via Vision+Vertex AI, and serve results through GraphQL and REST gateways.  

---

## Explore Our Microservices

| Service                                | Purpose                                                        |
|----------------------------------------|----------------------------------------------------------------|
| **crawler-puppeteer-ncci**             | Scrape workers’ comp code data from NCCI.                     |
| **xlsx-gcs-parser**                    | Parse GCS-stored XLSX into MongoDB + Pub/Sub events.          |
| **naic-codes-service**                 | Lookup NAIC code descriptions via REST API.                   |
| **google-search-service**              | Fetch business & owner insights from Google Search.           |
| **crawler-puppeteer-facebook/linkedin/instagram/websites** | OSINT-style profile scraping across social & web.             |
| **agent-vision-service**               | Analyze screenshots using OpenAI Vision & Vertex AI.          |
| **orchestrator-qualifier**             | Coordinate end-to-end scraping, classification & storage.      |
| **logs-orchestrator-service**          | Stream real-time logs and metrics from all scrapers.          |
| **pdf-acord-generator**                | Generate ACORD-130 insurance forms as PDFs.                   |
| **email-service**                      | Send, receive & track emails via Mailgun with GPT templating. |
| **sms-service**                        | Dispatch and manage SMS notifications.                        |
| **biberk-proposal-service**            | Automate biBERK quote scraping and proposal creation.         |
| **cennairus-gateway-graphql-nest**     | Unified GraphQL gateway for all microservices.                |
| **api-gateway-main-rest**              | NestJS REST gateway for secure routing & authentication.      |
| **cron-service**                       | Scheduled data sync tasks and REST endpoints in Go.           |

---

## Getting Started

1. **Browse our Repos**  
   Find each service in the [Shadow Insurtech GitHub organization](https://github.com/ShadowInsurtech).  
2. **View API Docs**  
   Visit the [Shadow NCCI API Documentation](https://github.com/ShadowInsurtech/.github/blob/main/README.md) for detailed endpoints and examples.  
