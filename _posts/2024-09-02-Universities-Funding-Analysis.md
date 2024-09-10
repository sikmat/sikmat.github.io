---
title: "Universities Funding Analysis"
date: 2024-09-02 00:00:00 -0700
image: assets/images/uni.png
categories: [Data Analytics]
tags: [data analytics, power bi, python, azure, cloud computing, sql]     # TAG names should always be lowercase
---
**End-to-End Data Engineering Project**

**Analysis of Funding Sources for South African Universities**

Funding is a critical component that influences the quality of education, research, and overall performance of universities. This analysis examines the funding structure of South African universities, focusing on the distribution of government funds, private income, and student fees. Understanding how these funding sources are allocated helps in assessing the financial health and sustainability of higher education institutions in South Africa.

**The Project**

Thank you to Nolubabalo Maxazana, Sibonelo Mhlongo, Thando Mandondo and Kopano Maluleke for their collaboration on this project! Our primary objective was to analyze the funding sources of South African universities to uncover trends and insights that can inform financial planning and policy-making. We concentrated on answering the following questions:

- How do government funds, private income, and student fees contribute to the total funding of universities?
- Which universities rely most heavily on government funding versus private income or student fees?
- How has the distribution of these funding sources evolved over time?
- What are the implications of these funding structures for the universities' financial sustainability?

**Key Insights**

Some of the key insights from our analysis include:

- **Funding Distribution by University:** Government funds contribute the most to university funding, with an average of 47.59%, followed by student fees at 32.81% and private income at 19.6%. However, some universities, like the University of South Africa, rely more heavily on student fees (35.03%) than others.
- **Trend Analysis:** Over the years, the reliance on government funding has generally increased, while the proportion of private income and student fees has seen a slight decline. This trend suggests a growing dependency on government support, which could impact the financial flexibility of universities.
- **University Comparisons:** Universities like Sol Plaatje and the University of Mpumalanga show a higher dependency on government funds, while others like the University of South Africa and Central University of Technology have a more balanced distribution between government funds and student fees.

**Tools Used**

The project leveraged a suite of Microsoft Azure tools to process and analyze the data:

- **Power BI:** For data visualization and creating interactive dashboards, with Direct Query for a live data connection.
- **DAX:** For data manipulation and aggregation.
- **Azure Data Factory** For initial Extraction, Transform and Load of data
- **Azure SQL Database** For storing data to be used with Azure resources
- **Azure Function App:** With Python Runtime Stack for executing serverless functions to process incoming data.
- **Azure Logic App:** To automate workflows between different Azure services and external applications.
- **Power Automate:** For creating automated workflows to trigger data processing and visualization tasks.

**The Data**

Our analysis focused on the following key areas:

- **Government Funds:** The portion of university funding that comes from government allocations.
- **Private Income:** Funding sourced from private donors, partnerships, and other non-governmental sources.
- **Student Fees:** Revenue generated from tuition and other fees paid by students.
- **Funding Trends Over Time:** Analysis of how the distribution of these funding sources has changed from 2010 to 2011.
- **University-Wise Funding Distribution:** Comparison of how different universities balance their funding sources.

**Summary**

Our analysis revealed that most South African universities are heavily reliant on government funding, which makes up nearly half of their total income. However, there is significant variation among institutions, with some relying more on student fees or private income. The trend over the years suggests an increasing dependency on government support, raising questions about the long-term sustainability of this funding model.

**Application**

This analysis has several practical applications. Universities can use these insights to diversify their funding sources, reducing their dependency on government funds. Policymakers can also use this data to assess the financial needs of different institutions and allocate resources more effectively. Additionally, understanding these trends can help universities plan for future financial stability, ensuring they can continue to provide high-quality education and research opportunities.

- [Live Power BI Visualization](<https://app.powerbi.com/reportEmbed?reportId=4334c8e6-b136-46ab-b945-776b77008733&autoAuth=true&ctid=a3f14f21-237f-4028-b978-425eb768a716>)
- [Download PDF version of the Power Bi Visualization](<https://github.com/sikmat/Universities-Funding-Analysis/blob/main/University%20Funding%20Analysis.pdf>)
- [GitHub Project Link](<https://github.com/sikmat/Universities-Funding-Analysis>)
