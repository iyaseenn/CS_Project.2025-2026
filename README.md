# Foundations of Computer Science – Project  
## MS Data Science, 2025–26

---

### 📊 Trending YouTube Dataset

## 📄 Project Description

This project analyzes the **Trending YouTube Dataset** using Python and Pandas.  
The goal is to perform data cleaning, aggregation, and analysis across multiple countries and time periods.

---

## 🧩 Project Tasks

1. Create a single dataframe by concatenating all input CSV files, adding a column called **country**.

2. Extract all videos that have **no tag**.

3. For each channel, determine the **total number of views**.

4. Save all rows with:
   - disabled comments and disabled ratings, or  
   - `video_error_or_removed = True`  
   in a new dataframe called **excluded**, and remove those rows from the original dataframe.

5. Add a **like_ratio** column storing the ratio between the number of likes and the number of dislikes.

6. Cluster the **publish time** into **10-minute intervals**  
   (e.g. from 02:20 to 02:30).

7. For each time interval, determine:
   - the number of videos  
   - the average number of likes  
   - the average number of dislikes  

8. For each **tag**, determine the number of videos.  
   *(Note: the tags column contains a string with multiple tags.)*

9. Find the **tags with the largest number of videos**.

10. For each **(tag, country)** pair, compute the **average likes/dislikes ratio**.

11. For each **(trending_date, country)** pair, find the video with the **largest number of views**.

12. Divide **trending_date** into three separate columns:
    - year  
    - month  
    - day  

13. For each **(month, country)** pair, determine the video with the **largest number of views**.

14. Read all **JSON files** containing video categories.

15. For each country, determine how many videos have a category that is **not assignable**.

---

## 🛠 Technologies Used

- Python  
- Pandas  
- Jupyter Notebook  

---

## 👤 Author
Muhammad Yaseen,  Uzakbay Dias and Millaniyage Thilina Lakshan Peiris

- **Program:** MS Data Science  
- **Academic Year:** 2025–26
