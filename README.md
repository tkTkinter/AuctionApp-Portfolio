# AuctionApp v6: A Real-Time, Hardware-Integrated Auction System
**(Patent-Pending & Trademarked Technology)**

This repository provides a professional overview of the AuctionApp v6 system, a comprehensive solution I architected and engineered from concept to deployment.

---

### **Project Video (Live Demonstration)**

Here is a short clip of the system being used by customers during a live auction event.

[![AuctionApp Live Demo](https://img.youtube.com/vi/nS5rUdKLvtA/0.jpg)](https://www.youtube.com/watch?v=nS5rUdKLvtA)


---

### **System Overview**
The AuctionApp is a mission-critical desktop application that manages a fast-paced, live auction. It seamlessly integrates custom hardware, cloud services, and multiple user interfaces to provide a flawless experience for both the auctioneer and bidders.

### **Physical System & Prototypes**
The project involved designing and building the complete physical auction environment, including three full-scale, networked bidding tables.
<img width="1165" height="878" alt="finished 3 prototypes" src="https://github.com/user-attachments/assets/28b0f45d-b829-405a-8cc2-3edd3fe164d2" />
<img width="1168" height="885" alt="finished prototype table" src="https://github.com/user-attachments/assets/7f73f3cc-5007-46d0-b974-0655d05c47ad" />
<img width="651" height="860" alt="tiny prototype" src="https://github.com/user-attachments/assets/fd659a54-ebaf-4325-bab8-8f1293e62d85" />
<img width="672" height="894" alt="hardware integration" src="https://github.com/user-attachments/assets/0912f2c9-c7f9-415d-94df-e57b3429803b" />


### **Software Screenshots & Generated Outputs**
Here are some screenshots of the custom Human-Machine Interfaces (HMIs) and generated outputs I developed.
<img width="1370" height="810" alt="Dashboard screenshot" src="https://github.com/user-attachments/assets/05de9908-39ce-49fc-b359-22c07855fc08" />
![Bidderdisplay screenshot](https://github.com/user-attachments/assets/378bd138-bc62-40c9-acc2-fc9eb72dcb5a)
<img width="598" height="746" alt="1 invoice screenshot" src="https://github.com/user-attachments/assets/d0d26b92-e302-4cc2-afa6-65ac7c30cb1b" />
<img width="1093" height="721" alt="invoices preview screenshot" src="https://github.com/user-attachments/assets/0ff3ba87-54a5-4c0d-8718-22e3e781e941" />
![Item QR slip](https://github.com/user-attachments/assets/5e92874d-b9fe-430d-b38c-a27295ab96c5)

---

### **Technical Achievements**

* **Hardware Control System:** Engineered a robust hardware abstraction layer in Python to interface with a Phidgets I/O board, controlling a system of 9 bidder buzzers and 3 physical relays. Solved complex driver and permission issues specific to Apple Silicon (M1,M2) architecture to ensure millisecond-level real-time communication.

* **Advanced HMI Development:** Designed and built two synchronized Tkinter HMIs: a main dashboard for the auctioneer with full event control, and a secondary, full-screen display for bidders showing live updates on items, bids, and winners.

* **Automated Invoicing & QR Labeling:** Developed a robust module to auto-generate and print both detailed PDF invoices for end-of-session billing and instant QR-coded labels for item redemption, interfacing with two distinct printer types.

* **Cloud Data Pipeline:** Built a resilient data export pipeline using the Google Drive API to automatically generate and upload formatted Excel summaries and PDF invoices to a secure cloud folder with built-in retry logic.

* **Application Bundling & Deployment:** Successfully managed the entire build and deployment process using PyInstaller, resolving advanced, OS-specific bundling issues to create a stable, distributable application.
