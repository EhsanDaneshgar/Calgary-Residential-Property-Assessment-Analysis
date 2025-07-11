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
  - **Centre**, **South**, **North**, **Northwest**, **Northeast**, **East**, **West** and **Select All**
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
- One card now shows that the **most expensive residential property in Calgary** is valued at **$248 million**, based on the most recent assessment data.
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

This dashboard is powered by real open data provided by the **City of Calgary**.

- **Total Property Assessed Value** (Main dataset used in visuals):  
  https://data.calgary.ca/Government/Total-Property-Assessed-Value/dmd8-bmxh

Other datasets (API and CSV) were sourced from Calgary’s Open Data Portal and include:
- City Planning Sectors (API)
- Ward Boundaries (API)
- Community Populations
- Residential Structure Assessments


---

## ⚙️ Tools Used

- Microsoft Power BI Desktop
- City of Calgary Open Data
- DAX & Visual-Level Filters

---

## 📫 Contact

**Ehsan Daneshgar**  
📍 Calgary, AB  
📧 [e.daneshgar@gmail.com] 
🔗 [https://www.linkedin.com/in/ehsan-daneshgar/]

---

## 💡 Future Enhancements

- Add year-over-year trends of property assessments
- Include exportable insights (PDF or Excel)
- Add slicers for community or postal code

## 🧱 Notes  
- The report reflects the most recent dataset available as of July 10, 2025.  
- All values are in Canadian dollars (CAD).  
- This dashboard is intended for educational and analytical purposes.
- Relationships were created manually; **Auto-detect relationships** was disabled to ensure control over joins.





