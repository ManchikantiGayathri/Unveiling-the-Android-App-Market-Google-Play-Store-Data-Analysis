# 📊 Unveiling the Android App Market: Google Play Store Data Analysis

## 📌 Project Overview
This project dives into the **Google Play Store** dataset to uncover key insights about the Android app market.  
By cleaning, analyzing, and visualizing app and review data, we gain a deeper understanding of:
- App distribution across categories
- Ratings, size, and popularity trends
- Pricing strategies
- User sentiment patterns
- Market dynamics

The goal is to combine **data analytics** and **visual storytelling** to make the data speak for itself.

---

## 📂 Dataset
We used two datasets:
1. **apps.csv** → Contains app details such as name, category, rating, installs, size, price, etc.
2. **user_reviews.csv** → Contains user reviews, translated sentiments, polarity, and subjectivity.

---

## 🔍 Key Objectives
The analysis was broken down into **six main challenges**:

### 1️⃣ Data Preparation
- Cleaned dataset by handling missing values
- Corrected data types for numeric columns
- Removed duplicates
- Normalized formats (e.g., `Installs`, `Size`, `Price`)

### 2️⃣ Category Exploration
- Count of apps in each category
- Identification of most crowded categories
- Insights into niche markets with fewer competitors

### 3️⃣ Metrics Analysis
- Relationship between **app size** and **rating**
- Distribution of ratings
- Most popular (highest installs) categories
- Free vs Paid app trends

### 4️⃣ Sentiment Analysis
- Analyzed **user sentiments** from review data
- Used existing sentiment polarity from dataset
- Found which categories and apps have most positive/negative feedback

### 5️⃣ Interactive Visualization (Fallback to Matplotlib)
- Visualized top 10 categories by installs
- Plotted **Price vs Rating** colored by category
- Used **Seaborn** for clean and attractive plots (no additional installation required)

### 6️⃣ Skill Enhancement
- Applied principles from *Understanding Data Visualization* course
- Focused on **clarity, aesthetics, and interpretability**

---

## 📊 Sample Visualizations
Here’s a preview of some charts from the analysis:

| Visualization | Description |
|--------------|-------------|
| 📈 Bar Chart | Top 10 categories by total installs |
| 🟢 Scatter Plot | Price vs Rating colored by category |
| 📉 Histogram | Distribution of app ratings |
| 📊 Pie Chart | Free vs Paid app percentage |

*(You can replace this section with actual images once you add them to your repo.)*

---

## 🛠️ Technologies Used
- **Python** 🐍
- **Pandas** → Data cleaning & analysis
- **Matplotlib** → Static data visualization
- **Seaborn** → Enhanced statistical plots
- **NumPy** → Numerical operations

---

## 💻 Installation & Usage

To run this project locally, you'll need Python and several libraries.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/customer-segmentation.git](https://github.com/your-username/customer-segmentation.git)
    cd customer-segmentation
    ```

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    # On Windows
    .\venv\Scripts\activate
    # On macOS/Linux
    source venv/bin/activate
    ```

3.  **Install the required libraries:**
    ```bash
    pip install pandas numpy seaborn matplotlib scikit-learn scipy
    ```

---

## 🤝 Contributing
- Pull requests are welcome!
- For major changes, please open an issue first to discuss your ideas.

---

## 📜 License
- This project is licensed under the MIT License — see the LICENSE file for details.

---

## 💡 Author
### Your Name
📧 Email: [gayathri.manchikanti14@gmail.com](gayathri.manchikanti14@gmail.com)

🌐 GitHub: [https://github.com/ManchikantiGayathri](https://github.com/ManchikantiGayathri)
