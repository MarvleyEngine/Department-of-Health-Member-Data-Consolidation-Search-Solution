# Department-of-Health-Member-Data-Consolidation-Search-Solution
The solution addresses the challenge of locating member information that is spread across multiple files and repositories by providing a single, searchable database and an interactive Power BI report.

This project delivers a centralized member information platform for the Ministry of Health by consolidating member data from multiple SharePoint sources into a Microsoft Fabric Warehouse.
Users can quickly search and retrieve member information using:

Staff ID
SSNIT Number

The result is improved accessibility, reduced manual searching, and more efficient member record management.

SharePoint Files
        │
        ▼
Microsoft Fabric Pipeline
        │
        ▼
Data Transformation
        │
        ▼
Fabric Warehouse
        │
        ▼
Power BI Search Dashboard



Business Problem

Member information was stored across multiple SharePoint files, making it difficult and time-consuming for users to locate records.

The organization required a centralized solution that would:

Consolidate member records into a single repository
Improve data consistency
Eliminate manual file searching
Provide a simple search interface for member lookup

<img width="1693" height="929" alt="image" src="https://github.com/user-attachments/assets/1c4a3b2c-9550-4b07-b45c-50ae8ccf8327" />

Key Features
Data Consolidation
Extracts member data from SharePoint files.
Combines records into a centralized Fabric Warehouse.
Maintains a single source of truth for member information.



Data Transformation
Basic transformations performed during ingestion include:
Column renaming and standardization
Data type conversions
Data quality checks
Removal of unnecessary fields



Member Search Dashboard
The Power BI report enables users to:
Search members using Staff ID
Search members using SSNIT Number
View member details instantly
Access a centralized view of records



**Technology Stack**
Technology	Purpose
Microsoft Fabric	-- Data Platform,
Fabric Data Pipeline	-- Data Ingestion,
Fabric Warehouse	-- Centralized Storage,
SharePoint	-- Source Data Repository,
Power BI	-- Reporting & Search Interface



**Project Workflow**
Member data files are maintained in SharePoint.
Fabric pipelines extract data from SharePoint.
Data is transformed and standardized.
Consolidated records are loaded into a Fabric Warehouse.
Power BI connects to the Warehouse.
Users search and retrieve member information using Staff ID or SSNIT Number.

**Dashboard Capabilities**
Search by Staff ID
Search by SSNIT Number
View member profile information
Fast access to consolidated member records
User-friendly reporting interface

**Business Benefits**
Centralized member data repository
Reduced time spent searching through files
Improved data accessibility
Better reporting and operational efficiency
Scalable Microsoft Fabric-based architecture

<img width="1316" height="731" alt="image" src="https://github.com/user-attachments/assets/74e3407b-85b2-4387-9afb-7d17449bc69f" />

<img width="868" height="696" alt="image" src="https://github.com/user-attachments/assets/a974a707-c44a-43d7-a136-872894a8a927" />


