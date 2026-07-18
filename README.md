# Comprehensive Real Estate & Commission Management ERP 🏢

A fully integrated Real Estate and Property Management solution built within Odoo, engineered to handle the complete property lifecycle from project initiation to final contracting, alongside a complex, automated commission engine.

### 🎯 The Challenge
Real estate operations often suffer from disconnected systems. Tracking unit availability across massive projects, managing the delicate sales pipeline from Expression of Interest (EOI) to final contracts, and accurately calculating dynamic, multi-tiered sales commissions are frequent pain points that lead to revenue leakage and operational bottlenecks.

### 💡 The Solution
I architected a tailored Real Estate suite that centralizes property inventory, orchestrates the entire sales journey, and completely automates commission calculations. This module ensures 100% visibility over unit statuses and financial obligations, empowering the sales and accounting teams to work in perfect sync.

### 🔄 The Complete Real Estate Cycle (Workflow)
The system manages a robust and automated workflow encompassing:

1. **Property & Inventory Management:**
   * **Projects -> Buildings -> Units:** A structured hierarchy to manage massive developments.
   * Real-time tracking of unit statuses (e.g., Available, EOI Placed, Reserved, Contracted, Sold).

2. **The Sales Lifecycle:**
   * **Expression of Interest (EOI):** Capturing initial client interest and securing priority without fully locking the unit, including EOI payment tracking.
   * **Reservations (Bookings):** Upgrading an EOI to a formal reservation, locking the unit from the inventory to prevent double-booking, and generating down-payment invoices.
   * **Contracts:** Converting the reservation into a legally binding contract, outlining payment plans, installments, and handover dates.

3. **Advanced Commission Engine:**
   * Solved complex commission calculation issues by building an automated algorithmic engine.
   * Supports tiered commissions, multi-agent splits, and external broker percentages.
   * Commissions are automatically calculated and triggered based on specific lifecycle events (e.g., upon contract signature or installment collection), seamlessly integrating with Odoo Accounting.

### 🛠️ Technical Highlights
* **Complex Data Modeling:** Engineered a robust relational database structure linking Units, Customers, Contracts, and Accounting Journals.
* **Dynamic State Management:** Developed automated workflows where a unit's availability status is dynamically updated based on the progression of EOIs and Reservations.
* **Financial Automation:** Bridged the gap between sales actions and accounting using advanced Python logic to ensure error-free commission payouts.

---

### 📸 Project Showcase & Workflows

*(Below are screenshots demonstrating the UI/UX and system flow)*

**1. Property & Unit Inventory Dashboard**
![Property Hierarchy](https://github.com/ahmedqasas/Real-state/blob/main/Screenshot%202026-07-18%20222541.png)
![Property Hierarchy](https://github.com/ahmedqasas/Real-state/blob/main/Screenshot%202026-07-18%20222555.png)
![Property Hierarchy](https://github.com/ahmedqasas/Real-state/blob/main/Screenshot%202026-07-18%20222607.png)
![Property Hierarchy](https://github.com/ahmedqasas/Real-state/blob/main/Screenshot%202026-07-18%20222615.png)
![Property Hierarchy](https://github.com/ahmedqasas/Real-state/blob/main/Screenshot%202026-07-18%20222627.png)
![Property Hierarchy](https://github.com/ahmedqasas/Real-state/blob/main/Screenshot%202026-07-18%20222646.png)
*Visual representation of projects, buildings, and color-coded unit availability statuses.*

**2. EOI & Reservation Workflow**
![EOI and Reservation](https://github.com/ahmedqasas/Real-state/blob/main/Screenshot%202026-07-18%20222656.png)
![EOI and Reservation](https://github.com/ahmedqasas/Real-state/blob/main/Screenshot%202026-07-18%20222707.png)
![EOI and Reservation](https://github.com/ahmedqasas/Real-state/blob/main/Screenshot%202026-07-18%20222719.png)
*The seamless transition from an Expression of Interest to a locked Reservation.*

**3. Automated Commission Engine**
![Commission Calculation](https://github.com/ahmedqasas/Real-state/blob/main/Screenshot%202026-07-18%20222729.png)
![Commission Calculation](https://github.com/ahmedqasas/Real-state/blob/main/Screenshot%202026-07-18%20222737.png)
*Custom views showing automated commission splits for sales agents and brokers.*


---
*🔒 **Note:** Source code is intentionally omitted to protect proprietary business logic. This repository serves to demonstrate workflow architecture, complex mathematical automations, and industry-specific ERP tailoring.*
