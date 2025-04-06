# AI Support Agent for Mifos/Fineract Community using Botpress

## Project Overview

The Mifos and Fineract ecosystems offer robust platforms for financial services, but their complexity poses a challenge for new users and developers. Currently, community support is provided through Slack and various documentation sources, leading to inconsistent and delayed responses.

This project aims to create an intelligent, AI-powered support chatbot using **Botpress**. The bot will assist users by answering frequently asked questions, linking to relevant documentation, and learning from historical community interactions.

Initially, the chatbot will support one Mifos product and be deployed on Slack. Future iterations may expand to cover other products and include web integration.

---

## Objectives

- Identify the best AI/NLP approach to integrate with Botpress
- Build a PoC chatbot for one Mifos product using Botpress
- Train it using historical Slack conversations, FAQs, and documentation
- Evaluate its performance with common user queries
- Deploy the bot to Slack for community use
- Prepare for future web integration and product expansion

---

## Tools & Technologies

- **Botpress** (open-source AI chatbot builder)
- **Slack API** (for bot deployment and integration)
- **Vector Database** (Weaviate or Pinecone for embedding Q&A)
- **LangChain / OpenAI / HuggingFace** (for RAG and semantic search)
- **Markdown/HTML Parser** (for documentation ingestion)
- **GitHub** (for code management and CI workflows)

---

## Project Timeline

| Week | Task |
|------|------|
| Week 1 | Research support workflows, select PoC product, gather Slack and doc data |
| Week 2 | Set up Botpress environment, create dev Slack bot |
| Week 3 | Preprocess Slack Q&A + docs for training |
| Week 4 | Train chatbot with static and dynamic (RAG) knowledge |
| Week 5 | User testing, improve accuracy and fallback logic |
| Week 6 | Finalize Slack deployment, document implementation |
| Week 7–8 (Stretch) | Add web interface, plan multi-product expansion |

---

## Deliverables

- Slack-deployed chatbot for one Mifos product
- Knowledge base from Slack and documentation
- Botpress project repo with flows and training data
- Deployment and contribution guide
- Stretch: Web interface for chatbot

---

## Future Plans

- Add NLP-driven FAQ expansion from Slack logs
- Expand to support more Mifos/Fineract products
- Continuous improvement through community contributions
- Integrate with documentation update workflows

