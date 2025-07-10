# 🏘 Calgary Residential Property Assessment Analysis (Power BI)

This Power BI dashboard presents a geographic and value-based analysis of Calgary's residential property assessments. It allows users to visually explore the most expensive communities and the distribution of property values across city sectors.

---

## 📊 Key Visuals & Features

### 1. **Top 15 Most Expensive Communities Table**
- A static table displaying the top 15 Calgary communities ranked by the number of properties assessed in the **$2M–$5M** and **over $5M** categories.
- Highlights luxury residential zones such as **Upper Mount Royal**, **Elbow Park**, and **Beltline**.
- This table is independent and does not interact with filters or visuals.

### 2. **City Sector Filter (Tile Format)**
- Selectable buttons for sectors:
  - **Centre**, **South**, **North**, **Northwest**, **Northeast**, **East**, and **Select All**
- Dynamically filters the **bar chart** and **map** to focus on selected regions.

### 3. **Bar Chart: Property Count by Sector & Value Range**
- **X-axis:** City Sectors  
- **Y-axis:** Number of Residential Properties
- **Color-coded bars** show value categories:
  - Less than 300K
  - 300K to 1M
  - 1M to 2M
  - 2M to 5M
  - More than 5M

### 4. **Property Category Filter (Dropdown)**
- Allows users to isolate a specific value category to analyze across the map and chart.

### 5. **Interactive Map of Calgary**
- Shows Calgary communities divided by sector.
- Color-coded shading based on the number of high-value residential properties.
- Fully interactive with the sector and value filters.

### 6. **Card Visuals**
- When a **community** is selected on the map:
  - **Card 1:** Displays the name of the community.
  - **Card 2:** Shows the **highest assessed residential property** value in that community.
  - A stylized arrow guides attention from the name to the value card.

### 7. **City-wide Highlight**
- One card highlights that the **most expensive residential property in Calgary** is valued at **$221 million**.

---

## 🖼️ Sample Screenshots

| Dashboard Overview | Map & Chart Example |
|--------------------|---------------------|
| ![Overview](./images/dashboard_overview.png) | ![Map](./images/map_and_chart.png) |

---

## 📂 Project Files

| File | Description |
|------|-------------|
| `Calgary_Property_Assessment.pbix` | Power BI report file |
| `images/` | Contains screenshots for this README |
| *(optional)* `data/` | Source data from Calgary Open Data Portal (see below) |

---

## 🔍 Data Source

*(Coming soon — Ehsan will provide source information for the open dataset used)*  
This project is based on open public assessment data provided by the **City of Calgary**.

---

## ⚙️ Tools Used

- Microsoft Power BI Desktop
- City of Calgary Open Data
- DAX & Visual-Level Filters

---

## 📫 Contact

**Ehsan Daneshgar**  
📍 Calgary, AB  
📧 [your email here]  
🔗 [LinkedIn or GitHub profile]

---

## 💡 Future Enhancements

- Add year-over-year trends of property assessments
- Include exportable insights (PDF or Excel)
- Add slicers for community or postal code

---


