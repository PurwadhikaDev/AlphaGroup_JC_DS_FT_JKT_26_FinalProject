# Olist E-commerce Recommendation System

## Business Problem

In today's competitive e-commerce landscape, **Olist** faces the challenge of effectively engaging a diverse customer base and driving repeat purchases. With a wide range of products and varying customer behaviors, the key issues include:
- **Customer Retention:** Identifying ways to keep customers engaged and loyal.
- **Personalization:** Delivering tailored shopping experiences to meet individual customer needs.
- **Revenue Growth:** Enhancing cross-selling and up-selling opportunities to boost overall sales.

## Objective

The primary goal of this project is to develop an advanced recommendation system that:
- **Delivers Personalized Suggestions:** Uses customer behavior and product similarities to suggest products that match individual preferences.
- **Leverages Advanced Analytics:** Integrates collaborative filtering (both user-based and item-based) and a Singular Value Decomposition (SVD) model to improve recommendation accuracy.
- **Informs Strategic Decisions:** Provides actionable insights through customer segmentation and RFM analysis to support targeted marketing initiatives.

## RFM Analysis

To better understand customer behavior, we conducted an RFM (Recency, Frequency, Monetary) analysis:
- **Recency:** Measures how recently a customer made a purchase, indicating current engagement.
- **Frequency:** Assesses how often a customer purchases, identifying loyal customers.
- **Monetary:** Evaluates how much a customer spends, highlighting high-value segments.

This analysis helps segment the customer base, enabling more effective targeting and personalized marketing strategies that complement the recommendation system.

## Recommendation System

Our recommendation engine is built using a combination of techniques:

- **User-Based Collaborative Filtering:**  
  Identifies customers with similar purchasing behaviors and recommends products that peers have liked.

- **Item-Based Collaborative Filtering:**  
  Suggests products that are similar to those a customer has interacted with, based on historical review data.

- **SVD Model Integration:**  
  Applies Singular Value Decomposition to reduce the dimensionality of the user-item matrix, capturing latent factors that enhance recommendation relevance.

The system is implemented in Python and features an interactive Streamlit interface, allowing users to test recommendations in real-time by entering either a Customer Unique ID or a Product ID.

## Note

[View the Tableau Dashboard](https://public.tableau.com/app/profile/satria.yudha/viz/FINALPROJECTJCDS2604ALPHATEAM/SalesDashboard?publish=yes)

This project serves as a foundational step toward a more data-driven approach in Olist's marketing strategy. Future enhancements will focus on refining our models, incorporating additional data sources, and scaling the system to accommodate growing customer and product volumes.

---
