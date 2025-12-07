# Mock Network Proposal – Home Installation

## Overview
This repository contains a **mock network proposal** for a home installation designed to support secure, high-speed gaming and remote work. It demonstrates professional documentation, logical and physical design, hardware planning, and implementation scheduling.

---

## Contents
- **Executive Summary**: Overview, current situation, objectives, proposed system, and recommendations.
- **Logical Design**: VLANs, ISP details, router/switch setup, guest vs private networks.
- **Physical Design**: Room layout, cabling plan, port assignments, hardware resources.
- **Installation & Management**: Timeline, walkthroughs, punch list, and final delivery.
- **Cost Breakdown**: Hardware, labor, and recurring expenses.

---

## Technologies & Hardware
- **ISP**: Vyve Broadband (960 Mbps download, 50 Mbps upload)
- **Router/Modem**: eero 6 Pro Router, Hitron Coda-57 Modem
- **Switch**: TP-Link 24-Port Managed Gigabit Switch
- **Cabling**: Cat6a Plenum cabling
- **Rack & Accessories**: NavePoint 12U Wallmount Rack, patch panels, cable management
- **Power**: CyberPower UPS and surge protection

---

## Logical Design
- **Private VLAN (VLAN01)**: For client desktops, printer, and workstations.
- **Guest VLAN (VLAN02)**: For LAN parties and guest devices.
- **Wireless Networks**: Separate guest and private SSIDs, password-protected and encrypted.
- **Managed Switch**: Ports assigned to VLAN01 and VLAN02 for segmentation.

---

## Physical Layout
- Cat6a cabling run to bedrooms, office, and living room.
- Wall plates and jacks installed for wired access.
- Rack-mounted switch and patch panel for centralized management.
- Ports 3–9, 13, 15, 16 → VLAN02 (guest)  
- Ports 1, 2, 10–12, 14 → VLAN01 (private)

---

## Installation Timeline
- **June 3**: Preliminary walkthrough & hardware cost received  
- **June 4–9**: Order parts (cabling, wall plates, jacks, rack)  
- **June 12**: Parts delivered  
- **June 13–15**: Wire installation & termination  
- **June 15–16**: Rack installation & patch panel setup  
- **June 19**: Testing  
- **June 20**: Client walkthrough  
- **June 21**: Punch list  
- **June 22–23**: Final walkthrough & completion  

---

## Cost Breakdown
- **Parts**: $2,859.07  
- **Labor**: $2,000.00  
- **Total Proposal**: $4,859.07  
- **Recurring Expenses**: $114.98/month (ISP + router rental)
