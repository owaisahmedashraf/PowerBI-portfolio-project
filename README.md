# Departmental Stores Sales Dashboard
I used Power BI to come up with insights and suggestions to help the CEO make effective decisions
## This was the task I was required to do:
You are the Data Analyst for a Chain of Departmental stores. The CEO has asked you to make a weekly sales dashboard/report. There is no data pipeline/warehouse available as such. Weekly data is extracted using a data tool connected to the POS at every store. The senior assistant (Suleman) has extracted a number of files for you to add to your report/dashboard. Every week Suleman will send you this data and you will expected to update this dashboard and then send it to the CEO via a link or otherwise. 
1.	You have been asked to decide the tool to do this task, what are the pros and cons of pbi vs streamlit. What would you recommend to your CEO and why. Understand the scale of the business and the sales before answering this question.
2.	The CEO (Sumera) has told you that it is common practice to compare weekly data to the year before. For e.g Sumera wants to see how well Store 3, Dept 1 did in Week 20 this year as compared to Week 20 last year. She also wants to see bigger picture by store and department.
a.	Hint: A common way to do such comparison is via Indices, usually calculated as Current Sales/Previous sales * 100. If index is > 100 it shows growth, maybe the dashboard could show this as green
b.	YTD or Year To Date values also provide a good comparison to last year. It is simply the running total of Sales till the current week. It is worthwhile to compare this number by last year and take out an index
3.	Folder named All data contains all data till the current week
4.	Sumera wants to see big picture summary, for eg top 10 stores in the current week, top 10 depts in the current week. Assume our current week is 19th to 25th Oct 2012
a.	Try defining what top 10 stores should be based on, also think about the worst performing stores/departments
b.	Every week the manager of the 5 best performing stores in terms of Sales gets a commission, the CEO would like to see who these people are. Commission is 0.5% of Sales. The CEO would also like to see Year to Date Values for these commissions for the top 10.
5.	The CEO likes simple design and big numbers, layout availability on mobile will impress her. She absolutely dislikes clutter and dark themes
6.	Assume you are now in week of 26th Oct 2012, try refreshing the numbers on the dashboard with this new data and see how long it takes. Think about how long it would take you to refresh and recommend the CEO what to do about the org data. Make a case to convince Sumera about your recommendations. This data is in the folder called New week. 
# Solution
## Question 1
Answer: Given the scale of the business and the sales volume, it's crucial to select a tool that can handle 
large datasets efficiently, provide deep insights through interactive visualizations, and accommodate the 
iterative addition of new data. Let's evaluate Power BI and Streamlit based on these requirements.
Power BI
Pros:
• Scalability: Power BI can handle large datasets efficiently, especially when using Power BI Pro or 
Premium for enhanced data refresh rates and more storage.
• Integration: Seamless integration with other Microsoft products, such as Excel and Azure, which 
could be beneficial if your company already uses these tools.
• Visualization: Offers a wide range of visualization options that are easy to use for creating 
comprehensive dashboards.
• Collaboration: Power BI reports can be easily shared and published within the organization, 
including scheduled automatic updates.
Cons:
• Cost: While there is a free version, the Pro and Premium versions, which offer necessary 
capabilities for large-scale businesses, come with a subscription cost.
• Complexity: Some of the more advanced features have a steep learning curve.
Streamlit
Pros:
• Flexibility: Being Python-based, it offers vast flexibility in terms of data manipulation, analysis, 
and the ability to use the entire Python ecosystem.
• Development Speed: Quick to develop and deploy data applications, especially for data 
scientists and analysts familiar with Python.
• Cost-Effective: Streamlit itself is free, and you can host applications on various platforms, 
depending on your budget and requirements.
Cons:
• Scalability: While Streamlit is excellent for quick development, handling very large datasets 
efficiently may require additional engineering effort, such as optimizing the app or managing the 
server infrastructure.
• Visualization and UI Polish: While Streamlit supports many charting libraries, the out-of-the-box 
visualization options are not as extensive or as polished as those in Power BI.
Recommendation
Given the large scale of your business and the emphasis on weekly sales reporting across various stores 
and departments, Power BI would likely be the more suitable choice. Its robust data handling 
capabilities, integration with existing business systems, and extensive visualization options make it a 
powerful tool for creating comprehensive dashboards. Power BI's ability to manage large datasets 
efficiently and its native integration with Microsoft's ecosystem (potentially including your POS system) 
can provide the scalability and reliability needed for your business.
Moreover, the collaborative and sharing features of Power BI align well with the need to regularly update 
and distribute reports to the CEO and other stakeholders. While Streamlit offers great flexibility and 
development speed, the requirements for scalability, data integration, and polished visualization lean 
towards Power BI as the better tool for this specific scenario.
However, it's important to consider the subscription cost of Power BI Pro or Premium as part of your 
decision. If cost is a significant concern, starting with Power BI's free version to validate the approach 
before scaling up could be a prudent strategy.

