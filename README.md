# Udemy Courses Analysis - Exploratory Data Analysis (EDA)

This project is an exploratory data analysis (EDA) focused on identifying trends among courses listed on Udemy. Using a dataset of course metrics, the notebook walks through data cleaning, general exploration, and data visualization using Seaborn and Matplotlib to look at course subjects, pricing, subscriber counts, and text patterns.


## Project Structure

The repository includes:
* **`5-Udemy-Courses (with seaborn)-Answers.ipynb`**: The Jupyter Notebook containing the data cleaning steps, analytical questions, and visualization code.
* **`5-udemy_courses (1).csv`**: The dataset containing courses across different subjects with columns for pricing, subscribers, reviews, and duration.


## Tech Stack & Dependencies

* **Language:** Python 3.x
* **Libraries Used:** Pandas, NumPy, Seaborn, Matplotlib
* **Environment:** Jupyter Notebook / JupyterLab


## Dataset Overview

The `5-udemy_courses (1).csv` dataset tracks course postings using the following 12 attributes:
* **course_id:** Unique numeric identifier for the course.
* **course_title:** The name of the course.
* **url:** The direct web link to the course page.
* **is_paid:** Boolean flag indicating if the course is paid (True) or free (False).
* **price:** The price listed for the course.
* **num_subscribers:** Total number of student enrollments.
* **num_reviews:** Total count of written user reviews received.
* **num_lectures:** Total number of lectures included in the syllabus.
* **level:** Target student experience tier (All Levels, Beginner, Intermediate, Expert).
* **content_duration:** Total length of video content in hours.
* **published_timestamp:** The exact date and time the course went live.
* **subject:** Broad topic category (e.g., Web Development, Business Finance, Musical Instruments, Graphic Design).


## Key Tasks & Insights Covered

The notebook steps through specific data discovery objectives and plots key findings:
1. **General Profiling:** Inspecting total rows, datatypes, shape, and checking for duplicate entries.
2. **Subject Distributions:** Counting unique subject tracks to see which categories have the highest number of courses available.
3. **Popularity Analysis:** Finding the absolute most popular courses based on the total number of subscribers and reviews.
4. **Price vs. Engagement:** Comparing free courses against paid options to see how pricing shifts enrollment numbers.
5. **Seaborn Visualizations:** Plotting data distributions, categorical counts, and checking timelines by parsing the published year to trace platform growth over time.
6. **Text-Based Filtering:** Isolating and analyzing courses specifically related to programming terms like "Python" using string matching.


## How to Run This Project

Choose the option below that works best for you:

### Option 1: The Quick Way (No Git Required)
1. Click the green **Code** button at the top right of this GitHub page.
2. Click **Download ZIP** and unzip the files into a folder on your computer.
3. Move your dataset (`5-udemy_courses (1).csv`) into the same folder if it isn't already there.
4. Open your terminal or command prompt, navigate to that folder, and run:
   ```bash
   pip install pandas numpy seaborn matplotlib notebook
   jupyter notebook


## Author

Priya Patel  
Aspiring Data Analyst  
Email: yourmail@gmail.com  
GitHub: [priyapatel96140](https://github.com/priyapatel96140)  

If you like this project, feel free to give it a star!
