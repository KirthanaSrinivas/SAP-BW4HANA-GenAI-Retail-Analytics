# InfoObjects

## Characteristics

| InfoObject | Description |
|---|---|
| ZSALES_ID | Unique sales transaction |
| ZSALES_DATE | Date of the sales transaction |
| ZCUSTOMER | Customer identifier |
| ZPRODUCT | Product name |
| ZCATEGORY | Product category |
| ZCITY | City where the sale occurred |

## Key Figures

| Key Figure | Description |
|---|---|
| ZQUANTITY | Number of units sold |
| ZSALES_AMOUNT | Total sales amount |

## Data Model

Characteristics are used to describe and group the sales data, while key figures represent the measurable values.

```text
Characteristics
    ├── ZSALES_DATE
    ├── ZCUSTOMER
    ├── ZPRODUCT
    ├── ZCATEGORY
    └── ZCITY

Key Figures
    ├── ZQUANTITY
    └── ZSALES_AMOUNT
