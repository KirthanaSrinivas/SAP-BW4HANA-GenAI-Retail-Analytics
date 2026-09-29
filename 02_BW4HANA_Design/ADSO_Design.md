# ADSO Design

## ADSO Name

`ZADSO_SALES`

## Purpose

The ADSO is used as the central data storage object for retail sales transactions.

It stores sales transaction details received from the source data.

## Fields

| Field | Type | Description | Key |
|---|---|---|---|
| SALES_ID | Character | Unique sales transaction | Yes |
| SALES_DATE | Date | Date of sale | No |
| CUSTOMER_ID | Character | Customer identifier | No |
| PRODUCT | Character | Product name | No |
| CATEGORY | Character | Product category | No |
| CITY | Character | Sales city | No |
| QUANTITY | Integer | Number of units sold | No |
| SALES_AMOUNT | Decimal | Total sales amount | No |

## Data Flow

```text
Source CSV
    ↓
Transformation
    ↓
DTP
    ↓
ZADSO_SALES
