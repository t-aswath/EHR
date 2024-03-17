<div align=center>
  <img src="https://github.com/bitspaceorg/.github/assets/119417646/577c8581-499e-4cbb-a2f8-e78c643204bc" width="150" alt="Logo"/>
   <h1> VASHISHT-HACKATHON</h1>
  <img src="https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white">
<img src="https://img.shields.io/badge/:bitspace-%23121011?style=for-the-badge&logoColor=%23ffffff&color=%23000000">
<img src="https://img.shields.io/badge/vashisht-%23121011?style=for-the-badge&color=black">
<img src="https://img.shields.io/badge/iiitdm-%23121011?style=for-the-badge&logoColor=%23ffffff&color=%23000000">
<img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&color=black">
</div>

# Electronic Health Record (EHR) Solution

## Problem Statement
In the modern healthcare landscape, managing patient records, treatment history, and medical data efficiently and securely is a daunting challenge. Traditional paper-based systems are cumbersome and prone to errors, while existing digital solutions often lack interoperability and user-friendly interfaces. Moreover, ensuring the privacy and security of sensitive medical information is paramount, requiring robust authentication and access control mechanisms.

## Our Solution
Our team has developed a comprehensive Electronic Health Record (EHR) solution to address the challenges faced by healthcare providers, patients, and medical professionals. Our EHR platform offers a centralized system for storing, managing, and accessing medical records securely, facilitating seamless communication and collaboration between stakeholders.

## Overview
Our EHR solution consists of frontend and backend components, designed to provide a user-friendly interface and robust backend infrastructure for managing patient data and medical records. Here's an overview of our solution:

### Frontend
Our frontend application is built using Next.js, React, Tailwind CSS, and D3.js for interactive data visualization. It offers a responsive and intuitive user interface accessible from any device, allowing patients, doctors, and hospital administrators to view medical records, treatment history, and prognosis predictions conveniently.
![fe](https://cdn.discordapp.com/attachments/1217865124820287508/1218823950730133504/image.png?ex=66091142&is=65f69c42&hm=1ee9cb6eb924084a256525ec464daa23f6805603a6721d62a4b6fba718fb80d6&)
### Backend
The backend of our EHR solution is powered by Node.js and Express.js, with TypeScript for improved code quality and developer experience. We utilize PostgreSQL as our relational database, with Superbase for authentication and real-time capabilities. The backend handles user authentication, authorization, and serves RESTful APIs for CRUD operations on patient records, treatment details, and medical history.
![bd](https://cdn.discordapp.com/attachments/1217865124820287508/1218797054894014554/Group_141.png?ex=6608f836&is=65f68336&hm=cea5bdfc27b27ae40589259ca92b462567eb838c9c23e96d34debfd1ad4a6d6e&)
### Machine Learning Models
To enhance the functionality of our EHR solution, we have integrated several machine learning models for forecasting the risk of major diseases and providing personalized medical insights. Here are the models used:

- **Novel Variation Detection (NVD)**: Gaussian Naive Bayes model trained to detect variations in lung cancer risk based on patient demographics and health attributes.
- **Sugar Kinetics (SK)**: Random Forest Classifier model trained to predict the likelihood of diabetes based on glucose levels, blood pressure, insulin levels, BMI, and age.
- **Mind Pulse (MP)**: Logistic Regression model used for predicting the risk of strokes based on patient characteristics such as age, gender, hypertension, heart disease, average glucose level, and BMI.
- **Kidney Condition Detection (KCD)**: Random Forest Classifier model trained to detect kidney conditions based on various health indicators such as age, blood pressure, glucose levels, and other attributes.
- **Outlier-Sensitive Predictor (OSP)**: Another Random Forest Classifier model designed to predict heart conditions based on age, gender, chest pain, cholesterol levels, and other factors.

These machine learning models complement our EHR solution by providing actionable insights and proactive healthcare recommendations to patients and medical professionals.

### Features
- **Role-based Access Control**: Different access levels for hospital administrators, patients, and doctors, ensuring data privacy and security.
- **Real-time Updates**: Seamless integration with Superbase for real-time updates to patient records and medical data.
- **Data Visualization**: Interactive charts and graphs powered by D3.js for visualizing medical data and prognosis predictions.
- **File Storage Bucket**: Secure storage for saving records such as X-rays, scans, and other medical documents, using Amazon S3.

## Setup Instructions
To set up and run the EHR solution locally, follow the instructions provided in the respective frontend and backend README files:

- [Frontend README](https://github.com/RahulNavneeth/IIITDM-HACK-frontend/blob/master/README.md)
- [Backend README](https://github.com/navi-prem/EHR-backend/blob/master/README.md)
- [Model README](https://github.com/RaviprasathKJ/EHR-model/blob/main/README.md)

## Demo


https://github.com/t-aswath/EHR/assets/119417646/d1b93119-199c-4686-a945-cb42a32bd2d3



## Team Members

- t-aswath : aswatht.cse2022@citchennai.net
- rahul m navneeth : rahulmnavneeth@gmail.com
- naveen : naviprem.2005@gmail.com
- ravi prasath : raviprasath320@gmail.com

## Contributing
We welcome contributions from the community to enhance and improve our EHR solution. Please refer to the contributing guidelines in the respective repositories for more information on how to contribute.
