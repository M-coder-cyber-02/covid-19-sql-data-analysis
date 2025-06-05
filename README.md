## Project Overview

Analyzed COVID-19 mortality data from the CDC’s Contributing Factors dataset using SQL to uncover patterns in death rates by state, age group, and contributing health conditions. Designed to demonstrate healthcare data analysis skills suitable for healthcare analytics and public health informatics roles.

## Objectives

Clean and validate COVID-19 death records dataset

Identify trends in deaths over time and by demographics

Rank states by COVID-19 death toll annually

Analyze contributing conditions associated with higher mortality

Generate insights into age-specific and state-specific trends

## Dataset Description

Source: CDC’s COVID-19 Contributing Factors Data (CSV)
Key Columns:

data_as_of

start_date, end_date

state

condition_group, condition, icd10_codes

age_group

covid_deaths

number_of_mentions

flags

## Tools & Technologies

PostgreSQL (via pgAdmin)

SQL window functions (RANK(), DENSE_RANK())

Aggregations (SUM(), AVG())

Date functions (EXTRACT(), DATE_TRUNC())

Data validation queries (DISTINCT, COUNT(), HAVING)

## Key Analyses & Queries

Total COVID-19 deaths per state per year

Deaths by age group and condition

Death trends by month and year

## Top contributing conditions per state

Deaths with vs without contributing conditions by age group

Rank states annually by total COVID-19 deaths

Identify states exceeding 5,000 deaths per year

Average contributing conditions per death

Data quality checks for unexpected labels and flags

## Key Findings

Certain states consistently experienced higher COVID-19 deaths, especially in 2020-2021

Older age groups had significantly higher death rates

Common contributing factors included respiratory diseases, diabetes, and cardiac conditions

The number of deaths involving multiple contributing factors was higher in elderly groups

Several records contained unusual or unknown flags requiring cleaning

