

# Educational Recommender System 🎓

[![TensorFlow.js](https://img.shields.io/badge/TensorFlow.js-4.11.0-FF6F00?logo=tensorflow)](https://www.tensorflow.org/js)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.2-7952B3?logo=bootstrap)](https://getbootstrap.com/)
[![Plotly.js](https://img.shields.io/badge/Plotly.js-2.27.0-3F4F75?logo=plotly)](https://plotly.com/javascript/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> A fully functional, browser-based educational course recommender system using **hybrid AI algorithms** (Collaborative Filtering + Content-Based Filtering) implemented with TensorFlow.js. No installation or server required!

---
<br>


<img width="900" height="850" alt="Screenshot 2025-10-22 150151" src="https://github.com/user-attachments/assets/fc4be233-4c71-46f0-8eca-cbc685eecedf" />

<img width="829" height="904" alt="Screenshot 2025-10-22 150643" src="https://github.com/user-attachments/assets/04a516c9-8e45-4554-8861-081ee627d8b1" />


<img width="561" height="784" alt="Screenshot 2025-10-22 150318" src="https://github.com/user-attachments/assets/d8763a1b-353c-4648-a171-3dd65dc0ef6f" />

<br>
---

## Features

- Hybrid recommendation combining collaborative filtering (TensorFlow.js matrix factorization) and content-based filtering (cosine similarity)
- Real-time model training and prediction entirely in-browser using CDN libraries
- Sample dataset with 20 courses and 50 users with ratings and completion data
- Interactive UI with Bootstrap 5 and elegant visualization via Plotly.js
- Dynamic learning path generation considering prerequisites and difficulty levels
- Responsive and modern design featuring glassmorphism styling
- Clear explanations and recommendation source indicators (Collaborative, Content-Based, Hybrid)

---

## Getting Started

1. Open the live demo link above or download the source and open `index.html` locally.
2. Select a user profile from the dropdown or choose “New User” for a cold-start experience.
3. View user’s past course ratings and completions.
4. Click **Generate Recommendations** to train the model and get personalized course recommendations.
5. Explore course details, similarity heatmaps, and suggested learning paths.

---

## Technical Details

- **Machine Learning Engine:** TensorFlow.js 4.11.0 (Matrix factorization for collaborative filtering)
- **UI Framework:** Bootstrap 5.3.2 (Responsive components)
- **Visualization:** Plotly.js 2.27.0 (Charts and heatmaps)
- **Data:** Embedded JSON with courses metadata and user interactions
- **Training Configuration:** 50 epochs, batch size 32, Adam optimizer, MSE loss
- **Hybrid Weights:** Default 60% Collaborative, 40% Content; Cold start 30% Collaborative, 70% Content

---

## System Requirements

- Modern web browser with JavaScript and WebGL enabled (Chrome, Firefox, Edge, Safari)
- Internet connection required for CDN resources
- Approximately 5-10 seconds for model training in-browser

---


## Contributing

Contributions are welcome in the following areas:

- Adding new course datasets and user profiles
- Enhancing recommendation algorithms or tuning parameters
- UI/UX improvements and accessibility features
- Performance optimization and offline capabilities
- Extending learning path generation logic

---


*Enjoy personalized learning with AI-powered course recommendations at your fingertips!* 🚀🎓
