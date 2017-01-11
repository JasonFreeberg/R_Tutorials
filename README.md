# PSTAT 193 Syllabus
### R Programming Tutorials -- Winter 2017

**Instructor**:
Professor [Raya Feldman](http://www.pstat.ucsb.edu/faculty%20pages/FELDMAN.htm)
- feldman [at] pstat.ucsb.edu
- South Hall 5516

**Undergraduate Assistants**:
- [Jason Freeberg](https://www.linkedin.com/in/jfreeberg), freeberg [at] umail.ucsb.edu
- [Aaron Nguyen](https://www.linkedin.com/in/aaronknguyen), aaronknguyen [at] umail.ucsb.edu

**Lecture Time and Location**:
Wednesdays 7:00pm - 8:50pm, Girvetz 2128

**Prerequisites**: Students must be of upper division standing or recieve consent from the instructor. Students should also have programming experience, either through UCSB classes or personal projects.

**Grading**: This class is offered for 1 unit, Pass/No Pass. Students will recieve a passing grade for attending *and* actively participating in **9** lectures. 
  - During lecture on February 22nd there will be a review examination. Scoring above 75% on this exam allow a student to make up one (1) previous missed lecture attendance. This cannot be used towards future missed attendances after February 22nd.

**Topics**: This class will cover the basics of the R programming language and apply the material to real-world problems and data. In the first weeks, we will explore the fundamental objects and syntax of R. Next, we will learn how to load and format data. In the last weeks we will cover the basics of [ggplot2](https://en.wikipedia.org/wiki/Ggplot2), a popular data visualization package for R.

**Textbooks and other resources**: There are no required textbooks for this course. However, the following are all great resources for students learning the R language.
- [Jupyter Notebook Docs](http://jupyter-notebook.readthedocs.io/en/latest/) has all the answers for installing, running, and saving Jupyter Notebooks
- [DataCamp.com](https://www.datacamp.com/courses?learn=r_programming) is an interactive programming tutorial website and will be used for most homework assignments
- [The R Book](https://www.cs.upc.edu/~robert/teaching/estadistica/TheRBook.pdf) is a great R reference manual
- [PSTAT's Piazza Group](https://piazza.com/ucsb/other/pstat199) is where students can ask and answer R programming questions

**Software**: Students are required to download following free programs/software and ensure they are running properly on their machine.
  - R, the programming language for the course
  - RStudio, the IDE for R
  - Jupyter, an interactive notebook we will use in every class
    - Install this [R Kernel](https://github.com/IRkernel/IRkernel) for Jupyter
  - [Video Walk-Through](https://youtu.be/I9a9Jj2A95g)

### Lesson Plan

**Week 1**, Jan. 11: Welcome
- About this class
  - Students should have a programming background of some sort
  - Grading critera for the class
  - Suggested homework for the quarter
- Ensure all students are set up with course materials
  - R and RStudio
  - Jupyter
    - Along with the R kernel
  - DataCamp.com
    - $9 Monthly Subscription [Student Discount]  (hopefully)
- Why R?
- Cover the basics of running a Jupyter Notebook
  - Command line argument: "jupyter notebook"
  - [Keyboard shortcuts](https://www.cheatography.com/weidadeyue/cheat-sheets/jupyter-notebook/)
- **Suggested Homework:**

**Week 2**, Jan. 18: Basics of R -- <em>Jason</em>
- R's data types
- Vectors
  - Selection
  - Non-nesting
- Writing clean code
  - Clean bad code for practice
- **Homework:**
  - Sign up for DataCamp.com
  - DataCamp: <a href="https://www.datacamp.com/courses/free-introduction-to-r">Introduction to R</a>
    - Chapters 1, 2, 3

**Week 3**, Jan. 25: Lists and User-Defined Functions (UDFs) -- *Aaron*
- Built-in Functions
  - Numerical / Statistical
  - Segway into students making the functions themselves.
- UDFs
  - Make your code DRY
  - Divide and conquer
- **Exercise:** Mean and Variance
- Lists
  - Generating
    - Named lists
  - Subsetting
  - Use cases
- **Homework:**
 - DataCamp: <a href="https://www.datacamp.com/courses/free-introduction-to-r">Introduction to R</a>
    - Chapters 4 and 5: Factors and Dataframes
 - DataCamp: <a href="https://www.datacamp.com/courses/intermediate-r">Intermediate R</a>
    - Chapters 1 to 3: Contiditionals and Control Flow, Loops, and Functions
 
**Week 4**, Feb. 1: Data Frames -- *Aaron*
- Conditioning and Subsetting
  - Syntax: *dataframe[rows, columns]*
- New columns/rows
- **Excercise:** 
  - Create a clone of an existing data frame (or create your own if time permits)
  - Manipulate the data frame by adding new and old columns/rows
  - Sorting your data frame
- Helpful functions
  - head(), summary(), glimpse(), is.na(), ...
- **Excercise:** 
  - Use these newly learned functions to find specific information in your data frame
- **Homework:**

**Week 5**, Feb. 8th: Aggregating Data -- *Jason*
- Using dplyr
  - Functions for basic analysis
  - Grouping data with <code>group\_by()</code>
  - The piping operator, <code>%>%</code>
- Joining dataframes
  - inner, outer, left, and right
- **Homework:**
  - DataCamp: <a href="https://www.datacamp.com/courses/dplyr-data-manipulation-r-tutorial">Data Manipulation in R with dplyr</a>
    - All chapters
 
**Week 6**, Feb. 15th: Loading and Cleaning Data -- *Jason*
- Formats
  - .csv and other delimited formats
  - JSON
- Techniques for checking data
  - max and min values
  - unique factor levels
- Regular Expressions
  - regex101.com
  - gsub()
- **Homework:**
  - DataCamp: <a hre="https://www.datacamp.com/courses/cleaning-data-in-r">Cleaning Data in R</a>
  - Work through [RegexOne.com](https://regexone.com)'s free online exercises.
 
**Week 7**, Feb. 22nd: Review Exam -- *Jason and Aaron*
- Review Examination
  - Short Answer: Fill in the blank and multiple choice (8 questions)
  - Long Answer: Writing functions and correcting code (2 questions)
- Tour of RStudio
  - Main components
  - Helpful tips
    - Console <code>^</code>
    - Using the tab key
    - Organizing code with <code>####</code>
- **Homework:**
  - Complete all assigned Datacamp exercises up to this point.
  - DataCamp: Finish <a href="https://www.datacamp.com/courses/intermediate-r">Intermediate R</a>
 
**Week 8**, Mar. 1st: ggplot2 (Part I) -- *Jason*
- Layering
  - Adding layers
- Mapping
  - Basic aesthetics
- **Homework:**

**Week 9**, Mar. 8th: ggplot2 (Part II) -- *Jason*
- Deeper dive into ggplot2
- Mapping multiple attributes
- Static vs. Dynamic mapping
- Layering generalized linear models
- **Homework:**

**Week 10**, Mar. 15th: The Good and Bad of R -- *Jason*
- R's strengths and weaknesses
    - Large memory footprint
    - Difficult to use in production
    - NULL columns
- Compare R to other programming languages dominant in data science
    - Python using Pandas and matplotlib
- Where to go now
    - Kaggle competitions
    - Personal projects
    - Shiny applications
