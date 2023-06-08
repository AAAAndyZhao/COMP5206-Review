# Week6 Enhancing business intelligence using big data and analytics

## 1 Business decision

* Decision
  * A choice among two or more alternatives that individuals and groups make

## 2 Decision Making Process

* Three phases in decision making
  * Intelligence Phase
    * Examine a situation and identify and define the problem or opportunity
  * Design Phase
    * Construct a model for the situation
      * Making assumptions that simplify the reality
      * Expressing the relationships among all the relevant variables
    * Validate the model by using test data
  * Choice Phase
    * Select a solution or course of action that seems best suited to resolve the problem

## 3 Decision Support Framework

* Problem Structure
  1. Structured
     * Routine and repetitive problems for which standard solutions exist
     * Standardized procedures for carrying out the three phases in the decision-making process
  2. Semi-structured
     * Only some of the decision process phases are structured
  3. Unstructured
     * Complex problems for which there are no cut-and-dried solutions
     * No standardized procedures for carrying out the three phases in the decision-making process
* Nature of Decisions
  1. Operational
     * Executing specific tasks efficiently and effectively
  2. Managerial
     * Acquiring and using resources efficiently in accomplishing organizational goals
  3. Strategic
     * Long-term goals and polices for growth and resource allocation

## 4 Decision Matrix

| | Operational Control | Management Control | Strategic Planning | IS Support |
| --- | --- | --- | --- | --- |
| Structured | Accounts receivable | Budget analysis | | MIS, statistical models (management science, financial, etc.) |
| Semi-structured | Protection scheduling, inventory control | Credit evaluation, budget preparation, plan layout, project scheduling, reward system design | Building a new plant, mergers and acquisitions, planning (productm, quality, assurance, compensation, etc.) | Decision support systems, business intelligence |
| Unstructured | | Negotiating, recruiting an executive, buying hardware, lobbying | New technology development, product R&D, social responsibility planning | Decision support systems, expert systems, enterprise resource planning, neural networks, business intelligence, big data |

## 5 Business Intelligence (BI)

* The use of information systems to gather and analyze information from internal and external sources in order to make better business decisions

## 6 Business Intelligence Architecture

## 7 Data Warehouse and Data Marts

* Extraction, Transformation, Load (ETL)
  * The process of integrating data into a data mart or warehouse

### 7.1 Characteristics of Data Warehouse and Data Mart

* Organized by business dimension or subject
  * Data are organized by subject (e.g., by customer, vendor, product, price level, region, etc.)
  * Transactional systems: data are organized by process (e.g., order entry, inventory control, accounts receivable, etc.)
* Support online analytical processing (OLAP)
  * Online Analytical Processing (OLAP): support decision makers in the analysis of accumulated data
  * Online Transaction Processing (OLTP): support business transactions processing in a speedy and efficient manner
* Integrated
  * Data are collected from multiple systems and then integrated around subjects
* Time variant
  * Maintain historical data (i.e., data that include time as a variable)
  * Transactional systems: maintain only recent data
* Nonvolatile
  * Users cannot change or update the data
* Multidimensional
  * Uses multidimensional data structure
  * Relational databases: store data in two-dimensional tables

### 7.2 Relational Databases

### 7.3 Multidimensional Data Structure

## 8 Business Intelligence Applications

* For Analysis
  * Decision Support Systems
  * OnLine Analytical Processing (OLAP)
  * Data Mining
* For Presentation
  * Dashboard

## 9 Decision Support Systems (DSS)

* BI systems that combine models and data in an attempt to solve semi-structured and some unstructured problems with extensive user involvement
* Employ mathematical models
  * Simplified representations, or abstractions, of reality
* Capabilities
  * Sensitivity Analysis
    * The study of impact that changes in one or more parts of a decision-making model have on other parts
  * What-if Analysis
    * Attempts to predict the impact of a change in the assumptions (input data) on the proposed solution
  * Goal-Seeking Analysis
    * Attempts to calculate the value of the inputs necessary to achieve a desired level of output

### 9.1 Architecture of a DSS

* Input
  * Data
  * Models
  * Data Entry and Data Manipulation
* Process
  * Decision Support System Programs
  * Interactive Processing of Data and Models Examples:
    * Simulations
    * Optimization
    * Forecasting
* Output
  * Graphical Reports
  * Textual Reports
  * Feedback to System Operator

## 10 OnLine Analytical Processing (OLAP)

