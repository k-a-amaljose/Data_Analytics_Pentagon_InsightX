# Data-analyst-workshop
## Data Analytics Project
This project analyzes the Top 1000 IMDb movies dataset to identify trends in genre popularity, box office performance, and audience preferences. The analysis examines which genres and directors are most strongly associated with a film’s success.

Based on these insights, the report provides recommendations on the types of movies the studio should prioritize producing and releasing over the next decade.

The analysis was carried out using **Python**, with libraries including **Pandas** for data manipulation and **Matplotlib** for result visualization.
## Working
### Task 1
**Goal** : Task 1 analyses the IMDb Top 1000 movies dataset to identify the top 10 directors who achieved the highest total box office revenue, considering only directors with a minimum of three movies.<br>

**Methodology** : The dataset is first cleaned by removing commas from the Gross column and converting it into a numeric data type. Movies with invalid or missing gross values are handled using coercion. The data is then grouped by director to calculate the total gross revenue and the number of movies directed by each individual. Directors with fewer than three movies are excluded to ensure meaningful comparison. The directors are then sorted based on total gross revenue, and the top 10 performers are selected.
The results are visualised using a bar graph, with distinct colors and a dark-themed background to enhance clarity and readability.
### Task 2
**Goal** : A bubble chart shows the result, with rating on the x-axis, revenue on the y-axis, and bubble size showing how many movies are in each genre. This makes it easy to compare genres by quality and profit.<br>

**Methodelogy** :This task uses the IMDb Top 1000 Movies dataset to compare movie genres using ratings and box-office revenue. The data is cleaned by splitting multiple genres, removing missing values, and converting revenue into numbers. Genres are grouped to find average rating, average revenue (in $100M), and movie count, keeping only genres with at least ten movies.
### Task 3
**Goal** : Task 3 analyses movies released over the time span of 3 decades  (1990 - 2019) to identify the genre most likely to achieve high box office revenue.<br>

**Methodology** : The provided Dataset is first cleaned by converting gross revenue into numeric datatype. The movies released after 1990 are then selected for the analysis. Since many movies  belong to multiple genres, the dataset is exploded to separate each movie-genre pair into separate rows. The average gross revenue for each genre for each year is calculated and the top performing genre for each year is identified. 
The results are visualised using a bar graph with different colors assigned to different genre for clarity and readability.

## Files
The repo consists of 5 files.
- **Data_Analysis_Report.ipynb** - The documented report after analysing the data 
- **Data_Analysis_Task_1.ipynb** - The code file used to $clean$ the data provided and create bar graph of top 10 dirtectors by Total Gross Revenue
- **Data_Analysis_Task_2.ipynb** - Code used to make bubble Graph of different genre of movies and their rating
- **Year_wise_top_genre_Analysis.ipyjnb** - A bar graph of the highest grossing genre for each year and the code used to make it
- **README.md** - The one you are reading right now!

## Our Team
We're five members who are part of $GCEK$ studying in $S2 CSE$ .<br>
😽 $${\color{#e78284}Adithya}$$ $${\color{#e78284}Shankar -}$$ https://github.com/Adithya-D2 <br>
🤖 $${\color{#7287fd}Amaljose}$$ $${\color{#7287fd}K}$$ $${\color{#7287fd}Augustin -}$$https://github.com/k-a-amaljose <br>
🧠 $${\color{#a6d189}Aleema}$$ $${\color{#a6d189}Majinas -}$$https://github.com/Busy-Coding-n-Debugging<br>
💀 $${\color{#e5c890}Akhil}$$ $${\color{#e5c890}Chandran}$$ $${\color{#e5c890}AV - }$$ https://github.com/ConfidentHero <br>
👻 $${\color{#ca9ee6}Adwaid}$$ $${\color{#ca9ee6}EV -}$$ https://github.com/AD-EV<br>

##  Goal
Our goal through this project is to improve our skills by gaining practical experience through collaboration while having $${\color{#a6d189}F}$$ $${\color{#e78284}u}$$ $${\color{#e5c890}n}$$ $${\color{#8caaee}!}$$   
