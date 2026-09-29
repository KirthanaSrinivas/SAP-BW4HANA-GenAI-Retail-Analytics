# DTP Design

## DTP Name

`ZDTP_SALES`

## Purpose

The DTP is used to transfer retail sales data from the source into the target ADSO.

## Source

`retail_sales.csv`

## Transformation

`ZTR_SALES`

## Target

`ZADSO_SALES`

## Data Flow

```text
Source Data
    ↓
ZTR_SALES
    ↓
ZDTP_SALES
    ↓
ZADSO_SALES