* A set of capabilities for “slicing and dicing” data using dimensions and measures associated with the data
  * Measures (Facts)
    * Values or numbers the user wants to analyze (e.g. sales)
    * “What” you want to see
  * Dimensions
    * Provide a way to summarize the data (e.g. region, time, product)
    * “How” you want to see
  * OLAP Cube
    * Data structure allowing for multiple dimensions to be added to a traditional two-dimensional table
    * Can have any number of dimensions
  * Analyzing the data on subsets of the dimensions is referred to as slicing and dicing
    * Dimensions
      * Product type
      * Region
      * Time
  * To enable the analysis of data at more or less detailed levels, the dimensions are organized as hierarchies, which allow for
    * Drill down
    * Roll up

## 11 Data Mining

* The process of searching for valuable business information in a large database, data warehouse, or data mart
  * Search for patterns, trends, or rules that are hidden in the data
* Two basic operations
  * Predicting trends and behaviors
  * Identifying previous unknown patterns
* Applications
  * Classification
  * Estimation
  * Association Discovery
  * Sequence Discovery
  * Clustering
  * Text and Web Mining

### 11.1 Data Mining for Classification

* Classification
  * Assignment of a newly presented object to one of a set of predefined classes
    * Used when groups are known
* Applications
  * Identifying potential customers (prospects)
  * Classifying credit applicants as low, medium, or high risk
  * Spotting fraudulent insurance claims

### 11.2 Data Mining for Estimation

* Estimation
  * Comes up with a value for some unknown continuous variable (e.g. income, order size, credit card balance) given some input data
* Applications
  * Estimating the lifetime value of a customer
  * Estimating the probability that someone will respond to a marketing promotion
  * Determining which customers will leave within the next 6 months

### 11.3 Data Mining for Clustering

* Grouping related records together on the basis of having similar values for attributes (e.g. age groups, income levels, etc.)
  * Used when groups are unknown
* Applications
  * Targeting certain groups of customers in marketing campaigns
  * New product development

### 11.4 Data Mining for Association Discovery

* Find associations or correlations among sets of items (e.g. items typically purchased together)
  * E.g., Market basket analysis
* Applications
  * Redesign the store’s layout and optimize the customers’ “navigational path” though the store
  * Product recommendations / cross-selling / bundling

## 12 Text Mining

* The application of large-scale analysis of non-numeric data, symbols, or text
* Applications
  * Analyze email text to block spam
  * Analyze customer text comments
  * Identify documents of interest to users with specific profiles
  * Filter and match resumes to job postings by human resources

## 13 Web Mining

* Web Content Mining
  * Analyze the content data (text, image, audio, etc.) available in web documents
    * E.g., Sentiment analysis on customer reviews
* Web Structure Mining
  * Analyze the underlying link (node and connection) structure of web documents
    * E.g., Link analysis on web pages and hyperlinks
    * E.g., Social network analysis on social relationships in a network
* Web Usage Mining
  * Analyze web server logs to discover useful patterns of web user behavior
    * E.g., Analysis on clickstream data

## 14 Sentiment Analysis

* The use of natural language processing, text analysis and computational linguistics to identify and extract subjective information in source materials.

## 15 Link Analysis

* A data-analysis technique used to evaluate relationships (connections) between nodes
* PageRank
  * Algorithm used by Google Search to rank websites in their search engine

## 16 Dashboard

* A BI application that provides rapid access to timely information and direct access to management reports
  * User friendly
  * Supported by graphics
  * Enables managers to examine exception reports and drill down into detailed data
* Report

| Report/Query | Description | Example |
| --- | --- | --- |
| Scheduled Reports | Reports produced at predefined interval-daily, weekly, or monthly - to support routine decisions | Daily Sales Register by Type |
| Key-indicator Reports | Reports that provide a summary of critical information on a recuring schedule | Year-End Sales by Item: Top 20 as of 12/31/2018 |
| Exception Reports | Reports that highlight situations that are out of the normal range | Items Temporarily Out of Stock as of 12/31/2018 |
| Drill-down reports | Reports that provide greater detail, so as to help analyze why a key indicator is not at an appropriate level or why an exception occurred | Absenteeism Drill Down |
| Ad hoc Query and Analysis | Queries answering unplanned information requests to support a nonroutine decision; typically not saved to be run again |  |

## 17 Class exercise – IBM Business Intelligence

