# Azure data engineering
Ingesting on-premise data and transforming it using Azure Data Factory, Databricks and analysing and reporting using Synapse and PowerBI

In this project the aim is to engineer the data present on the on-premises databases for generating insights and creating reports using the power of distributed computing using a cloud provider. There is a lot of data that is structured and exists in a database that is located on-premises. The quantity of data may be too large to be able to be transformed as required using the available compute power on-premises. Also, setting up infrastructure may not always be feasible as it requires planning, time and money and thus increases the lead time. Also, the infrastructure may become outdated or unnecessary in the near future. So, moving to cloud is the easiest way to achieve the desired results without much overhead.

In this case, the on-premises database is SQL server and I have used the publicly available AdventureWorksLT2017 database for this purpose. The reason for using this is, it is lightweight and helps control the costs incurred and to showcase the process rather than the computing power. The size of the Dataset in real life situation would be much larger and the architecture used in this project would still be able to handle it very efficiently. The high-level architecture diagram is as below.

![image](https://github.com/DataCounsel/Azure-Data-Engineering/assets/71335870/4193068d-e8f4-4396-9893-ac4283373ab2)

