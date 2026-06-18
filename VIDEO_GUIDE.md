# 🎥 UPI Dashboard Video Presentation & Script Guide

This guide is designed to help you record a highly professional, 4-minute screen-recording walkthrough of your **UPI Transaction Dashboard** using Loom, Zoom, or any screen recorder.

---

## ⏱️ Video Presentation Blueprint

```mermaid
gantt
    title Video Presentation Timeline (4 Minutes)
    dateFormat  m:s
    axisFormat %M:%S
    section Section
    Introduction & Overview   :active, 0:00, 0:45
    Page 1: Executive Summary : 0:45, 1:45
    Page 2: Transaction Analysis : 1:45, 2:35
    Page 3: Fraud Intelligence : 2:35, 3:25
    Future Scope & Conclusion : 3:25, 4:00
```

---

## 🎬 Word-for-Word Speaker Script

### Part 1: Introduction & Overview (0:00 – 0:45)
**Visual Setup**: Show your browser or Power BI desktop with **Page 1 (Executive Summary)** loaded. Have your webcam bubble visible in the corner.

> "Hello everyone, my name is **Simaran Shaikh**, a B.Com Financial Accounting student from Government College of Arts, Science and Commerce, Goa. 
> 
> Over the last 4 weeks, I participated in the **Microsoft Elevate × AICTE Power BI Internship** under the Emerging Technologies Track. Today, I am excited to present my Capstone project: the **UPI Transaction Analytics Dashboard**.
> 
> The objective of this project was to analyze **2,50,000 raw UPI transaction records** from 2024. The raw dataset contained zero pre-built metrics or insights. Using Power Query for data cleansing and writing custom DAX measures from scratch, I transformed these transaction logs into an interactive 3-page business intelligence tool. Let's walk through it."

---

### Part 2: Page 1 — Executive Summary Walkthrough (0:45 – 1:45)
**Visual Action**: Click and highlight the KPI cards at the top of Page 1 as you mention them. Hover over the Monthly charts.

> "Starting here on Page 1, the **Executive Summary** gives us a high-level look at the overall health of our UPI dataset. 
> 
> We processed a total of **250,000 transactions**, representing a cumulative transaction value of **327.94 Million Rupees**, with an average transaction size of **1.31K Rupees**. Out of these, **237,624 transactions** were successful, resulting in an overall success rate of **95.05%**, while **480 transactions** were flagged as fraudulent.
> 
> Looking at our monthly trend lines for volume and value, we see clear seasonality. Our **Peak Month by Volume** was **May 2024** with **21,333 transactions**, while the **Highest Value Month** was **July**, peaking at **28.1 Million Rupees**. Conversely, **February** represented our lowest transactional volume. 
> 
> We also designed a dynamic **Month-on-Month Growth** card using time-intelligence DAX functions, which shows a positive growth momentum peaking at **9%**."

---

### Part 3: Page 2 — Transaction Analysis (1:45 – 2:35)
**Visual Action**: Switch to **Page 2** in Power BI. Click on the **26-35** age group slicer to show how the visuals cross-filter, then click it again to reset.

> "Moving on to Page 2: **Transaction Analysis**. This page focuses on user demographics and transaction mediums. 
> 
> At the top, we have an **Age Group Slicer** synced across all pages. Notice how our bar chart highlights that the **26 to 35 age group** is the primary spender demographic, contributing a massive **116 Million Rupees** to the transaction volume.
> 
> On the geographic chart, **Maharashtra**, **Uttar Pradesh**, and **Karnataka** emerge as the clear leaders in transaction volume, indicating higher digital payment penetration.
> 
> On the right, our donut charts show that **Peer-to-Peer (P2P)** transactions dominate the ecosystem at **44.98%**, followed by **Peer-to-Merchant (P2M)** at **35.06%**. In terms of hardware, **Android** is the dominant platform at **75.2%**, and **4G networks** represent **60%** of the connectivity."

---

### Part 4: Page 3 — Fraud Intelligence (2:35 – 3:25)
**Visual Action**: Switch to **Page 3**. Hover over the Merchant combo chart and the Fraud by Transaction Type chart.

> "Next, let's look at Page 3: **Fraud Intelligence**, which is critical for risk management. 
> 
> We isolated the **480 fraud-flagged transactions** against a **Failed Transaction Rate of 5%**. 
> 
> Our geographic chart shows that **Maharashtra** and **Karnataka** don't just lead in volume — they also experience the highest number of fraud occurrences, which requires targeted security measures.
> 
> Looking at the **Transactions vs Fraud by Merchant** chart, we see that high-volume categories like **Grocery**, **Food**, and **Shopping** attract the highest frequency of fraud attempts.
> 
> Interestingly, the **Fraud by Transaction Type** breakdown reveals that **P2P (Peer-to-Peer)** transfers carry the highest fraud concentration with over **200 cases**, followed closely by **P2M**. This highlights that individual-to-individual transfers are the primary risk channel."

---

### Part 5: Future Scope & Conclusion (3:25 – 4:00)
**Visual Action**: Switch your PowerPoint slide to the **Future Scope** or **Conclusion** slide (or keep the dashboard open and look at the camera).

> "To conclude, this dashboard successfully turns raw data into actionable risk and demographic intelligence. 
> 
> For future scope, the dashboard could be expanded by:
> 1. Connecting a live API stream to replace the static CSV for **real-time transaction tracking**.
> 2. Integrating a **Machine Learning model** in Python to predict fraud probability in real time.
> 3. Implementing **Row-Level Security** so different partner banks can only view their own transaction data.
> 
> I want to express my gratitude to my mentor, **Vignesh Muthuvelan**, and the teams at **Microsoft**, **AICTE**, and **Edunet Foundation** for this incredible learning experience. Thank you!"

---

## 📹 Recording Checklist & Tips

### Before You Press Record:
- [ ] **Power BI Settings**: Open the report in Power BI Desktop and maximize it. Hide the fields and filters pane so the canvas is large and clean.
- [ ] **Loom Setup**: Make sure your microphone is clear, and your video bubble is visible in the bottom-left or bottom-right corner.
- [ ] **Practice Slices**: Test clicking the age group slicers to make sure they cross-filter smoothly.
- [ ] **Browser Tabs**: Close unrelated tabs so your PC doesn't lag during the recording.

### Presentation Best Practices:
* **Don't just read the screen**: The viewer can see the numbers. Focus on explaining *what the numbers mean* (e.g., *"the 26-35 age group is the primary driver of digital commerce"*).
* **Click to interact**: When talking about the 26-35 age group, click that option in the slicer! It shows the mentor that you actually built an interactive report.
* **Keep an enthusiastic tone**: Smile and speak clearly. You worked hard on this project — show your pride in the final results!
