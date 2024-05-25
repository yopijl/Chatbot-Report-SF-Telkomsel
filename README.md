Username: @ReportSFTelBot

Link Spreadsheet: https://docs.google.com/spreadsheets/d/1jSNK54SQJzPS9FBjR0vCEdI62_MwUTJsyKq8uPBMC3A/edit?usp=sharing

# Telkomsel Sales Force Reporting Chatbot

# Overview
The Telkomsel Sales Force Reporting Chatbot is an innovative solution designed to streamline and automate the reporting process for Telkomsel's sales force activities. Previously, the reporting was manually handled using Excel sheets, which was time-consuming and prone to errors. This chatbot enables sales representatives to report their daily activities efficiently through a conversational interface on Telegram. The data collected is automatically saved into a Google Spreadsheet for easy tracking and analysis.

# Key Features
1. Automated Data Collection:
- Sales force activities are reported via Telegram and automatically recorded in a Google Spreadsheet.
- Reduces manual data entry errors and saves time for sales representatives.

2. Real-time Updates:
- The chatbot can be added to Telegram groups to provide instant responses and updates when requested.
- Ensures that all team members have access to the latest information.

3. Interactive Reporting:
- Sales representatives can report their activities using a predefined format.
- The chatbot parses the message and inputs the data into the spreadsheet, ensuring consistency and accuracy.

4. Status Queries:
- Sales force members can query the chatbot for their report status or other specific information.
- The chatbot retrieves and displays the requested data, enhancing transparency and accountability.

5. Daily Reports:
- The chatbot can generate and provide reports based on specific dates, summarizing activities for the selected period.
- Facilitates daily monitoring and management of sales activities.

# Technical Implementation
1. Functions:
- Logging:
  - Captures and stores log messages in the Log sheet for audit and debugging.
- Message Parsing:
  - Extracts relevant data from the structured report messages sent by sales representatives.
- Data Input:
  - Inserts parsed data into the Data Report sheet, ensuring correct formatting and data types.
- Status Checking:
  - Allows users to check the status of their reports and view the latest data entries.
- Report Generation:
  - Generates daily reports based on specific dates, summarizing the sales activities recorded.

- Interactive Commands:
  - /start: Activates the bot and confirms its operational status.
  - /input: Allows sales representatives to input their report data.
  - /namasf [name]: Checks the report status of a specific sales force member.
  - /report [DD/MM/YYYY]: Generates a report for a specific date.
  - /format: Provides the format for reporting sales activities.

# Benefits
1. Efficiency: Automates data collection, reducing time and effort for sales representatives.
2. Accuracy: Ensures consistent and accurate data entry, minimizing human errors.
3. Transparency: Provides real-time updates and easy access to report data.
4. Accountability: Tracks and logs all interactions and report submissions for better accountability.
5. Scalability: Can be easily scaled to handle more users and integrate with other systems.

This project leverages the power of automation to enhance the efficiency and effectiveness of Telkomsel's sales force reporting, providing a modern and user-friendly solution for daily operations.