* Explore the IBM’s BI Business Intelligence (https://www.ibm.com/au-en/analytics/business-intelligence) site and respond to the following questions:
* Q1: How would you describe BI in terms of its emerging capabilities?

| Room No | Your group response |
| --- | --- |
| 4 | BI tools allow users to access various data types, from historical to current, both third-part and in-house, also semi-structured data and unstructured data. With BI, users are able to analyze and examine the information, derive and gain insights from it, and presenting it in a very user-friendly views such as reports and dashboards. With their capabilities, organizations are able to make better decisions, take informed actions and implement more efficient business process. Users are offered applications to help them gain actionable information at every stage of the process, including applications for data preparation, analysis, data visualization, reporting, and collaboration for use on premises, at the desktop, in cloud and away from the office via mobile capability |
| 2 | Real-Time analysis, lots of BI systems have capabilities which allow users to analyze their organization’s data in real-time, which means these organizations can make decisions more quickly. Big data gives organisations alot more information which with the right tools can be used to make better, more informed strategic plans |
| 6 | NLP allows users to interact with BI systems using natural language queries, making data analysis more accessible and user-friendly. Cloud-based BI platforms enables organizations to store an dnanalyze data more efficiently drive data to improve product quality, customer interactions and process improvements. By providing an accurate picture of the business at a specific point in time, BI provides an organization with the means to design a business strategy based on factual data |
| 5 | Self-Service Analytics: IBM Cognos Analytics allows users to explore and visualize data on their own without requiring assistance from IT or data professionals. Real-time Analytics: IBM Cognos Analytics can process and analyze data in real-time, enabling businesses to make informed decisions quickly and respond to changing conditions as they occur. |
| 3 | As BI is the emerging capabilities and have certain benefits such as:It supports enterprise decision-making by collecting and analysing internal and external information and data. Connect different warehouse
| 7 | BI takes business data and presents it to the user in the form of specific views such as dashboards and charts.The user can analyze the different data in these views to get the actual situation of the business. Data visualisation: It allows you to quickly build tables or ICONS that visually and clearly convey information to decision makers. |
| 8 | By providing an accurate picture of the business at a specific point in time, BI provides an organisation with the means to design a business strategy based on factual data. Allocate resources intelligently to increase return on investment. Analyse customer preferences and locate potential customers. Continuous improvement of business operations. Monitor activities with partners and suppliers to improve the supply chain. |
| 9 | Allows intuitive interface for complex calculation and processing of data of different formats in real time. BI is incorporating AI and ML to conduct data analysis, pattern analysis and generating predictive decision. |
| 10 | BI is software that allows business analysts to visualise and understand big sets of data by providing different slicing and dicing tools in addition to visualisations tools. This then allows analysts to drive business decisions. Some of the emerging capabilities are the use of AI to summarise and understand better the data and incorporation of third party data sources to internal analysis tools. |
| 11 | Real-time data processing: IBM BI tools integrate capabilities to process and analyse real-time data which enables users to make decisions based on the most up-to-date information. Big Data: Vast structured and unstructured data collected from various sources enables businesses to make decisions based on more comprehensive information. The data is presented to the user in a visual way such as charts and graphs. It also allows users to compare existing data with previous data to figure out the state of the market. |
| 12 | Responsiveness. The BI can ingest real-time business data to help users analyse the data. Large volume. The BI can process large amounts of data concurrently. Flexibilities. The BI can process different types of data. |
| 13 | It connects to a wide variety of data systems and data sets, then provides deep analysis to help users to identify hidden relationships and patterns in their data. Then it presents answers in informative and compelling data visualisations. And it provides side-by-side comparisons of data under different scenarios, and lots of features for users to explore more of the data. BI has been developing rapidly, and ​​it accelerates the ability of enterprises to analyse their data and gain insights at a deep level. BI provides past and current insights into the business and the means to design a business strategy based on factual data. |
| 14 | Some newer business intelligence solutions can extract and ingest raw data directly using technology such as Hadoop, but data warehouses are still the data source of choice in many cases. A data warehouse aggregates data from multiple data sources into one central system to support business analytics and reporting. Business intelligence software queries the warehouse and presents the results to the user in the form of reports, charts and maps. 1.Connecting to a wide variety of different data systems and data sets including databases and spreadsheets. 2.Providing deep analysis, helping users uncover hidden relationships and patterns in their data. 3.Presenting answers in informative and compelling data visualisations like reports, maps, charts and graphs. 4.Enabling side-by-side comparisons of data under different scenarios. 5.Providing drill-down, drill-up and drill-through features, enabling users to investigate different levels of data. |
| 15 | Connect different data warehouses, support deep analysis, let the data visualise and it is the process of gathering, analysing, and visualising data to help businesses make informed decisions. |
| 17 | BI has been one of the most emerging technologies in the past few years. Players like Microsoft have entered into this technology and are providing software support. Without BI, organizations can't readily take advantage of data-driven decision-making. BI improves decision making. |
| 18 | BI can collect and allow users to access different data,provide users with a way to examine data and identify problems, and improve business. Also,BI can process large amounts of data and provide accurate information data. |
| 19 | The Business Intelligence is a software trans business data to reports that are friendly to users. BI is a newer way to respond users’ feedback. |
| 20 | BI is a software that provides users a user-friendly form of data including reports or charts. It also helps users to analyse the data and gain the insights of how business performs. With these forms of data, decision-making can also be improved. |
| 21 | Provide support for enterprise decision-making by collecting and analysing internal and external information and data. BI can analyse and process data in real time, allowing business to respond to market change instantly, and can make decisions flexibly. |
| 22 | Real time analysis of big data. Use AI and ML to promote the ability to automate and streamline complex tasks. Can use to drive data to improve product quality, customer interactions and process improvements |
| 23 | Business Intelligence could access different types of data and gain useful information based on analysis. It offers multidimensional queries for data discovery. |

* Q2: How do IBM’s BI solutions work in operations? Write your response here:

```
Room No
Your group response
10
IBM Planning Analytics can be used to “Automate planning, budgeting, forecasting and analysis processes.” This allows businesses to gain a competitive advantage by predicting user behavior and adjusting to it as well as reducing operation costs that come from misplanning and misbudgetting.
IBM Cognos Analytics helps you monitor data that your business is producing. This centralizes all the metrics in one place so important decision makers in the business can gain important knowledge about the direction and performance of the business while having confidence in the data.
IBM SPSS Modeler uses AI and machine learning that helps businesses uncover difficult to discover patterns in the data as well as forecast performance in the market.
3
empowers an organization to derive a factual data-driven business strategy by presenting a precise presentation of the business operations and it’s flaws and modification those are required as a organisation. 
2
IBM Cognos Analytics Solution uses AI to assist with data preparation and exploration. This is then used to generate reports and deliver predictive models.
7
IBM Planning Analytics is auto,  it can automate planning, budgeting, forecasting and analysis processes. it also goes beyond spreadsheets to create efficiency and remove manual steps. It Costs less time and produces more stuff.
Collect different types of business data and process and monitor these data in real time
8
Advanced BI and analytics systems may integrate artificial intelligence (AI) and machine learning to automate and streamline complex tasks. These capabilities further accelerate the ability of enterprises to analyze their data and gain insights at a deep level.
15
Use OLAP to support multi-dimensional query. And it uses advanced analytics and data visualization tools to help businesses gather insights from their data and make informed decisions. They can be integrated with existing systems and customized to meet specific business needs.
6
Using AI and machine learning resulting in optimize operations and make data-driven decisions.




11
It needs the support of the database, through the call of different time periods of data, and then the data analysis and comparison, the user can get in front of the market.

IBM BI tools can help users find hidden relationships in big data by providing deep analysis.

Data visualizations: presenting answers in forms of reports, maps, charts and graphs

Providing drill-down, drill-up and drill-through features, enabling users to investigate different levels of data
12
IBM Planning Analytics automates planning, budgeting, forecasting and analysis processes and removes manual steps. It can greatly improve working efficiency.
IBM Cognos Analytics takes advantage of the single analytics solution across the entire organization to confidently monitor, explore and share insights from data.
IBM SPSS Modeler uses predictive analytics to help users uncover data patterns, gain accurate insights and improve decision making.
13
1. IBM Planning Analytics. “Automate the planning, budgeting, forecasting and analysis process. Go beyond spreadsheets to create efficiencies and eliminate manual steps. ” This solution lets users create concrete ideas about their business and help them to be much more prepared for the market. 
2. IBM Cognos Analytics.Leverage this single analytics solution to confidently monitor, explore and share insights from your data. If it’s not from Cognos, it doesn’t count’
3. IBM SPSS Modeler.It is a leading visual data science and machine learning (ML) solution designed to help enterprises accelerate time to value by speeding up operational tasks for data scientists.


21
1.IBM’s BI can collect and integrate data from different data sources.
2.Real-time processing and monitoring of data.
3.Analyze and visualize the collected data, allowing users to understand the data more intuitively.


20
BI queries the data warehouse and presents the results in user-friendly form including reports or charts. Moreover, Bi applies the OLAP engine to support multidimensional queries, which reduces the difficulty of complex and predictive analyse.
23
The consistency of information and calculations that uses to drive data to enhance users interactions and promote product quality.
17
IBM’s BI empowers an organization to devise a factual data-driven business strategy by presenting a precise snapshot of the business operations at a particular moment. 




19


9


4
BI systems show the data more clearly and make it easier to predict the tendency, which improves the working efficiency and strategic decision making.


```