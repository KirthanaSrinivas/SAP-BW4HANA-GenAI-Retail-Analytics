# Transformation Design

## Purpose

The Transformation defines how data from the source structure is mapped to the target ADSO.

## Source

`retail_sales.csv`

## Target

`ZADSO_SALES`

## Field Mapping

| Source Field | Target Field | Mapping |
|---|---|---|
| SALES_ID | SALES_ID | Direct |
| SALES_DATE | SALES_DATE | Direct |
| CUSTOMER_ID | CUSTOMER_ID | Direct |
| PRODUCT | PRODUCT | Direct |
| CATEGORY | CATEGORY | Direct |
| CITY | CITY | Direct |
| QUANTITY | QUANTITY | Direct |
| SALES_AMOUNT | SALES_AMOUNT | Direct |

## Transformation Logic

The initial transformation uses direct field-to-field mapping because the source data already follows the required target structure.

Additional transformation logic can be introduced later if required.
