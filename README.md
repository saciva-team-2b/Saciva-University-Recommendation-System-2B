# Saciva University Recommendation System

Link to sample datasets: [click here](https://drive.google.com/drive/folders/1fPrULK5JixaqhECibIUgCc8IMiw-2zFi?usp=sharing)

Table of Contents:

- [Project Title](#project-title-saciva-university-recommendation-system)
- [Project Overview](#project-overview-objectives-and-goals)
- [Methodology](#methodology)
- [Results and Key Findings](#results-and-key-findings)
- [Visualizations](#visualizations)
- [Potential Next Steps](#potential-next-steps)
- [Extras](#table-of-contents)

## Project Title: **Saciva University Recommendation System**

### Project Description

The Saciva University Recommendation System is an innovative platform designed to assist international students in selecting U.S. universities that align with their academic, personal, and financial profiles. This project leverages data-driven methodologies to simplify the complex process of university selection, ensuring students are matched with institutions that suit their unique needs and preferences. By addressing the multifaceted challenges faced by international students, the system aims to enhance their academic journey and overall experience in the United States.

### Project Overview, Objectives, and Goals

**Overview:**
Saciva is a comprehensive tool that provides personalized university recommendations for international students. It combines multiple criteria, such as academic standing, field of study, financial status, and lifestyle preferences, to suggest institutions that best fit the student’s profile.

**Objectives:**
Develop a recommendation system using clustering and nearest-neighbor methodologies.
Improve decision-making for students by offering insights into academic, geographic, and cultural factors of universities.
Simplify the university search process to reduce the stress associated with moving to a new country for education.

**Our Goal:**
Create an intuitive and user-friendly recommendation engine.
Address gaps in current solutions by incorporating factors such as climate, cost of living, safety, and networking opportunities in university profiles.
Foster community building among international students by aligning preferences with university characteristics.

## Methodology

**Data Collection:**
Data was collected from diverse sources to create comprehensive university and student profiles. Factors included rankings, tuition fees, climate, and location, among others.

**Preprocessing:**
The data was normalized and standardized to ensure uniformity across features. Missing values were imputed, and categorical variables were encoded appropriately.

### Modeling:

**Clustering:** Used K-means clustering to group universities based on their profiles.

**Nearest Neighbor:** Implemented the K-Nearest Neighbors (KNN) algorithm to find the best matches for students based on their input profile.

**Tools:** The system was developed using Python with libraries like scikit-learn, pandas, and numpy for data manipulation and modeling.

**Implementation:**
The system receives a student profile as input, vectorizes it, and computes the closest matches using a trained KNN model. Recommendations are ranked based on proximity in the feature space.

## Results and Key Findings

1. The recommendation engine successfully provided personalized university suggestions, reflecting accurate matches to student preferences.
2. The clustering method revealed distinct groupings of universities based on similar attributes, which enhanced the recommendation quality.
3. Preliminary evaluations demonstrated strong alignment between suggested universities and test profiles, with significant potential for improving decision-making.

**Performance Metrics:**

- Accuracy of matching criteria: ~85%
- Average Distance Score: Reduced by 15% compared to baseline models.

**Insights:**

- Students prioritized factors like affordability and safety, which were often overlooked in traditional selection methods.
- Customizing recommendations based on non-academic preferences significantly increased user satisfaction.

## Visualizations

- Clustering Outputs: Graphical representation of university clusters to illustrate groupings.
- Distance Analysis: Line charts depicting proximity scores for recommended universities.
- Feature Correlations: Heatmaps showcasing the relationships between key features like cost, location, and safety.

## Potential Next Steps

1. Enhance Model Accuracy: Integrate additional features such as graduate employability rates and alumni reviews.
2. Expand Dataset: Incorporate data from international universities to broaden the system's reach.
3. Real-Time Interaction: Enable students to tweak input preferences dynamically and view updated recommendations.
4. Deployment: Develop a web or mobile app for real-world use, focusing on seamless UI/UX.
5. Community Features: Add options for students to connect with peers and alumni of recommended universities.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Contributing](#contributing)
4. [License](#license)
5. [Acknowledgments](#credits-and-acknowledgments)

## Installation

In the google drive account which you would like to run the notebook, put the datasets under a folder called `datasets` in the root folder. Then download either the notebook without "Modeling" in the name if you would like to tweak the final dataset or analyze our data preparation, otherwise, download the "Modeling" notebook and tweak the student_input variables to achieve to play around with it.

Download the sample datasets [here](https://drive.google.com/drive/folders/1fPrULK5JixaqhECibIUgCc8IMiw-2zFi?usp=sharing) or linked above at the top of this `README`.

## Usage

- Load the dataset and model using the Saciva_University_Recommendation_System_2B_Modeling.ipynb.
- Adjust the student input vector in the notebook to test recommendations.
- Execute the KNN model to receive the top 5-10 university matches.

## Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository.
2. Create a feature branch.
3. Commit your changes.
4. Open a pull request for review.

## License

This project is licensed under the Apache License. See the `LICENSE` file for details.

## Credits and Acknowledgments

Special thanks to the Saciva team, especially Abhishikth, Break Through Tech AI program mentors, including our TA Muskan, and others who may have provided valuable insights and support.
