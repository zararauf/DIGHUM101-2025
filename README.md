# DIGHUM101-2025

Welcome to Python Programming for Digital Humanities, UC Berkeley Summer 2025, taught by Merve Tekgürler.

## Software Installations and Set Up

*Please have this complete before first day*

In this class, we will learn to use the programming language Python. Just as you use a text editor like Microsoft Word for writing, you'll need a code editor to write and manage your code. In our case, we’ll be using Visual Studio Code (VS Code), a user-friendly and free editor designed for programming.
To install and manage additional tools or libraries (also called packages) that extend Python’s functionality, we will use a package manager—specifically, Conda. Conda allows us to install, update, and organize the various packages we’ll need throughout the course.
Finally, we will be using GitHub, a platform for sharing and collaborating on code. GitHub allows you to store your code in the cloud, track changes over time, and work with others on shared projects, similar to Google Docs.

Please follow the steps below to install the required software:

- [ ] Python
- If you are using a MacBook, you should already have Python installed on your computer.
- If you are using Windows, please follow the instructions here to install [Python](https://realpython.com/installing-python/)
- Make sure that you are running Python 3.12
- [ ] GitHub
- Use your student email address to create a [GitHub account](https://github.com/)
- Follow the instructions on [this page](https://docs.github.com/en/education/about-github-education/github-education-for-students/apply-to-github-education-as-a-student) to apply for a GitHub Pro account, which is free for students
- [ ] Virtual Studio Code
- Download [VS Code](https://code.visualstudio.com/)
- Sign in VS Code with your GitHub account
- [ ] Miniconda
- Download [Miniconda Installer](https://www.anaconda.com/download/) You have to scroll all the way down to the Miniconda installer
- Make sure to choose the correct Miniconda for your computer (Windows vs Mac) and your chip architecture (Mac Intel or Mac Apple).
Refer to [getting started](https://www.anaconda.com/docs/getting-started/miniconda/main) and [installation](https://www.anaconda.com/docs/getting-started/miniconda/install) guides for questions

## Conda Environment

*We will run this together in class*

A Conda environment is like a workspace or container on your computer that keeps all the packages you need for a project in one place.

When you're working on a coding project, you will need specific tools, called packages. Each package serves a different function. For example, numpy is for doing advanced math, pandas are for handling data and tables, matplotlib is for making graphs, and nltk is for analyzing language. These tools need to work with a specific version of Python and may even have different versions depending on the project. If you install everything globally (for your entire computer), things can break—especially when different projects need different versions of the same tool. Think of environments as toolboxes, that you set up with select tools for each project.

A conda environment keeps your project’s tools and settings separate from everything else on your computer. It helps avoid version conflicts and makes it easy to share your setup with others, using an environment.yml file.

We will create a conda environment for this class and call it **dighum101**. You will install this enviroment once, using the steps below and activate it every time we are coding in this class.

Follow these steps to set up your Python environment for this course.

### 1. Copy the repository

Clone or download this repository to your computer. Make sure to place it in a folder **whose location you will not change** later on.

### 2. Create the Conda environment

Open a terminal in Visual Studio Code, navigate to the folder where the `environment.yml` file is located, and run:

`conda env create -f environment.yml`

### 3. Activate the Conda environment

`conda activate dighum101`

### 4. Make the environment available as a Jupyter kernel

`python -m ipykernel install --user --name dighum101`

### 5. Deactivate the environment when you're done

`conda deactivate`