---
description: 'Puppeteer'
public: true
layout: ../../layouts/BlogPost.astro
title: 'From Scraped Data to Clean CSV, Automating Product Data for Amazon KDP'
createdAt: 1663138617853
updatedAt: 1663138617853
tags:
  - 'Puppeteer'
  - 'Web Scraping'
  - 'CSV'
  - 'Data Automation'
heroImage: '/img/csv.png'
slug: 'joey-roth'
---

# From Scraped Data to Clean CSV

This project demonstrates how browser automation can be used to collect product data, extract the relevant information, and transform the results into a structured CSV file.

The goal was to automate a workflow that would otherwise require manually collecting and organizing product information.

## The workflow

The automation follows a simple pipeline:

**Website → Puppeteer → Data Extraction → Data Processing → CSV**

Puppeteer controls the browser and handles the page interaction and data extraction. The collected information is then processed and organized into a consistent structure before being exported as a CSV file.

## Browser automation with Puppeteer

I used **Puppeteer** to automate the browser and interact with the target pages.

The script handles tasks such as:

- Launching and controlling the browser
- Navigating to the required pages
- Waiting for page content to load
- Extracting relevant product information
- Processing the collected data
- Preparing the final dataset

This removes repetitive manual collection and makes the workflow repeatable.

## Cleaning and structuring the data

Raw scraped data is not always ready to use directly.

After extraction, the data needs to be organized into consistent fields and cleaned before being exported.

The workflow transforms the extracted information into structured records that can be easily opened, filtered, and processed using spreadsheet applications or other data-processing tools.

## CSV export

The final step is generating a clean CSV file containing the processed product data.

This makes the output easier to:

- Review
- Filter
- Import into other tools
- Process programmatically
- Use as part of a larger data workflow

## Technologies

**Puppeteer**  
Browser automation and web data extraction.

**JavaScript / Node.js**  
Automation logic and data processing.

**CSV**  
Structured output for the collected product data.

## What this project demonstrates

This project demonstrates my ability to build an automation pipeline that goes beyond simply scraping a webpage.

The complete workflow is:

**Automate → Extract → Clean → Structure → Export**

The same approach can be adapted to other websites and business workflows where information needs to be collected repeatedly and transformed into a usable dataset.
