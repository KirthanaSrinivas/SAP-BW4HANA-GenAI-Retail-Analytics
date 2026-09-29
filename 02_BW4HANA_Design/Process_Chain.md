# Process Chain Design

## Process Chain Name

`ZPC_SALES_LOAD`

## Purpose

The Process Chain represents the automated sequence used to load retail sales data into the ADSO.

## Process Flow

```text
Start
  ↓
Source Data
  ↓
Transformation
  ↓
DTP
  ↓
ZADSO_SALES
  ↓
End
