# 📊 Student Performance Analysis Dashboard

This project is an interactive **Student Performance Analysis Dashboard** built using **Power BI** and **Python**. It visualizes and analyzes key student metrics such as CGPA, attendance, placement status, and participation in extracurricular activities. The dashboard helps educators, administrators, and placement cells make informed decisions by identifying trends, top performers, and students needing academic support.

---

## 📁 Dataset Overview

The dataset contains the following fields for each student:

- `StudentID`
- `Name`
- `Department` (CSE, ECE, ME, CIVIL)
- `CGPA`
- `Attendance (%)`
- `Placement Status` (Yes / No / Pending)
- `Internship Participation` (Yes / No)
- `Sports Participation` (Yes / No)
- `Mentor Meetings Attended`
- `Gender`

---

## 🚀 Key Features

- **Topper Card**: Displays the top-performing student and their CGPA.
- **Department-wise CGPA**: Bar chart showing average CGPA by department.
- **Placement Insights**: Donut chart for placement status and counts.
- **Attendance vs CGPA**: Scatter plot analyzing correlation.
- **Sports Analysis**: Compare CGPA of sports vs non-sports participants by gender.
- **Mentorship Impact**: Line chart showing CGPA trend vs mentor meetings.
- **Comprehensive Table**: Displays full student details with filtering.
- **KPI Cards**: Highlights key performance indicators like topper name & CGPA.

---

## 📷 Dashboard Preview

![Dashboard Preview](images/dashboard.png) <!-- You can replace the path if your image is in another folder -->

---

## 🛠️ Tools and Technologies Used

- **Power BI Desktop** – for creating and publishing the dashboard
- **Microsoft Excel** – for storing and preprocessing student data
- **Python** (Optional) – used for additional visualizations using:
  - `pandas`
  - `matplotlib`
- **SQL** (Optional) – for normalized table creation and data modeling

---

## 🧠 How to Use This Project

### ✅ Requirements
- Power BI Desktop installed
- Python (for optional Python visuals)
- Excel (for editing the dataset)

### 📦 Steps
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/student-performance-dashboard.git
   cd student-performance-dashboard
