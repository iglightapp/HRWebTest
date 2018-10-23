# HRWebTest

The attached mockup represents the desired UI outcome.

The user will select :

A. Date Range.
B. System to run against (Folder contains System.JSON file to retrieve systems list).

The raw data is organized in a single table with following fields:
- meter_id
- Timestamp
- value_type (KW / Flow)
- value
Each meter is linked to a system in the following way: 
System A consist of meters: 1001, 1002, 1003, 1004 
System B consist of meters: 2001, 2002, 2003, 2004

The overall data will be retrieved using the Folder API GetMetersData();


you will then have to filter data by selected system and date range.
and then present the following:

Raw -> Scalar that represent system efficiency overtime in raw aggregations.

Hourly -> Graph/Chart that represent system efficiency overtime in hourly aggregations.

Daily -> Grid that represent system efficiency overtime in daily aggregations.
