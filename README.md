# Analysis of Udemy Courses Dataset

## Overview

In this report, I present a detailed analysis of the Udemy courses dataset using **Power BI** and **Power Query**. The analysis covers **3,672 records of courses** from **four subjects**: Business Finance, Graphic Design, Musical Instruments, and Web Design. The primary focus is on key metrics such as course enrollments, student engagement, completion rates, content duration, lecture counts, and pricing structures to identify optimization opportunities.

Using Power BI's powerful visualization capabilities, I have created various charts to illustrate the data, addressing specific questions and revealing important trends. These include examining the relationship between content duration and subscriber counts, observing fluctuations in course metrics over time, and comparing total revenue across different subjects. Additionally, I analyze the revenue distribution across different course levels and assess course popularity based on subscriber numbers.

The following sections summarize the findings from each chart, outlining the problems identified, insights gained, and analyses conducted. This overview is intended to offer a comprehensive understanding of Udemy’s course offerings and their performance, facilitating more informed decision-making.

## Analysis by Chart

### Revenue Breakdown by Course Level: From Beginner to Expert

- **Chart Title**: Sum of Revenue by Course Level - All Levels, Beginner, Intermediate, Expert
- **Chart Type**: Treemap
- **Problem**: How does revenue break down across different course levels, including beginner, intermediate, expert, and all levels?
- **Insight**: The treemap shows that courses categorized as "All Levels" bring in the most revenue, followed by Beginner and Intermediate courses. Expert courses contribute the least.
- **Analysis**: It is clear that courses labeled for All Levels appeal to a much broader audience, which is why they lead in revenue. This is because learners from various skill backgrounds can enroll, giving these courses a wider reach. Beginner-level courses also perform well, attracting a large number of people who are just starting out. Intermediate courses follow closely, catering to those who want to build on their foundation. Expert-level courses, while more niched down and more expensive, generate the least revenue simply because they appeal to a smaller, more specialized audience. This breakdown is helpful in deciding how to structure future courses—targeting broader audiences with All Levels courses can maximize reach, while specialized content can still bring in dedicated learners at the Expert level.

### Number of Courses by Subject and Year

- **Chart Title**: Annual Course Count by Subject
- **Chart Type**: Clustered Bar Chart
- **Problem**: How has the number of courses in each subject changed over the years?
- **Insight**: The bar chart reveals trends in the count of courses by subject over time, showing growth in some areas and stability or decline in others.
- **Analysis**: This trend analysis indicates how learner interests and market demands shift over time. Growing numbers suggest increasing popularity, while declines might point to decreasing interest or market saturation.

### Subject-wise Breakdown of Lectures and Content Duration

- **Chart Title**: Average Number of Lectures and Content Duration by Subject
- **Chart Type**: 100% Stacked Column Chart
- **Problem**: How do the average number of lectures and content duration vary by subject?
- **Insight**: This chart shows that subjects like web development and graphic design often have a higher average number of lectures and longer content durations compared to others.
- **Analysis**: The trend indicates that more complex subjects require more extensive content. Course creators should consider this when designing courses to ensure they meet the depth and breadth required for different topics.

### Average Content Duration and Number of Lectures by Month

- **Chart Title**: Trends in Course Content Duration Relative to Number of Subscribers
- **Chart Type**: Line Charts
- **Problem**: What trends can be observed in content duration and subscriber counts over time?
- **Insight**: The chart reveals fluctuations in total content duration and the number of subscribers across different years, with noticeable peaks and troughs.
- **Analysis**: These variations suggest changes in course structure and content delivery strategies over time. The peaks in content duration might indicate periods when more comprehensive or in-depth material was added, potentially in response to evolving industry trends or learner demands. Conversely, the troughs could reflect a shift toward more concise, focused content or adjustments based on feedback to improve user engagement. The correlation between subscriber growth and content duration suggests that longer or more detailed courses may attract more subscribers, but there are instances where subscriber growth happens even when content duration decreases, possibly due to factors like marketing efforts, partnerships, or the introduction of high-demand courses.

### Distribution of Paid vs. Free Courses

- **Chart Title**: Proportion of Paid and Free Courses
- **Chart Type**: Pie Chart
- **Problem**: What is the distribution between paid and free courses on Udemy?
- **Insight**: The pie chart illustrates the proportion of paid versus free courses, with a significant segment dedicated to paid courses.
- **Analysis**: This distribution highlights the platform’s revenue model and accessibility. A larger share of paid courses indicates a premium focus, while a balanced ratio suggests a commitment to offering both free and paid options.

### Average Price by Subject

- **Chart Title**: Total Course Price by Subject
- **Chart Type**: Funnel
- **Problem**: How do course prices compare across different subjects, and how does this influence revenue generation?
- **Insight**: The funnel chart reveals that Web Development courses have the highest total revenue, followed by Business Finance, Graphic Design, and Musical Instruments courses. This correlates with the order of revenue generation, with Web Development generating the most revenue and Musical Instruments generating the least.
- **Analysis**: The subjects with higher course prices, such as Web Development and Business Finance, reflect the high demand and specialized knowledge required in these fields. These subjects also generate the most revenue, likely due to their relevance in the job market and the need for professional development in these areas. On the other hand, Graphic Design and Musical Instruments have lower average prices, which may reflect broader accessibility or more casual learning interest, leading to lower revenue generation. This insight highlights the relationship between subject pricing, demand, and overall revenue, which is crucial for course creators aiming to optimize both pricing strategies and content offerings.

### Course Popularity by Number of Subscribers

- **Chart Title**: Course Popularity Based on Number of Subscribers
- **Chart Type**: Scroller
- **Problem**: Which courses have the most subscribers, and how does the total number of subscribers vary across different course titles?
- **Insight**: The scroller chart provides a dynamic visualization of the total number of subscribers per course. The chart highlights the most popular courses with the highest number of subscribers, offering a direct comparison across course titles.
- **Analysis**: The chart clearly shows that some courses, particularly those related to in-demand subjects like Web Development and Business Finance, attract significantly higher numbers of subscribers. Courses in subjects like Musical Instruments or Graphic Design, while still popular, tend to have fewer subscribers. This could be due to the broader market appeal and perceived job-related benefits of certain courses. The absolute values of subscribers provide insight into which topics learners are most interested in, allowing course creators and educators to focus on high-interest areas or identify opportunities for growth in less popular subjects.

## Tools and Skills

- **Tools Used**: Power Query and Power BI for dynamic reporting on course trends and learner behavior.
- **Skills**: Power BI, Data Modeling, Data Cleaning, Microsoft Power Query, DAX, Data Visualization.

## Recommendations

To maximize revenue and engagement on Udemy, course creators should prioritize offering more "All Levels" courses, as these appeal to a broader audience and generate the highest revenue. Pricing strategies should be optimized for high-demand subjects like Web Development and Business Finance, while shorter, concise content may work better for less complex subjects. Offering a mix of free and paid courses can attract new learners and convert them into paying customers over time. Monitoring shifts in learner interest and market trends is crucial for staying competitive, while leveraging popular courses in high-demand areas can help drive subscriber growth. Incorporating user feedback into course updates will ensure continued learner engagement and course success.

## Conclusion

This report provides a comprehensive view of the Udemy courses dataset, offering valuable insights into content duration, lecture counts, pricing, and the balance between paid and free courses. These findings can guide decisions on course development and pricing strategies, helping to better align offerings with learner needs and market trends.
