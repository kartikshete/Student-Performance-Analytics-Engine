📊 Student Performance Analytics Engine

A Python-based data analytics project built using NumPy, Pandas, and Matplotlib to analyze the academic performance of 500 students across 6 subjects. The project demonstrates how NumPy can efficiently perform statistical calculations, identify outliers, rank students, and visualize academic results.

🚀 Project Overview

The Student Performance Analytics Engine generates a dataset of 500 students with marks across six subjects and performs comprehensive statistical analysis to understand student performance.

It uses NumPy’s array operations, broadcasting, sorting, and statistical functions to process data efficiently.

✨ Features

* 📚 Dataset Generation: Generate marks for 500 students across 6 subjects.
* 📈 Statistical Analysis: Calculate sum, mean, median, standard deviation, and variance.
* 👨‍🎓 Student Performance: Calculate total marks and average marks for each student.
* 🔍 Outlier Detection: Use Z-scores to identify unusually high or low subject scores.
* 🏆 Student Ranking: Rank students based on their total marks.
* ⚡ NumPy Broadcasting: Calculate standardized scores using broadcasting.
* 📊 Data Visualization: Create charts to compare subject averages and top-performing students.
* 📁 CSV Export: Export analyzed results into a CSV file.
* 🔗 Array Operations: Combine marks, totals, and averages using NumPy’s hstack().

🛠️ Technologies Used

* Python — Programming language
* NumPy — Numerical computing and array operations
* Pandas — Tabular data analysis and CSV export
* Matplotlib — Data visualization
* Google Colab / Jupyter Notebook — Development environment

📂 Project Structure

Student-Performance-Analytics-Engine/
│
├── Student_Performance_Analytics.ipynb
├── student_performance_report.csv
└── README.md

Note: The notebook and CSV file should be added to the repository after creating and running the project.

📊 Dataset Details

The project generates a dataset containing:

* Students: 500
* Subjects: 6
* Marks: Generated using NumPy’s normal distribution and limited to the range of 0–100.

Subjects

1. Mathematics
2. Physics
3. Chemistry
4. Computer Science
5. English
6. Statistics

🧮 NumPy Concepts Demonstrated

Concept	Application
Array Creation	Generate a 500 × 6 marks matrix
np.sum()	Calculate total marks
np.mean()	Calculate average marks
np.median()	Find median scores
np.std()	Measure score variation
np.var()	Calculate score variance
Axis Operations	Analyze subject-wise and student-wise performance
Broadcasting	Calculate Z-scores
np.where()	Identify outliers
np.argsort()	Rank students
np.hstack()	Combine marks, totals, and averages

⚙️ How to Run the Project

Option 1: Google Colab

1. Open Google Colab.
2. Create a new notebook.
3. Copy the project code into the notebook.
4. Run the cells in order.
5. View the statistical results and visualizations.
6. Download the generated CSV report.

Option 2: Run Locally

1. Clone the repository

git clone https://github.com/YOUR_USERNAME/Student-Performance-Analytics-Engine.git

2. Navigate to the project directory

cd Student-Performance-Analytics-Engine

3. Install the required libraries

pip install numpy pandas matplotlib

4. Run the notebook

Open Student_Performance_Analytics.ipynb using Jupyter Notebook or VS Code and execute the cells.

📈 Expected Output

The project produces:

* Subject-wise statistical summaries.
* Student-wise total and average marks.
* Z-scores for each subject.
* Outlier detection results.
* A ranking of students based on total marks.
* Visualizations of subject averages and top-performing students.
* A CSV report containing analyzed student performance.

🎯 Learning Outcomes

Through this project, I practiced:

* Working with multidimensional NumPy arrays.
* Applying statistical functions along different axes.
* Using broadcasting for numerical calculations.
* Detecting outliers with Z-scores.
* Sorting and ranking data efficiently.
* Visualizing data with Matplotlib.
* Exporting structured results using Pandas.

🔮 Future Improvements

* Add an interactive dashboard.
* Support uploading real student datasets.
* Add subject-wise pass/fail analysis.
* Generate automated student performance reports.
* Compare academic performance across multiple classes.

👨‍💻 Author

Kartik Shete

* GitHub: @kartikshete

⸻

⭐ If you find this project useful, consider giving the repository a star!
