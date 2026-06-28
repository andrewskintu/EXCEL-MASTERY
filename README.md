DATA ISSUES IDENTIFIED
Missing values were identified and reviewed.
Duplicate records were checked and none was found.
Some data records contained Required Dates earlier than Order Dates
Suspicious values in pricing and discount were identified, reviewed and flagged.
There was data type inconsistencies in numeric columns.
CLEANING AND PREPARATION STEPS
Data types were corrected and standardized
Missing values were reviewed and handled using reasonable business assumptions
Records where the Required Date occurred before Order Dates were corrected.
Lead Time Days were created using the difference between CorrectedRequiredDate and Order Date.
Created Gross Revenue, Cost of Goods, Gross Profit and Margin Percentage calculated fields.
Created Month and Quarter dimensions from OrderDate.
Created Priceband categories for analysis.
Structured geographic hierachy using Region,Country and City.
Invalid RequiredDates were corrected using reasonable future-date assumptions.
Missing values were handled using available business context.
PriceBand were derived from product pricing ranges.

