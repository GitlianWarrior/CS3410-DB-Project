*ROUGH DRAFT: remove this line when finished*

# CS 3410: Database Project

Kennesaw State University
CS 3410: Introduction to Database Systems, Spring 2026
Instructor: Dr. North

------

## Executive Summary

TheGenericGameStore needs a relational database to replace its current system for inventory, sales, and customer records. The project builds a database to manage game inventory (titles, platform, price, stock), record sales with payment methods, and track customer profiles. The database uses IE Crow’s Foot ER notation in Microsoft Access, with tables like Game, Customer, Transaction, and ReceiptDetail linked via keys. A data dictionary and CRUD matrix define data roles, and Access queries/forms support tasks like recording sales and checking inventory.

------

## Step 1: Define the Client

- **Client**: TheGenericGameStore
  A retail game store selling physical/digital games. It uses paper/spreadsheets for inventory, sales, and customer data, which has led to consistent errors. The database replaces this with a system to:
  - Track inventory (titles, platform, price, stock).
  - Record sales (cash, credit).
  - Maintain customer profiles.
  - Generate sales/inventory/customer reports.

------

## Step 2: Identify Users

**Users**:

- **Store Staff** (Sales Associates, Inventory Managers)
  Handle day-to-day work such as adding new games to inventory, updating stock levels and conditions (e.g., “New” or “Used”), processing customer purchases, and recording payment methods.
- **Store Owner/Manager** (Administrator)
  Oversees the system by generating sales and inventory reports, monitoring stock levels for restocking, analyzing customer purchasing trends to guide marketing, and managing user access.
- **Customers** (Indirect Users)
  Do not use the database directly but benefit from accurate inventory, faster checkout, and purchase-history tracking.

------

## References

Kroenke, D. M., Auer, D. J., Vandenberg, S. L., & Yoder, R. C. (2022). *Database processing: Fundamentals, design, and implementation* (16th ed.). Pearson.
