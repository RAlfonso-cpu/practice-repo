---
title: "Introduction to Data Science - HW 2"
author: "Ryan Alfonso - `Ralfonso1717@floridapoly.edu`"
output: html_notebook
editor_options: 
  chunk_output_type: inline
---



# Problem 1 (30 points)

During class you completed an activity in which you practiced `git` commands and operations (such as forking a repository, cloning it using `git clone`, and uploading changes using `git push`).

In this exercise you are asked to modify the `flpoly_student.md` file you worked during class, and format it using the **markdown** tools discussed in class. You must **create a table** that shows the courses you are currently enrolled in, using for the headers of the table: 

- Prefix: in bold letters (such as **COP**)
- Number: in bold letters (such as **2073**)
- Name: in italics (such as _Introduction to Data Science_)
- Credits (such as 3)

a. Make sure your GitHub repo (`practice-repo/`) shows the results of your updated file (remember to use the commands `git add .` , `git commit -m "YOUR MESSAGE"`, and `git push`) 

b. Include a link to your GitHub repo in this document.

c. Take a screenshot of the GitHub repo, add the screenshot file to the repo, and include it in this document (review how to insert a picture using markdown)

## Ryan Alfonso
### Summer 2021 
## DSBA student at [Florida Polytechnic University](https://www.floridapoly.edu) currently enrolled in: 


**Course Number**     **Course Name**
--------------        --------------
**1**                 _Intro to data science_
**2**                  _pre calculus_


**Hobby number**  **Hobbies:**
---------------   -----------
1                      Science
2                      Sports
3                     the gym<https://www.floridapoly.edu>

***

> Last modified: 2021/07/20



# Problem 2 (30 points)

For this problem, you are asked to create a list of **3 concepts** you have learned about so far this semester. Include the name of the course as a sub-heading (that is, using `##`), and the concepts as an unordered list. Include a link to information about at least one of the concept you listed (for example a link to the Wikipedia page about that concept/topics).

## Intro to data science

- Values
- String
- Lists
- https://floridapolytechnic.instructure.com/courses/5418/files/3341661?module_item_id=240304&fd_cookie_set=1




# Problem 3 (40 points)

In this problem you will practice some basic R operations. Include solutions to each items by inserting a new R chunk of code (make sure you run the chunk so that the output is displayed)

(a) Create a variable called `my_name` that contains your preferred name.

```{r}
my_name <- 'Ryan Alfonso'

```


(b) Create a variable called `name_length` that holds how many letters are in `my_name`.

library(stringr)

```{r}

name_length <- nchar(my_name)
name_length
```


(c) Show which value is bigger: $e^\pi$ or $\pi^e$. 



$e^\pi$ > $\pi^e$




  
(d) Define a function called `add_three` that takes a single argument and returns a value with 3 units added to the original input.
```{r}
add_three <- name_length + 3
```


(e) Use the colon operator `:` to create a vector `v` of numbers from 10 to 49. Find the length of this vector using the `length()` function.

```{r}
v <- (10:49)
```


(f) Use the `seq()` function to produce a range of number from -5 to 10 in 0.5 increments.

```{r}
half <- seq(-5,10,.5)
```

