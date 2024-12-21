# ✨ Automated Insights with Fake Data

## 📋 Project Summary
This is the **Mid-Term Project** of my **Data Analytics Bootcamp**. I worked on demonstrating how to use Python for generating and analyzing fake CRM data that mimics real-world scenarios. The primary focus is on showcasing a structured approach to **data cleaning**, **exploration**, **statistical analysis**, and **visualization**. The insights and methods can easily be adapted by organizations using their real data to derive actionable insights.

📂 The dataset was generated using the **Faker library** and custom logic to simulate realistic CRM data, including fields like:
- 📈 UTM campaigns
- 🌐 Sources
- 💵 Revenue
- 📊 Deal stages
- 📍 Geographic information

---

## 📚 Libraries Used
- 📊 **matplotlib.pyplot**: For visualizing trends and insights.
- 🧹 **pandas**: For data manipulation and cleaning.
- 🃏 **faker**: To generate realistic fake data.
- 🎲 **random**: For adding variability to the dataset.
- 🕒 **datetime.timedelta**: To simulate realistic timeframes.
- 🧪 **scipy.stats.chi2_contingency**: For inferential statistical analysis.
- ➕ **numpy**: For mathematical operations and data handling.

---

## 🚀 Steps Taken

### 1️⃣ Data Generation
- 🃏 Used the **Faker library** to generate realistic CRM data, such as customer interactions, deal stages, and geographic information.
- 🎲 Incorporated randomness to mimic variability in real data.
- 📆 Simulated time-series data with **datetime.timedelta** for realistic trends.

### 2️⃣ Data Cleaning
- 🧹 While not needed with fake data, the script includes cleaning measures for when **real data** is uploaded.

### 3️⃣ Exploratory Data Analysis (EDA)
- 🔍 Investigated key patterns, including:
  - 💵 **Revenue distribution** across campaigns and sources.
  - 📆 **Temporal trends** to identify seasonality.
  - 🗺️ **Geographic breakdown** of revenue.
- 📊 Created visualizations like **bar charts**, **line plots**, and **heatmaps** to summarize findings.

### 4️⃣ Inferential Statistical Analysis
- 🧪 Performed a **chi-square test** using **scipy.stats.chi2_contingency** to analyze the relationship between campaign success and customer engagement.
- 📏 Calculated and interpreted effect sizes to quantify the significance of findings.

### 5️⃣ Visualizations
- 🖼️ Developed Python-based visualizations using **matplotlib** to:
  - 🌟 Highlight **top-performing campaigns and sources**.
  - 🔄 Visualize **deal pipeline stages and revenue contributions**.
- 📊 Created **Tableau dashboards** for interactive insights, including:
  - 📈 Campaign and source performance.
  - 🛠️ Pipeline efficiency and marketing attribution.

### 6️⃣ Insights Gained
- 🔍 Demonstrated the utility of **inferential statistics** to validate patterns observed during EDA.
- ⚡ Highlighted the power of combining **Python and Tableau** for comprehensive analysis and presentation.

---

## 🗂️ Project Structure
- 📁 **/data**: Contains the generated fake CRM data.
- 📁 **/scripts**: Python scripts for data generation, cleaning, and analysis.
- 📁 **/visualizations**: Tableau dashboards and Python-generated plots ([View Tableau Dashboard](#)).
- 📄 **/Notion**: Notion board including Agile setup and notes ([View Notion Board](#)).
- 📄 **README.md**: This file, documenting the project overview and workflow.

---

## 🛠️ How to Use
1. 🖥️ Clone this repository.
2. 🔄 Replace the fake data with your **real CRM data**, ensuring column names match.
3. 🏃‍♂️ Run the Python scripts to process and analyze the data.
4. 📊 Load your data into Tableau to generate updated dashboards.

---

## 🙏 Acknowledgments
A big thank you to **Ironhack** and to my instructors, **Isidre Munne-Bertran** and **Nicolas Mirabet**, for their invaluable guidance and support throughout this project. 💡
