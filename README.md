# Airbnb_BuenosAires
# Airbnb Market Analysis in Buenos Aires: Legal Compliance and Host Profiles 🇦🇷

## Project Description
This project analyzes the short-term rental ecosystem in the Autonomous City of Buenos Aires (CABA) through the lens of municipal regulatory compliance. The primary goal was to transform raw data into an interactive dashboard to identify the legal status of each property listed on Airbnb, revealing that the majority of hosts are corporations and over 99% operate without the legally required license.

## Tools used
* **Power BI**: Interactive dashboard creation and data modeling.
* **Power Query (M)**: ETL (Extract, Transform, and Load) process.
* **GitHub**: Version control and documentation.

## ETL Process (Cleaning)

Given the nature of the data (sourced from Inside Airbnb), the following cleaning tasks were performed to ensure analysis quality:

* **Null Treatment**: Management of missing reviews and descriptions.
* **Price Normalization**: Data type conversion and cleaning of special characters ($).
* **Outlier Filtering**: Removal of records with unrealistic prices to prevent average bias.
* **Geocoding**: Validation of neighborhoods and coordinates within Buenos Aires.
* **Host Classification**: Identification and segmentation between private individuals and companies/professional hosts based on the number of listed properties.

## Key Visualizations
>![Vista general del dashboard](Images/Contexto.png)
![KPIs de cumplimiento legal](Images/Cumplimiento.png)

1. **Heat Map**: Geographic distribution of properties by neighborhood (Palermo, Recoleta, etc.) with segmentation by legal status.
2. **Legal Compliance KPIs**:
   - % of properties without a license (~99%).
   - % of properties with a valid license.
   - Total number of properties analyzed.
3. **Host Profiles**: Comparative analysis between private hosts vs. companies/multi-property owners, highlighting market concentration among professional actors.
4. **Property Type Analysis**: Distribution between entire apartments, private rooms, and shared rooms.

## Repository Structure
* `/Data`: Contains representative samples of the original datasets (due to GitHub size restrictions).
* `/Images`: Screenshots of the Power BI dashboard.
* `Airbnb_BuenosAires.pdf`: Main report file in PDF format.
* `README.md`: Project documentation.
  
## Project Download
Due to the size of the data model (200MB), the Power BI file is hosted externally:

> [!IMPORTANT]
> [**Descargar archivo .pbix desde Google Drive**](https://drive.google.com/file/d/16HSG8nj0PzLDLIp5Er_dp1nfVMwqmWLH/view?usp=sharing)

---
**Daniel** | *Data Analyst | MSc Big Data Science (UNAV) | AWS Certified Cloud Practitioner*
