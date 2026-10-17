# Week 02 — Data Integration Report

## Objective
Integrate related cleaned datasets to prepare analytical datasets
for purchase, sales, and stock/inventory analysis.

## Integrated Datasets

### Purchase Orders
- Purchase Orders Header
- Purchase Orders Lines
- Suppliers
- Products
- Branches

### Sales Orders
- Sales Orders Header
- Sales Orders Lines
- Customers
- Products
- Branches

### Stock and Inventory
- Stock Ledger
- Inventory Master
- Products
- Branches

## Join Strategy
Left joins were used to retain records from each main dataset.
Join cardinality and unmatched keys were checked.

## Outputs
- purchase_orders_integrated.csv
- sales_orders_integrated.csv
- stock_inventory_integrated.csv

## Notes
Refer to the validation report for actual row counts, missing
values, duplicate checks, and unmatched join results.