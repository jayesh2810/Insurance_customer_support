# Customer_support

This project simulates a support workflow for travel insurance inquiries using autonomous agents. It leverages CrewAI and various tools to provide high-quality, friendly, and complete customer support, followed by a quality assurance review—modeled as a two-agent system working collaboratively.


Features:
- Uses environment variables for secure API key management.
- Implements a dual-agent setup:
- Support Agent: Drafts a comprehensive response.
- Quality Assurance Agent: Reviews and improves the response.
- Incorporates a web scraping tool to fetch live data from Niva Bupa's travel insurance page.
- Processes real user inquiries dynamically via CrewAI.
