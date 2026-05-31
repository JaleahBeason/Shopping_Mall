# Shopping Mall Database Application

A full-stack database application built for CS300 – Database Systems
at Bellarmine University. Implements a relational database system 
for managing a shopping mall with complete CRUD functionality and 
stored procedures, connected to a Python command-line interface.

## Tech Stack
- **Database:** MySQL
- **Backend:** Python (mysql-connector-python)
- **Concepts:** Relational modeling, stored procedures, 
CRUD operations, data integrity

## Database Schema
Tables: `Shopping_Mall`, `Retailer`, `Shop`, 
`Maintenance_Event`, `Income_Record`

## Features
- Add, update, and delete shops
- Execute stored procedures with IN/OUT parameters
- Query income summaries, discounts, and maintenance records
- Full separation of schema, data, and procedure files

## Stored Procedures
| Procedure | Description |
|-----------|-------------|
| `GetShopTotalIncome` | Returns total income for a shop |
| `GetShopsInMall` | Lists all shops in a given mall |
| `AddMaintenanceEvent` | Logs a new maintenance record |
| `GetMallIncomeSummary` | Summarizes income across all malls |
| `GetAverageDiscountForMall` | Calculates average discount per mall |

## Setup
1. Run `CS300_Project1_schema.sql` to create tables
2. Run `CS300_Project2_data.sql` to populate data
3. Run `CS300_Project2_procedures.sql` to load stored procedures
4. Update credentials in `db.py`
5. Run `python app.py`

## Skills Demonstrated
- Relational database design and normalization
- SQL stored procedures with IN/OUT parameters
- Python-to-MySQL integration
- CRUD application development
- Data modeling and schema planning
