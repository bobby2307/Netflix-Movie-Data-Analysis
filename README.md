# 🎬 Netflix Movie Analysis Project

This project analyzes a dataset of popular movies released on or relevant to Netflix using Python, pandas, seaborn, and matplotlib.

## 📁 Dataset

- Source: [TMDb API-based dataset]
- File: `mymoviedb.csv`
- Fields include: `Title`, `Release_Date`, `Popularity`, `Vote_Average`, `Genre`, `Original_Language`, etc.

---

## 📊 Key Visual Insights

### 1. Highest movies released over years
![Screenshot 2025-04-25 003239](https://github.com/user-attachments/assets/c8958521-e145-4d54-8567-61e9b3090663)


### 2. Top 10 Movie Genres
![Screenshot 2025-04-25 003045](https://github.com/user-attachments/assets/3f35e0d2-50d0-4527-9fb0-8e6683f8b362)


### 3. Ratings Distribution (Popular, Average, Below Average, Not Popular)
![Screenshot 2025-04-25 003108](https://github.com/user-attachments/assets/b712d560-548f-4937-86d3-d64d9a25c956)


### 4. Most Popular Movie
![Screenshot 2025-04-25 003212](https://github.com/user-attachments/assets/84154650-277b-4a05-a584-b34f9a9ce3e8)

### 5. Lowest Popular Movies
![Screenshot 2025-04-25 003224](https://github.com/user-attachments/assets/b8bf5924-0ae6-4939-be47-0d4b81edff65)




---

## 🛠 Technologies Used

- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Jupyter Notebook

---

##  Insights Summary

- Drama appears in over 14% of all Netflix titles, making it the most frequently released genre across the platform.
- In the top 25.5% of highly-voted movies (6250+ entries), Drama holds the lead again, accounting for 18.5% of popular titles.
- Spider-Man: No Way Home topped the popularity chart. It falls under Action, Adventure, and Science Fiction genres — a clear sign that high-budget, action-packed films 
  resonate strongly with Netflix audiences.
- The United States vs. Billie Holiday: Music, Drama, History and Threads: War, Drama, Science Fiction
  These genres, while critically important, appear to receive less mainstream attention or algorithmic promotion.
- The year 2020 saw the highest number of movies released, likely influenced by the COVID-19 pandemic’s impact on traditional film distribution and a shift toward streaming 
 content.


---

## 🚀 Run it Locally

```bash
git clone https://github.com/yourusername/netflix-movie-analysis.git
cd netflix-movie-analysis
pip install -r requirements.txt
jupyter notebook
