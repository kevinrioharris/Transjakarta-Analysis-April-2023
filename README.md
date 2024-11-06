# TransJakarta Analysis April 2023

## Overview
**Project:** Analysis of Tap-In and Tap-Out Transactions for TransJakarta  
**Dataset:** `Transjakarta.csv` (April 2023)  

TransJakarta, Jakarta’s bus rapid transit (BRT) system, aims to deliver efficient and reliable public transport. Established in 2004, it now includes Mikrotrans services for areas beyond BRT reach, offering enhanced accessibility. This analysis provides insights into transaction data to support TransJakarta’s goal of streamlining operations, improving service quality, and promoting sustainable transit.

## Problem Statements
1. **Route Utilization:** Limited insights on tap-in and tap-out locations hinder the understanding of route demand and overcrowding.
2. **Demographic Accessibility:** Services may not be well-tailored for diverse passenger demographics.
3. **Service Reliability:** Lack of timing data affects the ability to assess punctuality, impacting customer satisfaction.

## Objectives
1. **Passenger Profiles:** Understand demographics to tailor services.
2. **High-Demand Routes:** Identify high-use routes and stops for better resource allocation.
3. **Operational Efficiency:** Utilize data to improve scheduling and reduce wait times.

---

## Dataset Overview
The dataset includes variables capturing key aspects of each transaction:

- **Passenger Data:** `transID`, `payCardID`, `payCardBank`, `payCardName`, `payCardSex`, `payCardBirthDate`
- **Route Information:** `corridorID`, `corridorName`, `direction`
- **Tap-In Details:** `tapInStops`, `tapInStopsName`, `tapInStopsLat`, `tapInStopsLon`, `stopStartSeq`, `tapInTime`
- **Tap-Out Details:** `tapOutStops`, `tapOutStopsName`, `tapOutStopsLat`, `tapOutStopsLon`, `stopEndSeq`, `tapOutTime`
- **Payment Information:** `payAmount`

---

## Recommendations Actions

### 1. Adjust Service Frequency
   - **Peak Hours (6:00 and 17:00):** Increase frequency to reduce overcrowding.
   - **Off-Peak Hours (9:00-16:00):** Decrease frequency to optimize costs.

### 2. Increase Tap-Out Awareness
   - **Awareness Campaigns:** Use posters and announcements to remind passengers to tap out.
   - **Social Media Engagement:** Share videos on Instagram and Facebook targeting adult and middle-aged passengers, emphasizing the benefits of tapping out.

### 3. Service Improvements by Age Group
   - **Adults & Middle-Aged Passengers:** Ensure reliable services during peak hours.
   - **Senior Passengers:** Enhance priority seating on high-demand routes, specifically on the Ragunan - Gelora Bung Karno corridor.

### 4. Retain Loyal Passengers
   - Maintain high service standards to keep **84.7%** of frequent users satisfied and encourage continued use.

---

## Data Processing Steps

### 1. Data Preprocessing and Cleaning
   - Addressed duplicates and handled missing values.

### 2. Exploratory Data Analysis (EDA)
   - Conducted analysis on demographics, route demand, and transaction timing to extract actionable insights.

---

## Steps to Run the Project

1. **Download the Dataset**  
   Download the `Transjakarta.csv` dataset and place it into a project folder.

2. **Set Up the Project Folder**  
   Create a new folder (e.g., `TransJakarta_Analysis`) and add the dataset and Jupyter Notebook (`TransJakarta_Analysis.ipynb`) to this folder.

3. **Install Required Libraries**  
   Ensure you have the following libraries installed. You can install them via pip if necessary:
