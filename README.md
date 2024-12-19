# Instacart Order Dispatch and Delivery Routing Optimization

## Technologies and Skills
### Technologies Used:
- 🐍 **Programming Languages**: Python
- 📚 **Libraries and Tools**: Pandas, NumPy, Matplotlib, Jupyter Notebook, Azure Bing Maps API
- 🧩 **Optimization Solver**: Gurobi Optimization

### Skills Demonstrated:
- 🌍 **Data Simulation**: Leveraging Azure Bing Maps API to generate realistic datasets incorporating traffic, construction, and urban constraints.
- 🔧 **Optimization Modeling**: Designing and implementing solutions for Open Vehicle Routing Problems (OVRP).
- 🗺️ **Simulated Environment Modeling**: Creating realistic datasets with geographical and traffic constraints.
- 📊 **Business Insight Generation**: Translating technical results into actionable recommendations.
- 🤝 **Collaboration**: Working effectively within a team to produce comprehensive deliverables.
- 🎤 **Communication**: Presenting findings and implications clearly through visualizations and reports.


---
## Overview
This project focuses on optimizing order dispatch and delivery routing for Instacart, a leading grocery delivery platform. By addressing operational challenges in a dynamic urban environment like Montreal, this analysis offers actionable insights to enhance shopper efficiency, reduce delivery times, and improve customer satisfaction. The project applies data analytics and optimization techniques to deliver business-critical recommendations.

---

## Business Problem
Instacart operates within a complex four-sided marketplace including customers, shoppers, delivery drivers, and retail stores. The challenges include:
- Efficiently assigning shoppers to orders based on proximity and timing.
- Optimizing delivery routes in a city with complex traffic conditions and infrastructure.

**Objective**: Minimize delivery times during peak hours (10 AM–3 PM) while balancing operational efficiency and customer satisfaction.

---

## Key Insights and Business Implications

### Findings:
1. **Efficient Batching of Orders**:
   - Orders grouped by proximity reduce total travel time per delivery.
   - Actionable Insight: Group orders strategically to minimize transit costs.

2. **Traffic-Aware Routing**:
   - Incorporating penalties for traffic, construction, and one-way streets improves delivery accuracy.
   - Business Implication: Optimized routes reduce operational disruptions and improve on-time deliveries.

3. **Customer-Centric Delivery**:
   - Prioritizing time-sensitive orders (e.g., exceeding a 10-minute wait threshold) enhances service quality.
   - Business Impact: Improved customer satisfaction increases retention rates.

4. **Urban Zoning Impact**:
   - Residential areas exhibit higher order density; suburban deliveries take longer due to sparse demand points.
   - Recommendation: Allocate resources dynamically to match area-specific demand patterns.

---

## Project Features
- **Optimization Model**:
  - Solves the Open Vehicle Routing Problem (OVRP) with constraints for traffic, batching, and land-use diversity.
- **Simulated Real-World Environment**:
  - Data incorporates urban challenges like construction zones and varying land-use zones.

---

## Methodology
1. **Pickup Stage Optimization**:
   - Assign shoppers based on proximity and order waiting time.
   - Batching orders for efficiency.

2. **Delivery Stage Optimization**:
   - Determine optimal routes considering traffic and geographical diversity.

3. **Data Simulation**:
   - Simulated demand points and traffic conditions reflective of Montreal's urban characteristics.

4. **Tools and Techniques**:
   - Python, Jupyter Notebook, Pandas, Numpy, Matplotlib.
   - Azure Bing Maps API for real-world distance and time estimates.

---

## Results
- Reduced average delivery time by up to **20%** with strategic batching.
- Increased shopper efficiency through proximity-based assignments.
- Improved service reliability in high-density areas with adaptive routing.

---

## Files in this Repository
- **`Instacart_report.pdf`**: Comprehensive project report detailing methodology, results, and insights.
- **`Instacart_code.ipynb`**: Jupyter Notebook containing the optimization model and analysis.
- **`data.xlsx`**: Input dataset for simulated demand and traffic conditions.
- **`result.csv`**: Output file summarizing optimized routes and timings.
- **`Instachart_V_Final.pdf`**: Final presentation summarizing project objectives, methodology, and key findings.

---

## Recommendations
1. Integrate customer delivery time preferences for more personalized service.
2. Expand the model to handle multi-supplier orders to reflect real-world complexity.
3. Explore dynamic routing systems for real-time traffic and weather adaptability.

---

## Acknowledgments
This project was completed as part of the MGSC662 course at McGill University, in collaboration with **Shuxi Chen**, **Henry Tang**, **Samarth Annigeri** and **Jintao Li**.

---

## References
- [Gurobi Optimization Case Study](https://www.gurobi.com/case_studies/instacart-delivering-optimal-shopping-experiences)
- [Optimization Insights for Delivery Services](https://youtu.be/F0iaBmYyLCI)
