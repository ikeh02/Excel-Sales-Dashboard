# Excel-Sales-Dashboard
![Dashboard Preview](dashboard_preview.png)
An executive-grade, interactive Sales &amp; Product Performance Dashboard built in Microsoft Excel. Features a clean, custom light UI design, multi-column slicers, and real-time visual analytics for tracking revenue, orders, unit returns, and sales representative performance.
# Sales & Product Performance Dashboard (Excel)

An executive-grade, minimalist dynamic financial dashboard built in Microsoft Excel. This interactive analytics project tracks multi-region revenue, order quantities, product movement, and return metrics using custom UI cards, advanced Pivot Tables, and interactive slicers.

---

## 📊 Executive Summary

This project transforms raw transactional data into an actionable visual dashboard designed for stakeholders to quickly identify top-performing product categories, track regional revenue contributions, and monitor key performance indicators (KPIs) in real time.

### Key Performance Indicators (KPIs)
* **Total Revenue:** ₦4,379,992.43
* **Total Quantity Sold:** 15,616 Units
* **Total Orders Processed:** 1,500
* **Total Quantity Returned:** 372 Units

---

## 🛠️ Key Technical Features & UI Design Architecture

* **Custom Light UI Aesthetics:** Built with custom rounded container cards (`#FFFFFF`) set against a light-gray canvas to eliminate gridline clutter and establish a modern, native web application feel.
* **Unified Brand Color Palette:** Customized using precise color codes:
  * **Primary (Dark Navy):** `RGB(30, 41, 59)`
  * **Accent (Electric Blue):** `RGB(30, 144, 255)`
  * **Highlight (Cyan/Light Tint):** `RGB(0, 196, 223)`
* **Dynamic Slicer Navigation:** Custom-styled, borderless button slicers for **Salesperson**, **Region**, and **Product** configured with multi-column grid layouts for seamless global filtering across all visuals.
* **Data Visualizations Included:**
  * **Product Flow Chart:** Category-by-category revenue distribution.
  * **Regional Revenue Distribution:** Donut chart breakdown showing regional sales proportions.
  * **Order Trend Line Chart:** Sequential order metrics mapped by sales personnel.
  * **Return Rate Analysis:** Proportional pie breakdown highlighting regional product returns.
  * **Sales Representative Performance:** Bar ranking identifying top revenue drivers (Bob, Alice, Frank, Carlos, Eva, Diana).
  * **Product Average Unit Price:** Dual-axis/grouped horizontal bar chart evaluating unit pricing against total volume.

---

## 📁 Repository Structure

```text
├── Data/
│   └── sales_performance_raw_data.xlsx    # Source data tables
├── Dashboards/
│   └── Sales_Product_Performance.xlsx    # Master Excel file with dynamic dashboard
└── Screenshots/
    └── dashboard_preview.png              # High-resolution dashboard screenshot
