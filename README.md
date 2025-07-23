# AMPscript Examples for Salesforce Marketing Cloud (SFMC)

This repository contains practical AMPscript examples designed for use in Salesforce Marketing Cloud (SFMC). These snippets are commonly used for dynamic email personalization, conditional content, fallback handling, and data retrieval from Data Extensions.

Each file in this repo demonstrates a specific use case or technique, with clean syntax and in-line comments for clarity.

---

## 📂 File Descriptions

### 'AMPscript Basics - Syntax'
Basic syntax examples and AMPscript structure:
- Variable declarations
- Setting values
- Outputting content with '%%=v(@var)=%%'

---

### 'Conditional Content - IFELSE'
Shows how to use 'IF', 'ELSEIF', and 'ELSE' blocks for:
- Displaying content conditionally based on values like user preferences or profile attributes.

---

### 'Dynamic CTA button'
Dynamically sets the CTA link (e.g., mailto, support page) based on user segment or attribute such as 'ServicingTeam'.
- Includes fallback handling for missing or unexpected data.
- Supports multilingual links (e.g., English and Italian).

---

### 'Handling Missing Data (Fallback)'
Demonstrates best practices for fallback logic:
- How to gracefully handle missing values in personalization fields.
- Ensures dynamic content always has a default to prevent display issues or blank output.

---

### 'Retrieve a hotel information for a subscriber'
Advanced logic to retrieve and display hotel booking details for a subscriber using 'LookupOrderedRows'.
- Filters based on subscriber key.
- Ensures only confirmed bookings with specific criteria are shown.
- Handles duplicate entries and formats check-in/check-out dates.

---

### 'Using Subscriber Attributes'
Explains how to use attributes from the **All Subscribers list** or profile attributes.
- Examples of 'AttributeValue()' usage.
- Reminder: AMPscript logic **can vary depending on the Data Extension name or structure**.
- Always verify DE field names and matching keys.

---

## ⚠️ Notes

- The AMPscript used in these files is written for use in **email content blocks** within SFMC.
- Some logic may require modification based on your **Data Extension schema** or **Business Unit configuration**.
- Always test AMPscript with real subscriber data in **Preview and Test Send** before launching to production.

---

## ✅ Intended Audience
- Marketing Cloud developers
- Email developers using AMPscript
- Teams working on dynamic, personalized campaigns in SFMC

---

Feel free to fork, reuse, and adapt as needed. Pull requests are welcome!


