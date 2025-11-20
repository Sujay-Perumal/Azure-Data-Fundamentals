# ☁️ Azure Cloud & Data Governance Portfolio Summary

This README outlines the key concepts and strategic tasks covered in the Data Technician Workbook focusing on **Cloud Computing**, **Microsoft Azure Services**, and **Data Governance**.

The content demonstrates theoretical knowledge and practical application for planning a **modern, compliant cloud data environment**.

---

## 1. 🌐 Cloud Computing Fundamentals

This section defines the core concepts and delivery models essential for understanding and utilizing cloud technology.

---

### **Benefits of Cloud Computing**

Cloud computing enables businesses and individuals to access powerful computing resources over the internet without needing physical infrastructure.

| **Benefit**       | **Description** |
|------------------|-----------------|
| **Cost Reduction** | Eliminates large upfront capital expenditures on hardware and infrastructure. |
| **Scalability**    | Allows resources (storage, compute) to be easily scaled up or down based on demand. |
| **Flexibility**    | Supports remote work, real-time services, and rapid deployment of applications. |

---

### **Service Models**

Cloud services are categorized by the level of management provided by the vendor versus the user.

| **Model** | **Description** | **Example** | **User Management Focus** |
|----------|-----------------|-------------|----------------------------|
| **IaaS** | Infrastructure as a Service. Provides basic computing infrastructure (servers, storage, networks). | Azure Virtual Machines | Operating System, Applications, Data |
| **PaaS** | Platform as a Service. Provides hardware and operating systems, allowing developers to focus on application deployment. | Azure App Service | Applications, Data |
| **SaaS** | Software as a Service. Provides fully managed applications over the internet. | Microsoft 365, Gmail | User Access, Data |

---

## 2. 🛡️ Data Governance and Regulations

This section covers the legal and strategic measures necessary for secure and compliant data handling, particularly for data moving to the cloud.

---

### **Key Data Laws**

| **Law** | **Focus** | **Key Requirement** |
|---------|-----------|---------------------|
| **GDPR** | General Data Protection Regulation (EU/UK) | Requires consent, transparency, and the right to be forgotten for processing personal data. |
| **Data Protection Act 2018 (UK)** | UK implementation of GDPR | Reinforces data protection principles and outlines obligations for data controllers and processors. |

---

### **Data Strategy and Modelling**

- **Data Types & Modelling:** Determine whether data should be structured, semi-structured, or unstructured based on business needs.  
- **Data Storage Formats:** Select appropriate Azure storage formats (e.g., relational databases for structured data, blob storage for unstructured files).

---

## 3. ☁️ Azure Service Recommendations

Based on typical business requirements (transactional systems, large-scale analytics, scalable storage), the following Azure services are recommended:

---

### **Azure Services Overview**

| **Azure Service** | **Purpose** | **Use Case** |
|-------------------|-------------|--------------|
| **Azure SQL Database** | Relational Database (PaaS) | Storing transactional data (sales, customer records) requiring high reliability and structure. |
| **Azure Synapse Analytics** | Data Warehousing & Analytics | Running complex queries and advanced analytics on very large datasets (Big Data). |
| **Azure Data Lake Storage** | Massive Storage for Big Data | Storing structured, semi-structured, and unstructured data (logs, backups, media) for long-term access and processing. |

---

### **Additional Considerations**

- **Backup & Disaster Recovery:** Use *Azure Backup* or *Azure Site Recovery* to ensure business continuity.  
- **Data Visualization:** Integrate *Power BI* to create dashboards with real-time business insights.  
- **Future Scalability:** Use Azure’s elastic scaling to support business growth and increasing data volumes.  

