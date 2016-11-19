# PSTAT 193 Syllabus
### R Programming Tutorials -- Winter 2017

**Instructor**:
Professor [Raya Feldman](http://www.pstat.ucsb.edu/faculty%20pages/FELDMAN.htm)
- feldman [at] pstat.ucsb.edu
- South Hall #5....

**Undergraduate Assistants**:
- [Jason Freeberg](https://www.linkedin.com/in/jfreeberg) -> freeberg [at] umail.ucsb.edu
- [Aaron Nguyen](https://www.linkedin.com/in/aaronknguyen) -> ..... [at] umail.ucsb.edu

**Lecture Time and Location**:
Wednesdays 7:00pm - 8:00pm, [room]

**Prerequisites**: Students must be of upper division standing or recieve consent from the instructor. 

**Grading**: This class is offered for 1 unit, Pass/No Pass. Students will recieve a passing grade for attending *and* actively participating in **8** lectures. 

**Topics**: This class will cover the basics of the R programming language and apply the material to real-world problems and data. In the first weeks, we will explore the fundamentals and syntax of R. Next, we will learn how to load and format data. In the last weeks we will cover the basics of [ggplot2](https://en.wikipedia.org/wiki/Ggplot2), a popular data visualization package for R.

**Textbooks and other resources**: While none are required, the following are all great resources for anyone learning the R language.
- [Jupyter Notebook Docs](http://jupyter-notebook.readthedocs.io/en/latest/) has all the answers for installing, running, and saving Jupyter Notebooks
- [DataCamp.com](https://www.datacamp.com/courses?learn=r_programming) is an interactive programming tutorial website (much like Codecademy)
- [The R Book](https://www.cs.upc.edu/~robert/teaching/estadistica/TheRBook.pdf) is a great R reference manual
- [PSTAT's Piazza Group](https://piazza.com/ucsb/other/pstat199) is where students can ask and answer R programming questions

### Lesson Plan

**Week 0:** Before Winter Quarter
- Students are required to download following programs and ensure they are running properly on their machine.
  - R, the programming language for the course
  - RStudio, the IDE for R
  - Jupyter, an interactive notebook we will use in every class

**Week 1:** Welcome
- Why R?
- About the class
  - Students should have a programming background of some sort
  - Grading critera
  - Suggested homework
- Ensure all students set up with course materials
  - R, RStudio
  - Jupyter, course notebooks
    - Download this repo
    - Install this [R Kernel](https://github.com/IRkernel/IRkernel) for Jupyter
  - DataCamp.com
    - Student discount (hopefully)
- Cover the basics of running a Jupyter Notebook
  - Command line argument: "jupyter notebook"
  - Keyboard shortcuts
- **Suggested Homework:**

**Week 2:** Basics of R
- Intro to Basic Coding Jargon (e.g. logical, numeric, character, strings, etc.)
- Data Types
- Syntax
  - Basic Operations and Arithmetic
  - Logical Operators and Arguments
- Factors
- Vectors
- Matrices (?)
- **Suggested Homework:**
  - Sign up for DataCamp!
      - Recommended: Using the academic student discount provided by the class, sign up premium access to all of DataCamp's interactive lessons!
  - [FREE] Start the Introduction to R Chapter and do as much as you can.

**Week 3:** Lists and User-Defined Functions (UDFs)
- Built-in Functions
  - Numeric / Statistics 
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
- **Suggested Homework:**
  - Continue progress on DataCamp (continue "Introduction to R", you might get a sneak peek of next week's lesson!). 
 
**Week 4:** Data Frames
- Conditioning and Subsetting
  - Syntax: *dataframe[rows, columns]*
- New columns
- Helpful functions
  - head(), summary(), glimpse(), is.na(), ...
  - dplyr
- **Suggested Homework:**

**Week 5** Aggregating Data
- Using dplyr
  - Piping operator
  - Basics
- Grouping and Joining
- **Suggested Homework:**
 
**Week 6:** Loading and Cleaning Data
- Formats
  - .csv
  - json
- Regular Expressions
  - gsub()
- **Suggested Homework:**
 
**Week 7:** Review
- Review all material up until now, lots of in-class exercises
- **Suggested Homework:**
 
**Week 8:** ggplot2 (Part I)
- Layering
- Mapping
- **Suggested Homework:**

**Week 9:** ggplot2 (Part II)
- More examples and exercises
- **Suggested Homework:**

**Week 10:** Quirks and Pitfalls of R
- R's strengths and weaknesses
- Identify some odd features of the R language
- Comparison to Python using Pandas and matplotlib
