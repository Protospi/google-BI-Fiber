Certainly! Here's a draft for your project's README file for the Google Fiber customer service project, including the information you provided:

# Google Fiber Customer Service BI Project

Welcome to the Google Fiber Customer Service Business Intelligence (BI) Project! This project is part of the interview process for a BI analyst position within the Google Fiber customer service team. The aim is to design a dashboard using fictional data to monitor and improve customer satisfaction.

## Project Background

The customer service team at Google Fiber wants to gain insights into customer call patterns and understand how often customers phone customer support again after their initial inquiry. The project aims to provide valuable insights into customer call behavior, repeat call trends, and factors contributing to repeat calls to improve the overall customer experience. The dataset used for this project is fictional and anonymized, representing a version of actual data the team works with.

### Datasets

The fictional dataset includes the following information:

- Number of calls
- Number of repeat calls after first contact
- Call type
- Market city
- Date

## Stakeholders

- Emma Santiago, Hiring Manager
- Keith Portone, Project Manager
- Minna Rah, Lead BI Analyst

## Team Members

- Ian Ortega, BI Analyst
- Sylvie Essa, BI Analyst

## Project Approvals and Dependencies

It's essential to ensure that all stakeholders have access to the datasets used for this project so they can explore the steps taken. The project data is already anonymized and approved.

## Project Goal: Explore Trends in Repeat Callers

The primary goal is to explore trends in repeat customer calls. Mr. Portone emphasizes the following objectives:

- Understand how often customers are calling customer support after their first inquiry.
- Provide insights into the types of customer issues generating more repeat calls.
- Explore repeat caller trends in three different market cities.
- Design charts to view trends by week, month, quarter, and year.

## Dashboard Requirements

- The dashboard should be accessible, with large print and text-to-speech alternatives.

## Measuring Success

The project's ultimate goal is to reduce call volume by increasing customer satisfaction and improving operational optimization. The dashboard should provide stakeholders with insights about repeat caller volumes in different markets and the types of problems they represent.

## Other Considerations

- The dataset includes columns for market_1, market_2, and market_3, representing three different city service areas.
- The dataset lists five problem types: Type_1 (account management), Type_2 (technician troubleshooting), Type_3 (scheduling), Type_4 (construction), and Type_5 (internet and wifi).
- The dataset records repeat calls over seven-day periods, with initial contact dates and columns indicating days since the first call (e.g., contacts_n_6 indicating six days since the first contact).

## People with Dashboard-Viewing Privileges

- Emma Santiago, Keith Portone, Minna Rah, Ian Ortega, Sylvie Essa

## Key Questions

1. How often does the customer service team receive repeat calls from customers?
2. What problem types generate the most repeat calls?
3. Which market city’s customer service team receives the most repeat calls?

Certainly, here's the final section of your README file with the links to the project documents:

---

## Project Documents

Here are the three key project documents produced for this Google Fiber Customer Service BI project:

1. [Stakeholder Requirements Document](https://docs.google.com/document/d/1Q07IMMDWT0HxJ2uwOvyZgOlNttPpd1AJ6rJkaqaNOqM/edit?usp=sharing&resourcekey=0-aygyvd3tdd8TarqmbVGYRw)
2. [Project Requirements Document](https://docs.google.com/document/d/12ZKLj5Quc593Qcc_GBnRz-CTlRFHfqAvunMGG9YphL8/edit?usp=sharing&resourcekey=0-V4wLC4FYY7Ry55RHulW85g)
3. [Planning Document](https://docs.google.com/document/d/16yRZ6AhkfmeLg8q17ZvAyiKxJedrkYP9azxQ7R2Nqm4/edit?usp=sharing&resourcekey=0-AN7iBBwDFObjqy2HwkMKpA)

---


## Source Datasets

Google sheets markets 1, 2, 3 tables:

* [Market 1](https://docs.google.com/spreadsheets/d/1jVyA06t9G7grA7Bvi4qfZTGxBJ5St7bBTOREPwxBkVQ/edit?usp=sharing)

* [Market 2](https://docs.google.com/spreadsheets/d/19TZ_WOEjdHSKm6QFBnlIbBbhYVesHbdGzMkf_qSdf4A/edit?usp=sharing&resourcekey=0-cm8EaTm4AwHwtSRD4G-JiA)

* [Market 3](https://docs.google.com/spreadsheets/d/1grPaIYrYQqm35M33EQon1gzO-tacVKTgXJKKwUKFnNE/edit?usp=sharing)


## Target Tables

* First the 2 tables were ingested in Bigquery big query using upload local csv feature:
    * `market1`
    * `market2`
    * `market3`

* The query to unify the tables is in the repo as `unify_tables.sql` that generate the target table:
    * `data`

    


