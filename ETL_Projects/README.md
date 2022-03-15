# ETL (Extract,Transform, Load)

---

#### ETL, which stands for extract, transform and load, is a data integration process that combines data from multiple data sources into a single, consistent data store that is loaded into a data warehouse or other target system.

![DataWareHouse](https://1.cms.s81c.com/sites/default/files/2021-01-06/ICLH_Diagram_Batch_02_15-DataWarehouse-WHITEBG.png)

## How ETL works

The easiest way to understand how ETL works is to understand what happens in each step of the process.

#### 1. Extract

During data extraction, raw data is copied or exported from source locations to a staging area. Data management teams can extract data from a variety of data sources, which can be structured or unstructured. Those sources include but are not limited to:

- SQL or NoSQL servers
- CRM and ERP systems
- Flat files
- Email
- Web pages

#### 2. Transform

In the staging area, the raw data undergoes data processing. Here, the data is transformed and consolidated for its intended analytical use case. This phase can involve the following tasks:

Filtering, cleansing, de-duplicating, validating, and authenticating the data.

Performing calculations, translations, or summarizations based on the raw data. This can include changing row and column headers for consistency, converting currencies or other units of measurement, editing text strings, and more.
Conducting audits to ensure data quality and compliance
Removing, encrypting, or protecting data governed by industry or governmental regulators
Formatting the data into tables or joined tables to match the schema of the target data warehouse.

#### 3. Load

In this last step, the transformed data is moved from the staging area into a target data warehouse. Typically, this involves an initial loading of all data, followed by periodic loading of incremental data changes and, less often, full refreshes to erase and replace data in the warehouse. For most organizations that use ETL, the process is automated, well-defined, continuous and batch-driven. Typically, ETL takes place during off-hours when traffic on the source systems and the data warehouse is at its lowest.
