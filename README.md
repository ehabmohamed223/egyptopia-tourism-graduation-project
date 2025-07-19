# **Egyptopia - Virtual Tour Guide Application**

## **Overview**

Egyptopia is a smart travel recommendation system designed to enhance the tourism experience in Egypt by offering personalized suggestions based on user preferences and behavior. The system leverages artificial intelligence and a curated tourism dataset to recommend attractions that go beyond the typical tourist spots, helping users discover both popular landmarks and hidden gems.
The platform integrates multiple recommendation strategies, including content-based filtering, location-based suggestions, and a Bayesian average method to support new users. Additional features include an itinerary planner tailored to user budgets, a generative AI chatbot trained on Egypt-related data, and advanced filters by city and attraction type. To further enrich the experience, Egyptopia also offers cultural quizzes and a guide to traditional Egyptian food and beverages


## **Project Structure**
"This repository contains the foundational components, including AI-driven data pipelines, documentation, and structured datasets, that support the Egyptopia smart recommendation engine."

### 1.**Competitor Analysis**

A **competitor analysis** was conducted on six mobile applications dedicated exclusively to tourism in Egypt: **Around Egypt**, **Explore Egypt**, **Civitatis Egypt**, **Visit Egypt**, **Cairo Travel Guide**, and **Experience Egypt**. The objective was to assess their core features, usability, and overall effectiveness in supporting the tourist experience.

<p align="center">
  <img src="https://github.com/user-attachments/assets/322f8c99-7f84-46e7-a2ea-7aeb975e685c" alt="Egyptopia Feature Comparison Table" width="800" />
</p>

The evaluation focused on several key aspects, including:
- Functional features and tourism-related services  
- User interface (UI) and design quality  
- Download statistics and user reviews from Google Play  
- The presence of intelligent systems such as search, filters, or recommendation engines  

Findings indicated that while these applications provide basic informational content and cultural overviews, they generally lack advanced features such as personalized recommendations, intelligent filtering, interactive experiences, or dynamic content updates. In many cases, the visual design was outdated, and the platforms lacked support for diverse tourism types or localized experiences.

<p align="center">
  <img src="https://github.com/user-attachments/assets/faa852d4-3357-4dc4-b483-bd9232831d31" alt="Competitor Analysis Screenshot" width="500" />
</p>

[View the full Competitor Analysis Report](https://github.com/ehabmohamed223/egyptopia-tourism-graduation-project/blob/main/product-analysis-report-for-egyptopia/competitor_%20analysis_report_for_egyptopia.pdf)

---
## **2.Survey Analysis**


- **Objective**: Analyzes a survey of 82 participants to understand tourist preferences.

- **My Role**: Conducted comprehensive data analysis and designed targeted survey questions to enhance user experience.

- **Tools**: Python (pandas, numpy, plotly) for visualizations.


- **Key Insights**:
  
<p align="center">
  <img src="https://github.com/user-attachments/assets/884b73a2-e93b-4fda-bcab-f3b1afc7e3d4" alt="Image 1" width="220" />
  <img src="https://github.com/user-attachments/assets/d68324d3-2f5e-4e9d-b0e3-a331b06cf9f6" alt="Image 2" width="220" />
  <img src="https://github.com/user-attachments/assets/15317b9c-679a-40fb-bb6f-e87bbf9b8ebb" alt="Image 3" width="220" />
  <img src="https://github.com/user-attachments/assets/752f72c6-2b08-4202-a245-003a26fd1576" alt="Image 4" width="220" />
</p>

The full survey findings are documented in the [Egyptopia User Needs Survey Analysis Report](https://github.com/ehabmohamed223/egyptopia-tourism-graduation-project/blob/main/egyptopia-user-needs-survey-analysis/report_of_egyptopia_survey_analysis.pdf).

---

## **3.Database Design**

- **Objective**: Outlines the schema for storing Egyptopia data.

- **My Role**: Designed the database architecture to ensure efficient data relationships.

<p align="center">
  <img src="https://github.com/user-attachments/assets/b90d3a51-cbb0-40c1-b966-2aeaf71858d4" alt="Egyptopia Screenshot" width="600" />
</p>

The data architecture for Egyptopia is documented in a visual schema file.  
[Download Egyptopia Schema (.drawio)](https://github.com/ehabmohamed223/egyptopia-tourism-graduation-project/blob/main/egyptopia_database_schema/egyptopia_schema.drawio)

---

## **4.Data Collection**


- **Objective**: Gathers comprehensive datasets for Egyptopia.
- **MY Role**: Collected extensive data on tourist attractions, activities, and Egyptian cuisines/beverages, and processed it for database integration.
- **Notes**: Supports 320 places, 50 food items, 362 activities, and dynamic events.

- **Methods**: Web scraping, CSV storage, Pandas DataFrame.


<table>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/796d2823-bfdd-4a75-9a27-6e94a111fee9" alt="Image 1" width="480" />
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/d8a84e05-d1dc-4df7-8859-6230a51a8685" alt="Image 2" width="480" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/4a72ed99-03be-4d9f-a92e-f8ca69ed46a7" alt="Image 3" width="480" />
    </td>
    <td align="center">
      <img src="https://github.com/user-attachments/assets/a8b614e7-a73c-4c92-85fc-70b75d95c070" alt="Image 4" width="480" />
    </td>
  </tr>
</table>


For a complete overview of the data sources, scraping pipelines, and integration steps, please refer to the  
[Egyptopia Data Collection Report](https://github.com/ehabmohamed223/egyptopia-tourism-graduation-project/blob/main/egyptopia_data%20collection_and_processing/Egyptopia%20Data%20Collection%20Report.pdf)

---

## **5. Recommendation System**

- **Objective**: Delivers personalized travel suggestions.

- **My Role**:  
  Engineered a multi-faceted recommendation system that integrates various intelligent techniques to enhance user experience and promote exploration:

  - **Content-Based Recommendation System**  
    Designed to highlight lesser-known attractions that align with the user’s interests by placing them alongside popular destinations. It also introduces novel and diverse suggestions that slightly diverge from the user’s typical preferences to foster discovery and increase engagement.

  - **Non-Personalized Recommendation System**  
    Utilizes **Bayesian average scores** to promote attractions by tourism type, ensuring fair promotion of places regardless of the number of ratings.

  - **Location-Based Recommendation System**  
    Displays nearby attractions based on user-selected locations, helping users discover points of interest relative to their current or chosen area.

  - **User Behavior Simulation**  
    Developed simulations to evaluate the recommendation system’s performance based on user inputs, optimizing its effectiveness.

[View the Egyptopia Recommendation System Report](https://github.com/ehabmohamed223/egyptopia-tourism-graduation-project/blob/main/egyptopia-recommendation-system/egyptopia_recommendation_system_report-compressed.pdf)


---

## **6. Dataset Versions & Storage**

- The [Egyptopia Places Dataset Versions](https://github.com/ehabmohamed223/egyptopia-tourism-graduation-project/tree/main/egyptopia-recommendation-system/egyptopia_places_dataset_versions) directory contains iterative versions of the places dataset used throughout the development of the recommendation system. This versioning structure ensures traceability and reproducibility of changes made to place-related data.

- The full [Egyptopia Datasets Repository](https://github.com/ehabmohamed223/egyptopia-tourism-graduation-project/tree/main/egyptopia_data%20collection_and_processing/egyptopia_datasets) includes all collected datasets and associated media, such as the 2,377 place images, attraction metadata, food and drink entries, and tourism activity logs.
