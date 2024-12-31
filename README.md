## 📈 Problem Statement

This project focuses on optimizing Domino's inventory management by building a predictive system that forecasts pizza sales and generates purchase orders for ingredients. By leveraging historical sales data, the goal is to develop a model that accurately predicts future sales, allowing Domino's to order the right amount of ingredients, minimizing waste, and preventing stockouts.

---

## 🎯 Objective:

- To Develop a predictive model to forecast pizza sales.
- To Create a purchase order system that calculates the required quantities of ingredients based on the sales forecast.
  
---

## 🔍 Dataset Overview

The project involves two datasets: **Pizza Sales** and **Pizza Ingredients**. 

- The **Pizza Sales Dataset** comprises 48,620 entries, each detailing an individual sale. This includes information such as `pizza_id` (a unique identifier for the sale), `order_id` (linking to a specific order), `pizza_name_id` (a unique identifier for each pizza), `quantity` (number of pizzas sold), `order_date` and `order_time` (when the sale occurred), `unit_price` and `total_price` (pricing details), as well as `pizza_size` and `pizza_category` (size and type of pizza). This dataset offers a thorough view of sales, covering pricing, timing, and pizza characteristics. 

- The **Pizza Ingredients Dataset** consists of 518 entries that describe the ingredients for various pizzas. It includes `pizza_name_id` (a unique identifier for each pizza), `pizza_name` (name of the pizza), `pizza_ingredients` (list of ingredients), and `Items_Qty_In_Grams` (the quantity of each ingredient used). This dataset provides detailed insights into the composition of each pizza and the amounts of ingredients required.


## 🏆 Results

The project delivers highly accurate pizza sales forecasts, providing precise predictions for the upcoming week. These forecasts enable better planning and optimized inventory management. Based on the predicted sales, a comprehensive purchase order is generated, detailing the exact quantities of each ingredient required. This ensures that the necessary ingredients are stocked efficiently, minimizing waste and avoiding shortages. The result supports seamless operations by aligning supply with demand, improving both supply chain efficiency and overall business performance.
