# SQL Triggers and Stored Procedure Overview

This document provides an overview of SQL triggers and a stored procedure implemented in various scenarios.

## Trigger Q1: trg_PreventDeleteCustomer

### Purpose:
Prevents deletion of a customer if they have placed at least one order.

## Trigger Q2: order_details_insert_trigger

### Purpose:
Ensures the quantity of a product ordered does not exceed the available quantity in the store.

## Trigger Q3: trg_CheckQuantity

### Purpose:
Checks if the updated quantity in OrderDetails exceeds the available quantity in Store after an update.

## Trigger Q4: prevent_delete_if_quantity_high

### Purpose:
Prevents deletion of an item if the quantity in store is more than a specified limit.

## Trigger Q5: insert_order_date

### Purpose:
Inserts the current date as the order date if the provided order date is not today.

## Trigger Q6: AfterInsertCustomer

### Purpose:
Ensures no null values are inserted into essential fields of the Customers table.

## Stored Procedure: CustomerSignup

### Purpose:
Inserts a new customer into the Customers table while performing validation checks.

---

This markdown file summarizes various SQL triggers and a stored procedure used in database scenarios to enforce data integrity, perform validations, and control data manipulation operations.
