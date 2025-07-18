# **Egyptopia - Virtual Tour Guide Application**

## **Overview**

Egyptopia is a smart travel recommendation system designed to enhance the tourism experience in Egypt by offering personalized suggestions based on user preferences and behavior. The system leverages artificial intelligence and a curated tourism dataset to recommend attractions that go beyond the typical tourist spots, helping users discover both popular landmarks and hidden gems.
The platform integrates multiple recommendation strategies, including content-based filtering, location-based suggestions, and a Bayesian average method to support new users. Additional features include an itinerary planner tailored to user budgets, a generative AI chatbot trained on Egypt-related data, and advanced filters by city and attraction type. To further enrich the experience, Egyptopia also offers cultural quizzes and a guide to traditional Egyptian food and beverages


## **Project Structure**
"This repository contains the foundational components, including AI-driven data pipelines, documentation, and structured datasets, that support the Egyptopia smart recommendation engine."

### 1.**Competitor Analysis**

A **competitor analysis** was conducted on six mobile applications dedicated exclusively to tourism in Egypt: **Around Egypt**, **Explore Egypt**, **Civitatis Egypt**, **Visit Egypt**, **Cairo Travel Guide**, and **Experience Egypt**. The objective was to assess their core features, usability, and overall effectiveness in supporting the tourist experience.

The evaluation focused on several key aspects, including:
- Functional features and tourism-related services  
- User interface (UI) and design quality  
- Download statistics and user reviews from Google Play  
- The presence of intelligent systems such as search, filters, or recommendation engines  

Findings indicated that while these applications provide basic informational content and cultural overviews, they generally lack advanced features such as personalized recommendations, intelligent filtering, interactive experiences, or dynamic content updates. In many cases, the visual design was outdated, and the platforms lacked support for diverse tourism types or localized experiences.

These insights directly informed the design of **Egyptopia**, which addresses the identified limitations by introducing:
- AI-driven personalized and non-personalized recommendations  
- Location-based suggestions  
- A budget-aware itinerary planner  
- Advanced filtering options by city, tourism type, and category  
- A modern, intuitive user interface  

[View Competitor Analysis Report](https://github.com/ehabmohamed223/egyptopia-tourism-graduation-project/blob/main/product-analysis-report-for-egyptopia/competitor_%20analysis_report_for_egyptopia.pdf)

---

## **Survey Analysis**

- **Objective**: Analyzes a survey of 82 participants to understand tourist preferences.

- **Key Insights**:
  - **Gender**: 44 females, 38 males (23 Egyptians, 59 foreigners).
  - **Age**: 78% (18–29), 17% (30–49), 3.6% (50+), 1.22% (<18).
  - **Interests**: 57.32% very interested in local interaction, 42% in beaches.
  - **App Demand**: 56 want a guiding app, 70 prefer travel tips.

- **Tools**: Python (pandas, numpy, plotly) for visualizations (pie charts, bar graphs).

- **Role**: Conducted comprehensive data analysis and designed targeted survey questions to enhance user experience.

---

## **Database Design**

- **Objective**: Outlines the schema for storing Egyptopia data.

- **Components**:
  - **Places Table**: Includes name, category, place_id, Google Maps link, rate, total rates.
  - **Food & Drinks Table**: Item ID, Arabic/English names, classification, description.
  - **Events Table**: Event name, description, location, date, ticket price, organizer.
  - **Activities Table**: Title, rating, price, link, activity type.

- **Notes**: Supports 320 places, 50 food items, 362 activities, and dynamic events.

- **Role**: Designed the database architecture to ensure efficient data relationships.

---

## **Data Collection**

- **Objective**: Gathers comprehensive datasets for Egyptopia.

- **Datasets**:
  - **Places**: 320 sites across 5 categories, 2,377 images.
  - **Food & Drinks**: 50 items (16 Main Dishes, 12 Desserts, etc.).
  - **Events**: Static events (e.g., Sun Alignment at Abu Simbel) with admin updates.
  - **Activities**: 362 activities (e.g., Balloon Tours, Diving) via web scraping.

- **Methods**: Web scraping, CSV storage, Pandas DataFrame.

- **Role**: Collected extensive data on tourist attractions, activities, and Egyptian cuisines/beverages, and processed it for database integration.

---

## **Recommendation System**

- **Objective**: Delivers personalized travel suggestions.

- **Features**:
  - Content-based system to surface lesser-known attractions aligned with user interests, with novel suggestions to encourage exploration.
  - Non-personalized system using Bayesian average scores by tourism type.
  - Location-based system for nearby attractions.

- **Development**: Engineered the multi-faceted system and simulated user behavior to optimize performance.

- **Role**: Developed the recommendation system, including all three approaches and performance simulations.

---

## **Features**

- **User Preferences**: Tailored recommendations from the start.
- **Tourism Classification**: 5 types with flexible filters.
- **Price Range Filtering**: Budget-based activity selection.
- **Static Events**: Curated with dynamic updates.
- **Egyptian Cuisine**: 50 iconic items showcased.
- **Nearby Places & Budget Planner**: Enhanced itinerary tools.
- **Notifications**: Alerts for events and discounts.

---

---
