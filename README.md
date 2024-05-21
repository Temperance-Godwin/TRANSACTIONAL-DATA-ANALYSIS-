# TRANSACTIONAL-DATA-ANALYSIS-

**_8-Week SQL Challenge, Case Study #4 by Danny Ma_**

This case study centers on analyzing and interpreting the data generated from various transactions within an organization for understanding business operations, customer behavior, financial performance, and operational efficiency

![](DataBank.png)

## INTRODUCTION

There is a new innovation in the financial industry called Neo-Banks: new aged digital-only banks without physical branches.

Danny thought that there should be some sort of intersection between these new-age banks, cryptocurrency, and the data world…so he decided to launch a new initiative — Data Bank!

Data Bank runs just like any other digital bank — but it isn’t only for banking activities, they also have the world’s most secure distributed data storage platform!

Customers are allocated cloud data storage limits which are directly linked to how much money they have in their accounts. There are a few interesting caveats that go with this business model, and this is where the Data Bank team need your help!

The management team at Data Bank wants to increase its total customer base — but also needs some help tracking just how much data storage their customers will need.

This case study is all about calculating metrics, and growth and helping the business analyze their data in a smart way to better forecast and plan for their future developments!

## ABOUT THE DATASET

The Data Bank team have prepared a data model for this case study as well as a few example rows from the complete dataset below to get you familiar with their tables.
1. Regions
2. Customer Nodes
3. Customer Transactions

## DATA MODELLING

![](EntityDiagram.png)

## TABLE 1: REGIONS

Just like popular cryptocurrency platforms — Data Bank is also run off a network of nodes where both money and data is stored across the globe. In a traditional banking sense — you can think of these nodes as bank branches or stores that exist around the world.

This regions table contains the region_id and their respective region_name values

![](Region.png)

## TABLE 2: CUSTOMER NODES
Customers are randomly distributed across the nodes according to their region — this also specifies exactly which node contains both their cash and data.

This random distribution changes frequently to reduce the risk of hackers getting into Data Bank’s system and stealing customer’s money and data!

Below is a sample of the top 10 rows of the data_bank.customer_nodes

![](CustomerNodes.png)

## TABLE 3: CUSTOMER TRANSACTIONS
This table stores all customer deposits, withdrawals, and purchases using their Data Bank debit card.

![](CustomerTransactions.png)
















