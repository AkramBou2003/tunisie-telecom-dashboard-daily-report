# Tunisia Telecom – Business Data Visualization Platform

**Summer internship project | Documentation-only portfolio repository**

## Overview

During a summer internship at Tunisia Telecom, I contributed to a web application that enables company employees to consult business indicators through dashboards and charts.

The application provides separate administrator and employee interfaces. The administrator manages employee accounts and imports daily CSV reports. Before storage in the SQL database, the imported data goes through recurring preparation operations: removing unnecessary columns, splitting selected columns, combining selected columns, and applying calculations.

Employees can consult visualizations related to business activity, including telephone recharges and mobile data indicators, and use the information when preparing reports.

## Main features

### Administrator interface
- Employee account management (Create, Read, Update, Delete).
- Daily CSV report upload through an import action.
- Data preparation and transformation during the import workflow.
- Storage of prepared data in the SQL database.

### Employee interface
- Access to business dashboards and charts.
- Consultation of indicators such as telephone recharges and mobile data.
- Use of visualized information to support report preparation.

## Data workflow

1. The administrator uploads a daily CSV report.
2. The application prepares the data using recurring transformations.
3. Prepared data is inserted into the SQL database.
4. Dashboards use the updated data.

See [the architecture overview](docs/application-architecture.md) and [the feature description](docs/features.md).

## Technology stack

- **Frontend:** HTML, CSS, JavaScript
- **Backend:** PHP, Symfony
- **Database:** SQL
- **Data visualization:** Chart.js, Highcharts
- **Data input:** CSV files

## Repository contents

This repository contains public-facing project documentation only. It does not contain the application's source code, internal company data, real CSV reports, credentials, or proprietary documents.

## Confidentiality

This project was completed in a professional internship context. The implementation and company information are not published here. This repository describes the project at a high level without disclosing confidential material. Confirm that publication of this description and technology list complies with your internship agreement and company policies.
