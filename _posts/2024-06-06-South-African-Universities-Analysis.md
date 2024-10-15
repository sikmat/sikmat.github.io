---
title: "South African Universities Analysis"
date: 2024-06-06 00:00:00 -0700
image: assets/images/Uni Analysis.png
categories: [Data Analytics]
tags: [data analytics, power bi, python]     # TAG names should always be lowercase
---

**Impact of University Enrollment and Graduation Rates on South Africa's Education Sector**

Understanding the trends in university enrollment and graduation rates is crucial for assessing the performance of South Africa’s higher education sector. These trends directly influence the country's workforce, economic growth, and social mobility. By examining data from 2009 to 2016, we aim to uncover patterns that can guide policy decisions and institutional improvements.

**The Project**

A big thank you to my team members, Anathi Jack, Anati Vato, Buhle Ngqonwa and Siba Njisane, whom I collaborated with on this project! Our goal was to analyze data from 2009 to 2016 and extract meaningful insights into South African university enrollment and graduation trends. We worked with a comprehensive dataset that included information on over 1 million students across various qualifications, provinces, and racial groups. Our project set out to answer the following questions:

1. Which qualifications saw the highest and lowest enrollment rates across different provinces?
2. What are the trends in student performance across different provinces?
3. What are the relationships between racial demographics and enrollment/graduation trends?
4. How have enrollment and graduation rates evolved over the years, and what patterns can be identified?


**Key Insights**

Here are some of the interesting points we uncovered during this project:

1. **Enrollment Trends**: Enrollment rates were highest in fields like Education and Business, while Science and Technology fields saw moderate to low enrollment rates.

2. **Graduation Rates**: Graduation rates varied significantly by qualification, with health sciences and engineering showing higher completion rates compared to other fields. Provinces like Gauteng and KwaZulu-Natal had higher overall graduation rates, likely due to better access to educational resources.

3. **Racial Disparities**: Our analysis revealed significant disparities in enrollment and graduation rates among different racial groups. While there has been some improvement over the years, historically disadvantaged groups still face challenges in accessing and completing higher education, particularly in fields like engineering and natural sciences.

4. **Provincial Performance**: Gauteng, Western Cape, and KwaZulu-Natal provinces consistently showed strong performance in both enrollment and graduation rates, while provinces like Limpopo and Eastern Cape lagged behind.

5. **Temporal Trends**: Over the analyzed period, we observed a steady increase in enrollment across most qualifications, with a corresponding but smaller increase in graduation rates. This suggests a growing demand for higher education in South Africa, but also highlights the need for improving student support systems to ensure higher completion rates.


**Tools Used**

We utilized the "South African University Data" dataset, which covers a broad range of academic and demographic information from 2009 to 2016. The data was analyzed using the following tools:

- **Power BI**: For data visualization and creating interactive dashboards that allowed us to explore trends across different dimensions.
- **Excel:** For preliminary data cleaning and aggregation.
- **DAX**: To build formulas and expressions for manipulating data on Power BI
- **SQL**: For querying the dataset and extracting relevant information for our analysis.

**The Data**

The dataset included the following key variables:

- **Enrollment by Qualification**: Number of students enrolled in different qualifications across provinces.
- **Graduation by Qualification**: Number of graduates in different qualifications across provinces.
- **Enrollment by Race**: Breakdown of enrollment numbers by racial group.
- **Success Rate**: Academic performance trends across different provinces.
- **Temporal Data**: Enrollment and graduation data from 2009 to 2016, allowing us to analyze trends over time.

**Summary**

Our analysis provided valuable insights into the state of higher education in South Africa, highlighting areas of strength as well as opportunities for improvement. By identifying the qualifications and provinces with the highest and lowest enrollment and graduation rates, we can inform educational policies aimed at promoting equity and access to quality education.

The predictive model we developed offers a tool for educational institutions and policymakers to anticipate future trends and make data-driven decisions about resource allocation and program development. While our model performed well, there is potential for further refinement with additional data and more sophisticated modeling techniques.

**Application**

This project has several practical applications:

- **Policy Development**: Our findings can inform policies aimed at increasing access to higher education and improving graduation rates, particularly for historically disadvantaged groups.
- **Resource Allocation**: Educational institutions can use our insights to allocate resources more effectively, focusing on areas with growing demand and addressing disparities in enrollment and graduation rates.
- **Student Support**: By understanding the factors that influence graduation rates, institutions can develop targeted support programs to help students complete their qualifications successfully.
- **Future Research**: Our predictive model can serve as a foundation for further research into enrollment and graduation trends, helping to forecast future educational needs in South Africa.

**Conclusion**

This project has provided a comprehensive analysis of South African university data, shedding light on critical trends and disparities in higher education. By leveraging the power of data analysis and predictive modeling, we can help shape the future of education in South Africa, ensuring that all students have the opportunity to succeed.

**Links to the report resources**

- [Download PDF version of the Power Bi Visualization](<https://github.com/sikmat/Universities-Analysis/blob/main/University%20Data%20Analysis.pdf>)
- [GitHub Project Link](<https://github.com/sikmat/Universities-Analysis>)

- [Live Power BI Visualization](<https://app.powerbi.com/reportEmbed?reportId=c3647d31-d43e-4f1b-aaf1-87b1cd30b3be&autoAuth=true&ctid=a3f14f21-237f-4028-b978-425eb768a716>)

<div style="display: flex; justify-content: flex-start;">
  <iframe title="Universities Analysis" width="900" height="541.25" 
          src="https://app.powerbi.com/reportEmbed?reportId=acdf2204-cdb2-44ee-bc9e-32a01115a200&autoAuth=true&ctid=a3f14f21-237f-4028-b978-425eb768a716" 
          frameborder="0" allowFullScreen="true">
  </iframe>
</div>
