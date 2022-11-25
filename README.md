# Azure Data Explorer in a Day (Preview)

Welcome to a One Day, Hands on learning on Azure Data Explorer. Synapse Customer Success Engineering team is delighted to present this challenge based, discover by doing experience divided into 2 labs of 4 Hours each, a total of 8 hours.


## After the Labs, you'll better understand how to
- Setup Free Azure Data Explorer cluster and database
- Ingest data into ADX database
- Run Powerful KQL queries to explore the data
- Manage ADX cluster and DB using control commands and policies
- Visualize data in ADX Dashboards


 [**Lab 1: Cluster Creation, Data Ingestion and Exploration**](https://github.com/Azure/ADX-in-a-Day-Lab1)
This Lab will focus on enabling the participants to Create a free ADX cluster, and ingest data into the cluster - One click ingestion of historic data , update policy to perform ETL and write some KQL queries. 

 [**Lab 2: Advanced KQL, Policies, and Visualization**](https://github.com/Azure/ADX-in-a-Day-Lab2)
This Lab will focus on enabling the participants to write Kusto queries to explore and analyze the data stored in the clusters. Participants will also create cool visualizations. It is recommended to complete the Lab 1 before beginning with Lab 2.

---
Earn a digital badge! In order to receive the ADX-in-Day completion digital badge, you will need to complete the challenges marked with 🎓 in each Lab. Please submit the KQL queries/commands using the answer sheet found at the beginning of Lab. </br>

**Placeholder : "ADX in a Day" Digital Badge

---

### What is Data Explorer and when is it a good fit?

Data Explorer is a fully managed, high-performance, big data analytics platform that makes it easy to analyze high volumes of data in near real time. The Azure Data Explorer toolbox gives you an end-to-end solution for data ingestion, query, visualization, and management.

By analyzing structured, semi-structured, and unstructured data across time series, and by using Machine Learning, Azure Data Explorer makes it simple to extract key insights, spot patterns and trends, and create forecasting models. Azure Data Explorer is scalable, secure, robust, and enterprise-ready, and is useful for log analytics, time series analytics, IoT, and general-purpose exploratory analytics.

**Note**: Data Explorer exists as both a Standalone offering (Azure Data Explorer) and part of Synapse (Synapse Data Explorer). All the content will apply to both these offerings (will be referred to as 'ADX') without any change.

ADX capabilities are extended by other services built on its powerful query language, including [Azure Monitor logs](https://docs.microsoft.com/en-us/azure/log-analytics/), [Application Insights](https://docs.microsoft.com/en-us/azure/application-insights/), [Time Series Insights](https://docs.microsoft.com/en-us/azure/time-series-insights/), and [Microsoft Defender for Endpoint](https://docs.microsoft.com/en-us/microsoft-365/security/defender-endpoint/microsoft-defender-endpoint)


<img src="/assets/images/DX_Pic.png" width=800>


### Scenario 
Contoso is a multinational Steel equipment (Chairs, rods, pipes, kitchenware) manufacturing company. They store all their operational logs in Aure data explorer to perform exploration , forecast and anomaly dection that supports maintainance and performance of their manufacturing plants. Recently they found certain issues with their plant telemetry and approached you to analyse their data. You need to help them by writing KQL queries on 1 GB of contoso's operational logs and build a Dashboard. 

### Pre-requisites
- Either a Microsoft account (MSA) or an Azure Active Directory (AAD) identity. This will be used to create free cluster.

### How to start with ADX
Generally, when starting with Azure Data Explorer, you will follow the following steps (ADX-In-A-Day Labs will cover all these steps):
1. **Create a free ADX cluster**: To use Azure Data Explorer you first create a free cluster. An Azure Data Explorer cluster is the most basic unit.
2. **Create database**: Each cluster has one or more databases in that cluster. Each Azure Data Explorer cluster can hold up to 10,000 databases and each database up to 10,000 tables. 
3. **Ingest data**: Load data into database tables so that you can run queries against it. Azure Data Explorer supports several ingestion methods.
4. **Query data**: Azure Data Explorer uses the Kusto Query Language, which is an expressive, intuitive, and highly productive query language. It offers a smooth transition from simple one-liners to complex data processing scripts, and supports querying structured, semi-structured, and unstructured (text search) data. Use the web application to run, review, and share queries and results. You can also send queries programmatically (using an SDK) or to a REST API endpoint. 
5. **Visualize results**: Use different visual displays of your data in the native Azure Data Explorer Dashboards. You can also display your results using connectors to some of the leading visualization services, such as Power BI and Grafana. 

### Ready to go? Click on the below links to start the challenges
- [**Lab 1: Cluster Creation, Data Ingestion and Exploration**](https://github.com/Azure/ADX-in-a-Day-Lab1)

- [**Lab 2: Advanced KQL, Policies, and Visualization**](https://github.com/Azure/ADX-in-a-Day-Lab2)

