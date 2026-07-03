# Master Data

## What is Master Data?

Master data is the basic information required to execute a sales process in SAP S/4HANA.

For this project, we need two main types of master data:

1. Customer Master Data
2. Material Master Data

---

## Customer Master Data

### Customer Details

| Field | Value |
|---|---|
| Customer Name | Balaji Tiles & Sanitary |
| Customer Type | Dealer |
| City | Ahilyanagar |
| Country | India |
| Currency | INR |
| Sales Organization | BS01 |
| Distribution Channel | 10 - Dealer Sales |
| Division | 01 - Construction Chemicals |
| Payment Terms | 30 Days |

### Partner Functions

| Partner Function | Business Meaning |
|---|---|
| Sold-to Party | Customer who places the order |
| Ship-to Party | Location where goods are delivered |
| Bill-to Party | Customer who receives the invoice |
| Payer | Customer who makes the payment |

---

## Material Master Data

### Product Details

| Material Code | Product | Pack Size |
|---|---|---|
| BB-T1-20KG | Type 1 Tile Adhesive | 20 kg |
| BB-T2-20KG | Type 2 Tile Adhesive | 20 kg |
| BB-T3-20KG | Type 3 Tile Adhesive | 20 kg |
| BB-GR-01KG | Tile Grout | 1 kg |

---

## Material Used in This Project

The main material used in the Order-to-Cash scenario is:

**BB-T2-20KG - Type 2 Tile Adhesive, 20 kg**

The customer orders **100 bags** of this material.
