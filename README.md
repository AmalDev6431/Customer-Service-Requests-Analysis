# Customer-Service-Requests-Analysis
Introduction:

The New York City 311 service plays a crucial role in providing citizens with access to various non-emergency government services and information. Each day, thousands of service requests are received, covering a wide range of issues from noise complaints to plumbing problems. These requests are forwarded to relevant agencies, who address and close them after resolution.
Problem Objective:

The objective of this analysis is to perform a comprehensive data analysis of the New York City 311 service requests. We will focus on data wrangling techniques to understand patterns and visualize major complaint types. Additionally, we will examine the relationship between complaint types, service requests, and locations. Our goal is to draw meaningful insights from the data through visualization and statistical testing.

Analysis Tasks:

1.	Import and preprocess the 311 NYC service request data.
2.	Convert 'Created Date' and 'Closed Date' columns to datetime datatype and create a new 'Request_Closing_Time' column to measure the elapsed time between request creation and closure.
3.	Visualize major complaint types and patterns using graphs and tables.
4.	Order complaint types based on the average 'Request_Closing_Time', grouped by different locations.
5.	Perform statistical tests to investigate: a) Whether the average response time across complaint types is similar or not (overall). b) If the type of complaint or service requested is related to the location.
	
Dataset Description:

The dataset contains various fields such as Unique Key, Created Date, Closed Date, Agency, Complaint Type, Location Type, Incident Zip, City, Borough, Latitude, Longitude, and more. These fields provide valuable information about each service request and its characteristics.

Conclusion:

The analysis of the New York City 311 service requests has allowed us to gain valuable insights into the patterns and trends of complaints. By leveraging data wrangling techniques and visualization, we have identified major complaint types and their relationships with response times and locations.
