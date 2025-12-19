AI Outbound Prospecting Project

This repository contains the code and configuration to build an AI‑powered outbound prospecting pipeline.  
It is designed to run inside GitHub Codespaces and supports Python and Node.js development for tasks such as data ingestion, web scraping, enrichment, scoring and outreach automation.

Project Structure:

├── .devcontainer/        # Configuration for GitHub Codespaces
│   └── devcontainer.json # Defines the development environment
├── data_ingestion/       # Scripts for fetching data from Lusha, Sales Navigator, etc.
├── scrapers/             # Node.js Apify actors and scraping helpers
├── enrichment/           # Diffbot integration and data cleaning modules
├── scoring/              # Business success scoring logic
├── outbound/             # Overloop API integration and campaign scripts
├── qualification/        # YourAtlas integration for phone qualification
├── requirements.txt      # Python dependencies
├── package.json          # Node.js dependencies for scrapers
└── README.md             # This file
