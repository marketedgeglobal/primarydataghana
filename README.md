# Primary Data Ghana Agent

This Agent automates the analysis of primary data from Ghana every Monday morning at 7:00 AM CT.

## What It Does

- Retrieves all data from a connected Google Sheet (Primary Data Input Form - Ghana Responses)
- Analyzes the data to identify the most urgent items requiring follow-up
- Generates recommendations for each urgent item
- Updates the GitHub repository (marketedgeglobal/primarydataghana) with analysis results and recommendations

## How It Works

The Agent runs on a weekly schedule and:

- Pulls the latest Ghana primary data from your Google Sheet
- Performs intelligent analysis to prioritize urgent follow-ups
- Automatically commits the analysis results to analysis-results.md in the main branch

Key Benefits

- Automated weekly review – No manual analysis needed
- Prioritized insights – Urgent items are identified and flagged
- Version control – All analysis is tracked in GitHub for audit and history
- Time-saving – Frees you from routine data review tasks

Requirements

- A connected Google Sheet with Ghana primary data (Primary Data Input Form - Ghana Responses)
- GitHub repository access to marketedgeglobal/primarydataghana
