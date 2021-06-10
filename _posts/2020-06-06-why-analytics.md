---
layout: post
title: Why Data Analytics sometimes make me question my sanity?
---

I've been working as a data analyst in two different industries over the past 5 years. Data Analytics as a skill in itself isn't difficult to learn. The main challenge that comes with being a data analyst actually revolves around understanding, obtaining and cleaning of data. When a system or application is created, the database structure is designed by the developer. A data analyst's job is to figure out how and why a developer designed a data structure in a specific way, and figure out how they can extract that data to build dashboards and insights around them. On paper, this might seem easy: extract the data, write the SQL code, build a couple of bar charts. Not so fast...here are a couple of issues that the analyst will need to figure out:

  1. Where will the data be stored? In a database, in a datalake, in a data warehouse, which format is most suitable? Are there storage limitations?
  2. What is the Data Extraction Process like? Is it efficient enough to extract data without affecting the efficiency of the system database?
  3. Is the data accurately being extracted? Are there specific data that are being left out?
  4. What happens when a record is deleted in the original system, can the destination storage account for deletions? 
  5. What are the metrics to be used in the dashboard? What does management expect to see when they open it up?
  6. Is there a demand for raw data? If so, how can that info be seamlessly provided to management?

By reading these questions, you'll realize that the issues a data analyst face aren't limited to analytics alone but also computer systems. In a sense, you and your team are designing a new system to bring analytical insight to your viewers, and the design of such a system needs to be tight. Two statements that often causes my stress levels to peak are "The data is not right, something is amiss?", "These metrics are not meaningful, I need something I can use." This usually means that the solution you built is flawed and you misinterpreted the demands of your client. You have to walk yourself through your designs and figure out what went wrong and how to fix it. 

To quote a Principal Engineer from Amazon:"Your ideas can't be half-baked. You make an impassioned plea to architect your system, and your team does it, they are going to expect a payoff. If things get worse, you are in deep doo-doo. So it will take time and energy, on top of your existing duties to do deep designs and analysis." 

On top of what I mentioned, as a data analyst, you might also encounter: tools with missing features, broken software, no documentation, badly designed data structures, no data in your test environment, unclear design direction etc. Being mentally prepped and having a backup plan for dealing with all these issues will help you become a better analyst.
