# Weight & Height Analysis – Power BI Health Dashboard 🩺📊

## 👋 Hello!

This is a simple but insightful Power BI project where I explored health-related metrics such as **BMI**, **age**, and **gender-based health trends** using a sample dataset.

The goal? To turn raw height and weight data into an **interactive dashboard** that highlights meaningful health indicators and patterns in a clear, engaging way.

---

## 🎯 What I Set Out to Do

- Calculate **BMI** and **Age** from basic inputs (Height, Weight, Birth Year)
- Classify individuals into BMI categories: *Underweight, Normal, Overweight, Obese*
- Explore **how BMI differs across gender**
- Understand **age distribution** in the dataset
- Make everything interactive and easy to explore using slicers and filters

---

## 🧮 Key Calculations

### 1. **BMI (Body Mass Index)**  
`BMI = [Weight] / ([Height] * [Height])`  
*(Height in inches, Weight in pounds)*

### 2. **Age**  
`Age = YEAR(TODAY()) - [Born_Year]`

### 3. **BMI Categories**
- BMI < 18.5 → Underweight  
- 18.5 ≤ BMI < 25 → Normal  
- 25 ≤ BMI < 30 → Overweight  
- BMI ≥ 30 → Obese

---

## 📊 Dashboard Highlights

- **KPI Cards**: Average Height, Weight, and BMI
- **Bar Charts**: BMI comparison by Gender
- **Donut Chart**: Most and least common BMI categories
- **Histogram**: Age distribution – showing clusters and gaps
- **Slicers**: Easily filter the entire dashboard by Gender
- **Formatted Table**: Clean summary of each person's key health indicators with conditional formatting

---

## 🛠 Features I’m Proud Of

✔️ Custom BMI gauge  
✔️ Clean layout and logical flow  
✔️ Color-coded visuals that make insights pop  
✔️ Interactive filters that make exploration fun  

---

## 🖼 Dashboard Preview

### 📍 Card Insights – Average Height, Weight, and BMI  
![Card Insights](screenshots/card_insights.png)

### 📍 Comparative Analysis – BMI by Gender  
![Comparative Analysis](screenshots/comparative_analysis.png)

### 📍 Detailed Table – Health Indicators Per Person  
![Detailed Table](screenshots/detailed_table.png)


---

## 📆 Date of Completion

**Tuesday, 13th May 2025**

---

## 🙋‍♀️ About Me

I'm Tiffany Karanja, a budding data analyst passionate about transforming raw data into simple, impactful stories through dashboards and visuals.

If you'd like to connect or see more of my work – let’s chat!
