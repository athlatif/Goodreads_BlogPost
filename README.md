# Data Science Blog Post - Goodreads

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Acknowledgements](#Acknowledgements)

## 1. Installation <a name="installation"></a>

- Python versions 3.*.
- Libraries:
- Pandas.
- matplotlib.
- seaborn.

## 2. Project Motivation <a name="motivation"></a>
In this project, I was curious about the factors that motivate users and people in general to read a book. Goodreads is a website and a social network where users share reviews and find new books. I tried to answer the following:

1. Are classic books better than modern books?
2. What is the most popular genre? 
3. Does the number of reviews per book and the average rating influence users’ choices of books to read?


## 3. File Descriptions <a name="files"></a>  

1. Notebook file 
2. Data files:
- to_read.csv provides IDs of the books marked "to read" by each user, as user_id,book_id pairs, sorted by time. There are close to a million pairs.
- books.csv has metadata for each book (goodreads IDs, authors, title, average rating, etc.).
- book_tags.csv contains tags/shelves/genres assigned by users to books. Tags in this file are represented by their IDs. They are sorted by goodreads_book_id ascending and count descending.
- tags.csv translates tag IDs to names.

## 4. Results <a name="results"></a>
Please check the following blog post [Here](https://medium.com/@athlatif/what-motivates-readers-to-choose-their-next-book-insights-on-goodreads-dataset-41681e9720f7)

## 5. Acknowledgements<a name="Acknowledgements"></a>
Data credits [Here](https://github.com/zygmuntz/goodbooks-10k) 


