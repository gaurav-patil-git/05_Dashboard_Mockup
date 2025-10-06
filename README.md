# 🤖 Dashboard Mockup | Sales & Retail Domain

### Design a simple Power BI dashboard mockup for product manager and analytics team working on Sales & Retail Data.

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools-technologies">Tools & Technologies</a>
- <a href="#designing-process">Designing Process</a>
- <a href="#mockup">Mockup</a>
- <a href="#author-contact">Author & Contact</a>

<h2><a class="anchor" id="overview"></a>📝 Overview</h2>

This project leverages Claude (Sonnet 4.5 Free Version) to design a Power BI dashboard mockup. The objective is to conceptualize and visualize a basic executive dashboard by:
- Defining a clear and functional executive dashboard layout
- Developing and iteratively refining the design prompt
- Using Claude to generate and refine the visual mockup

<h2><a class="anchor" id="tools-technologies"></a>🛠️ Tools & Technologies</h2>

| Task                 | Tools Used                          |
|----------------------|-------------------------------------|
| Gemini   | Refining Prompt                               |
| Claude         | Develop Dashboard Mockup                       |


<h2><a class="anchor" id="designing-process"></a>📝 Designing Process</h2>

### Step 1: Rough Ideation (Executive Dashboard)
- Left Pane: Slim navigation and filter panel
- KPI cards at top: Revenue, Profit, Orders, Return Rate (CM, % v PM)
- Line Chart 1: Revenue by Months with a dashed trendline
- Line Chart 2: Orders by Months with a dashed trendline
- Horizontal Bar chart: Top 5 Cities by Sales
- Donut chart: Revenue and Revenue % by categories (values as data labels)
- Colours: White background, E1E5EE, 2A324B, F7C59F

### Step 2: Draft Prompt
```
#### Task: Generate a modern and aesthetic 16:9 executive power-bi dashboard mockup 
#### Layout:
- A slim vertical navigation and filter panel on the left side of the screen. 
- Navigation: Executive, Products, Customers. 
- Filter Options: Regions as dropdown.
- On the top is the left aligned title “Sales Dashboard” in bold. Below the title is the subtitle as “Last Updated on DD-MM-YYYY”.
- Across the top of main dashboard area, there are four KPI cards: Revenue, Profit, Orders, Return Rate (Each having Current Value, Percentage change v Last Month)
#### Charts:
- Below KPI Cards on left section of the main dashboard area, there are two-line charts stacked on each other
- Line Chart 1: Revenue by Months with a dashed trendline
- Line Chart 2: Orders by Months with a dashed trendline
- Below KPI Cards on right section of the main dashboard area, there are two charts stacked on each other.
- Horizontal Bar chart: Top 5 Cities by Revenue (Mumbai, Pune, Chennai, Delhi, Hyderabad) 
- Donut chart: Revenue and Revenue % by categories. Values are shown data labels with connecting line
#### Colour palette:
- White - background, 
- 2A324B - text and primary chart element
- E1E5EE – secondary chart element
- F7C59F – specific highlights
- Font: Segoe UI
- Dashboard should be professional and highly readable.
```

### Step 3: Refine Prompt (Google Gemini)
```
- A modern, aesthetic, and professional 16:9 executive Power BI dashboard mockup.
- The layout features a slim, vertical navigation and filter panel on the left. The navigation includes "Executive," "Products," and "Customers." Filter options consist of a "Regions" dropdown.
- The top of the main dashboard area displays the left-aligned bold title "Sales Dashboard" with the subtitle "Last Updated on DD-MM-YYYY" directly below it.
- Across the top of the main dashboard area are four KPI cards: Revenue, Profit, Orders, and Return Rate. Each card shows the Current Value and Percentage change versus Last Month.
- Below the KPI cards, the main dashboard area is divided. The left section contains two stacked line charts:
- Line Chart 1: Revenue by Months with a dashed trendline.
- Line Chart 2: Orders by Months with a dashed trendline.
- The right section, also below the KPI cards, features two stacked charts:
- Horizontal Bar Chart: Top 5 Cities by Revenue (E.g.: Mumbai, Pune, Chennai, Delhi, Hyderabad).
- Donut Chart: Revenue and Revenue % by categories, with data labels and connecting lines.
- The color palette is:
  - Background: White
  - Text and Primary Chart Elements: #2A324B
  - Secondary Chart Elements: #E1E5EE
  - Specific Highlights: #F7C59F
- The font used throughout the dashboard is Segoe UI. The dashboard should be highly readable.
```

<h2><a class="anchor" id="mockup"></a>📊 Final Mockup</h2>

![final-mockup](https://github.com/gaurav-patil-git/05_Dashboard_Mockup/blob/main/visuals./final-mockup.png)

<h2><a class="anchor" id="author-contact"></a>📝 Author & Contact</h2>

**Gaurav Patil** (Data Analyst) 
- 🔗 [LinkedIn](https://www.linkedin.com/in/gaurav-patil-in/)


