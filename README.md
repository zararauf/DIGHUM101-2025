# DIGHUM101-2025: Python Programming for Digital Humanities

Course Catalog: [Python Programming for Digital Humanities 2025 Summer Session A](https://classes.berkeley.edu/content/2025-summer-dighum-101-001-lec-001)

Offered Through: [UC Berkeley D-Lab](https://dlab.berkeley.edu/)

Instructor: [Merve Tekgürler](http://mervetekgurler.com/)

**Dates:** May 27 – July 3, 2025
Mondays, Tuesdays, Wednesdays, and Thursdays

**Time:** 1:00 – 3:00 PM

**Instruction Mode:** Online

**Office Hours:** Mondays and Wednesdays after class or by appointment on Zoom

**Prerequisites:** None!

**Requirements:** Computer, Zoom account, and Internet connection.

## Course Description

The digital and data revolution has begun to transform the study of the humanities by introducing new archival data sources, tools and methods, and modes of analysis. In this applied course, students will learn foundational knowledge of Python, the leading programming language in Digital Humanities and data science. By the end of this course, students will be able to program Python in Jupyter Notebooks, analyze and visualize data for purposes of computational text analysis and gain a fundemental understanding of machine learning.

## Learning Goals

The goal of this course is to teach you basic principles for conducting professional research in the Digital Humanities. You will learn how to program Python in Jupyter Notebooks to access, explore, visualize, and analyze data in humanities contexts. You are strongly encouraged to concurrently enroll in [DIGHUM 100 – Theory and Methods in the Digital Humanities](https://classes.berkeley.edu/index.php/content/2025-summer-dighum-100-001-lec-001) to complement this experience with a strong theoretical foundation. By the end of this course, you will learn:

- A variety of Pythonic approaches to explore questions in the humanities;
- How to understand data more holistically, its generative process and lifecycle;
- Strategies for organizing research projects based on your interests;
- Methods for data acquisition and visualization, computational text analysis, and machine learning;
- The importance of developing a critical lens in your field of study.

## Course Materials

Course materials and instructions are on bCourses and [the course Github repository](https://github.com/dlab-berkeley/DIGHUM101-2025). The repository has the following structure:

### Directories

- Week {1-6}/ contains the Jupyter notebooks used in class for each week
- Data/ contains several example datasets we will work through together during class time and for challenge questions. Think bigger for your project!

### Files

- `environment.yml` contains code for setting up the class conda environment
- `README.md` contains the text on this page
- `assignment_descriptions.md` contains detailed descriptions of the course assignments

## Course Policies

### Attendance

This course is synchronous and attendance is required. Asynchronous exceptions will be considered on a case-by-case basis, such as for those living in distant time zones. Attendance will be tracked through Zoom sign-ins.

Alongside attendance, students are expected to be present and participating in the class. Our course is a practicum, which means that we will spend most of our class time solving coding problems and analyzing solutions. Come prepared to join the class discussions. You are encouraged to ask questions if something is not clear or if you would like to see more examples. You are welcome to answer your colleagues' questions. Let's keep a lively conversation!

### Collaboration

Students are encouraged to discuss assignments and collaborate with one another. However, unless otherwise stated, students are expected to submit individual work and disclose any collaboration.

### Generative Artificial Intelligence

Generative AI refers to technology that can create new content such as text, images, or code, based on user input. Since the main learning goal of this class is to become fluent in coding with Python, students are expected to solve the coding exercises and assignments on their own. They can however use AI models to help with their assignments, as long as the answers are their own and they disclose the use of AI. [AI at UC Berkeley](https://technology.berkeley.edu/AI) contains useful information and guides about Berkeley's AI policies.

This course introduces students to Python and in 2025 any introduction to coding course should emphasize AI literacy. On the first day of class, we will go over what generative AI and where it might help the learning goals of our course and where it might hinder your learning process.

## Grading

|                               |       |
|-------------------------------|-------|
| **Attendance and Participation** | 10%    |
| **Individual Project**         |        |
| └─ Short Paper                 | 20%    |
| └─ Presentation                | 10%    |
| **Group Project**              |        |
| └─ Topic Statement             | 10%    |
| └─ Short Paper                 | 15%    |
| └─ Repository                  | 25%    |
| **Video Reflection**           | 10%    |

Grading is straight scale: A=90-100; B=80-89; C=70-79; D=60-69; F<60

## Software Installations and Set Up

*Please have this complete before first day*

In this class, we will learn to use the programming language Python. Just as you use a text editor like Microsoft Word for writing, you'll need a code editor to write and manage your code. In our case, we’ll be using Visual Studio Code (VS Code), a user-friendly and free editor designed for programming.
To install and manage additional tools or libraries (also called packages) that extend Python’s functionality, we will use a package manager—specifically, Conda. Conda allows us to install, update, and organize the various packages we’ll need throughout the course.
Finally, we will be using GitHub, a platform for sharing and collaborating on code. GitHub allows you to store your code in the cloud, track changes over time, and work with others on shared projects, similar to Google Docs.

Please follow the steps below to install the required software:

- [ ] Miniconda
  - Download [Miniconda Installer](https://www.anaconda.com/download/) You have to scroll all the way down to the Miniconda installer
  - Make sure to choose the correct Miniconda for your computer (Windows vs Mac) and your chip architecture (Mac Intel or Mac Apple) and download the Graphical Installer (not command line)
  - Refer to [getting started](https://www.anaconda.com/docs/getting-started/miniconda/main) and [installation](https://www.anaconda.com/docs/getting-started/miniconda/install) guides for questions

- [ ] Python
  - If you are using Mac, you should already have Python installed on your computer.
  - If you are using Windows, Miniconda should take care of the Python installation. If not, please follow the instructions here to install [Python](https://realpython.com/installing-python/)
  - Make sure that you are running Python 3.12

- [ ] GitHub
  - Use your student email address to create a [GitHub account](https://github.com/)
  - Follow the instructions on [this page](https://docs.github.com/en/education/about-github-education/github-education-for-students/apply-to-github-education-as-a-student) to apply for a GitHub Pro account, which is free for students

- [ ] Virtual Studio Code
  - Download [VS Code](https://code.visualstudio.com/)
  - Sign into VS Code with your GitHub account

- [ ] Git Bash (Windows users only – optional)
  - If you'd like a Unix-style terminal experience, install [Git Bash](https://gitforwindows.org/)
  - Mac users already have Terminal built-in
  - We will use the Terminal inside VS Code, so Git Bash might not be necessary for in-class exercises

## Conda Environment

*We will run this together in class*

A Conda environment is like a workspace or container on your computer that keeps all the packages you need for a project in one place.

When you're working on a coding project, you will need specific tools, called packages. Each package serves a different function. For example, numpy is for doing advanced math, pandas are for handling data and tables, matplotlib is for making graphs, and nltk is for analyzing language. These tools need to work with a specific version of Python and may even have different versions depending on the project. If you install everything globally (for your entire computer), things can break—especially when different projects need different versions of the same tool. Think of environments as toolboxes, that you set up with select tools for each project.

A conda environment keeps your project’s tools and settings separate from everything else on your computer. It helps avoid version conflicts and makes it easy to share your setup with others, using an environment.yml file.

We will create a conda environment for this class and call it **dighum101**. You will install this enviroment once, using the steps below and activate it every time we are coding in this class.

Follow these steps to set up your Python environment for this course.

### 1. Copy the repository

Clone or download this repository to your computer.
    Click the green "Code" button in the top right of the repository information.
    Click "Download Zip".
    Extract this folder to a location on your computer that you will **not change** later on.
Open this repository in VS Code

### 2. Create the Conda environment

Open a terminal in Visual Studio Code, navigate to the folder where the `environment.yml` file is located, and run:

`conda env create -f environment.yml`

### 3. Activate the Conda environment

`conda activate dighum101`

### 4. Make the environment available as a Jupyter kernel

`python -m ipykernel install --user --name dighum101`

### 5. Deactivate the environment when you're done

`conda deactivate`

## Past Courses and Related Links

Parts of these materials were created by Evan Muzzall, 2018-2021, Brooks Jessup, 2021, Tom van Nuenen, 2022, Prashant Sharma 2023-2024.

- https://github.com/dlab-berkeley/DIGHUM101-2024
- https://github.com/dlab-berkeley/DIGHUM101-2023
- https://github.com/dlab-berkeley/DIGHUM101-2022
- https://github.com/dlab-berkeley/DIGHUM101-2021
- https://github.com/dlab-berkeley/DIGHUM101-2020
- https://github.com/dlab-berkeley/DIGHUM101-2019
- https://github.com/dlab-berkeley/DIGHUM101-2018

Newly developed materials (Summer 2025, Merve Tekgürler) make use of the following repositories and resources:

- https://github.com/dlab-berkeley/Python-Fundamentals
- https://github.com/dlab-berkeley/Python-Data-Wrangling/
- https://github.com/dlab-berkeley/Python-Web-APIs
- https://github.com/cs124/pa2-naive-bayes/blob/main/pa2.ipynb
- https://github.com/cs124/pa2-naive-bayes/blob/main/numpy_tutorial.ipynb
- https://web.stanford.edu/class/cs124/lec/Lab1_UnixText_2025_upload.pdf
- https://github.com/cs124/labs/blob/main/Lab3_InformationRetrieval.md 
- https://github.com/dlab-berkeley/Python-Intermediate-Legacy
- https://github.com/dlab-berkeley/Python-Data-Visualization
