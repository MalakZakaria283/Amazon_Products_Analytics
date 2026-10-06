# 📊 Amazon Products Analytics Power BI Dashboard

An executive-level, interactive two-page Power BI dashboard designed to analyze e-commerce product performance, pricing dynamics, discount strategies, and customer satisfaction metrics[span_0](start_span)[span_0](end_span)[span_1](start_span)[span_1](end_span).

---

## 🛠️ Key Features & Interactivity
- **Executive Overview (Page 1):** Highlights key KPIs (Catalog Count, Total Engagement, Average Rating, Discount %, Pricing) alongside rating distributions, satisfaction hierarchies, and discount band counts[span_2](start_span)[span_2](end_span)[span_3](start_span)[span_3](end_span).
- **Details & Deep-Dive Analysis (Page 2):** Tabular analysis of product-level metrics, customer engagement, satisfaction scores, and revenue generation[span_4](start_span)[span_4](end_span).
- **Interactive UI & Filtering:** Modern dark-themed layout with synchronized slicers for Category and Sub-Category across all visuals[span_5](start_span)[span_5](end_span)[span_6](start_span)[span_6](end_span).
- **Insight Cards:** Dedicated textual cards providing instant executive insights and analytical notes[span_7](start_span)[span_7](end_span)[span_8](start_span)[span_8](end_span).

---

## 📐 Data Modeling & DAX Measures
- **Data Model:** Structured star schema built in Power Query with cleaned e-commerce attributes, category hierarchies, and pricing dimensions[span_9](start_span)[span_9](end_span).
- **DAX Calculations:** Custom measures implemented to ensure accurate row-level evaluation context (e.g., dynamic average ratings) and prevent rate-aggregation distortions across categories[span_10](start_span)[span_10](end_span)[span_11](start_span)[span_11](end_span).
  - `Average Rating`
  - `Total Engagement`
  - `Average Discount %`
  - `Total Revenue`

---

## 📂 Repository Contents
- **`Dashboard/`**: Contains the full `.pbix` Power BI interactive report file[span_12](start_span)[span_12](end_span).
- **`Dataset/`**: Contains the raw CSV data source used for transformation and modeling[span_13](start_span)[span_13](end_span).
- **`Images/`**: High-resolution screenshots of the dashboard pages[span_14](start_span)[span_14](end_span).

---

## 📸 Previews

### Page 1: Home
![Home Page Overview](home.png)

### Page 2: Details
![Details Page Preview](details.png)