## Question 2
![powerbi1](https://github.com/owaisahmedashraf/PowerBI-portfolio-project/assets/62153426/8bd3cf7c-0e13-402d-9559-13032fa8ee5e)

## Question 3 and 4
![powerbi 2](https://github.com/owaisahmedashraf/PowerBI-portfolio-project/assets/62153426/504710ef-a67a-471d-97c9-72b64d0239b9)

## Question 5.
Answer: Reflecting on how I approached creating the Power BI dashboard to align with CEO Sumera's preferences for simplicity, big numbers, mobile accessibility, and her aversion to clutter and dark themes, I made several deliberate choices:
Clean and Simple Layout
I opted for a minimalist design, carefully arranging the visual components to ensure the dashboard remains uncluttered. I prioritized whitespace and used it strategically to make the dashboard feel more open and less crowded, ensuring that the data presented is the focal point.
Emphasis on Key Metrics
Understanding the importance of key metrics, I chose large, bold fonts to make these figures stand out. This approach was intended to capture attention immediately and make the information easily digestible at a glance, which I believe is critical for effective decision-making.
Light and Neutral Color Scheme
I selected a light and neutral color palette for the dashboard's background and elements to adhere to Sumera's dislike for dark themes. I used color judiciously to highlight important data points and indicators, such as using green to denote positive growth and red for areas needing attention, ensuring these visual cues are clear and intuitive.
Clear Visualizations
I incorporated simple yet effective charts and graphs to represent the data. My choice of visualizations—bar charts, line graphs, and pie charts—was guided by the need for clarity and ease of interpretation. I made sure these visualizations were not overly complex and included clear labels for immediate comprehension.
Prioritizing Mobile Accessibility
Given the emphasis on mobile accessibility, I utilized Power BI's mobile layout view to arrange visuals in a way that they're easily navigable and readable on smaller screens. This ensures that Sumera can access the dashboard and derive insights no matter where she is, directly from her mobile device.
Interactive Elements for Depth
While maintaining a simple overall design, I introduced interactive elements like filters and drill-down capabilities. This allows for a deeper exploration of the data without overcomplicating the initial view. It's a balance between simplicity and functionality, enabling Sumera to delve into specifics as needed.
Regular Updates and Iteration
I ensured the dashboard is regularly updated with the latest data, automating data refreshes wherever possible. This commitment to providing the most current insights is crucial for timely and informed decision-making.
Soliciting Feedback
Finally, after presenting the dashboard to Sumera, I sought her feedback on its layout, design, and usability, especially on mobile devices. Her insights are invaluable, and I plan to use them for continuous improvement of the dashboard, ensuring it remains an effective tool for our decision-making process.
By adhering to these principles, I aimed to create a Power BI dashboard that not only meets Sumera's requirements but also enhances our ability to make informed decisions quickly and efficiently, leveraging the latest sales data across our departmental stores chain.

## Question 6.
Answer: When updating the dashboard with the new week's data, covering the period starting 26th October 2012, the process involves a few steps that directly impact the overall time needed for the refresh. This includes moving the new data from the "New week" folder to the “All week” folder, ensuring it's correctly formatted and aligned with the existing dataset structure, and then performing the actual data refresh in Power BI. The entire process, depending on the dataset size and complexity, could take anywhere from a few minutes to potentially longer if manual adjustments or data transformations are required. In this case it was only a few minutes
Recommendations for Organizational Data Management:
To maintain and even improve the efficiency of our weekly updates, I propose a few strategic recommendations for managing our organizational data:
1.	Automated Data Collection: Implementing a more automated data collection process from our POS systems could significantly reduce the time needed to prepare and load the data each week. Automation ensures data consistency and accuracy, reducing manual errors.
2.	Centralized Data Storage: Establishing a centralized data storage solution, such as a cloud-based data warehouse, would allow for more streamlined data management. This centralization supports better data governance, security, and accessibility across the organization.
3.	Scheduled Refreshes: Utilizing Power BI's scheduled refresh feature can automate the dashboard update process. By setting up specific times for the data to be refreshed automatically, we ensure that the dashboard always displays the most current data without manual intervention.
4.	Data Quality Checks: Implementing regular data quality checks can help identify and correct any issues before they impact the dashboard. This proactive approach keeps our data reliable and trustworthy.


Making the Case:
By adopting these recommendations, we're not just streamlining our weekly dashboard updates. We're setting a foundation for a more data-driven culture within our organization. Automated data collection and centralized storage reduce manual workload and improve data accuracy. Scheduled refreshes ensure our insights are always current, empowering us to make swift, informed decisions. Finally, regular data quality checks maintain the integrity of our insights, building trust and confidence in our data-driven strategies. These steps will further solidify our competitive edge, enabling us to respond more agilely to market changes and opportunities.

