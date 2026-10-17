# Week 02 — Feature Engineering Report

## Purchase Features
- delivery_delay_days: received date minus expected delivery date
- delivery_status: Early, On Time, Late, Not Received, or Unknown
- line_purchase_value: quantity multiplied by purchase line unit cost
- expected_lead_days: expected delivery date minus order date

## Sales Features
- line_sales_value: quantity multiplied by the selected sales unit price

## Stock and Inventory
Stock-related features should only be included after confirming
the meaning of ledger quantities and calculating a valid current
stock balance.

## Validation
Feature missing values and data types were checked.