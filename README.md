# Python Workshop 2023

## Description

Python is a programming language that has found widespread adoption in data science, 
machine learning, and web-development applications while valuing code-readability. This 
course provides a two-day introduction to core-features that Python offers to social 
scientists. The course will focus on the practical use of Python by teaching 
participants how to scrape websites, train machine-learning algorithms, and process text 
in an automated fashion. The course aims to provide hands-on examples that participants 
can then adapt to their own needs and research interests.


## Requirements and Grading

Participants will have to fulfill the following requirements:

- Basic programming experience, either in Python or in another programming language (R, 
Stata, or others).
- Participate on each day of the workshop.
- Bring a laptop, ideally with a Python runtime installed.
- Submit a final programming assignment. 

Participants can include the workshop in their grade transcript. Grades for the 
workshop will be based on the final programming assignment.


## Installation

### Set Up Anaconda

You will need a Python runtime environment to run Python code. You can either install it 
manually from the Python website or you can use a ready-made distribution of Python. In 
the following steps we will install Anaconda, a Python distribution. The advantage of 
this is that it is very simple to install and it comes with a very useful interface 
called Jupyter Lab.

1. Visit the website of [Anaconda](https://www.anaconda.com/download). Select your 
operating system, look for Anaconda in the Python 3.11 Version, download and install it.
2. After you have completed the installation, search in your Applications for `Anaconda 
Navigator` and start it. In the tab `Home`, look for `Jupyter Lab` and launch it. 
3. If everything worked out, you can now access your own Jupyter Lab via you web browser. 
By default, Anaconda will automatically open a tab with the corresponding page, 
otherwise it can be reached in most cases via this [link](http://localhost:8888).


### Set Up GitHub Desktop

In order to access the code for this workshop, we will be using the code hosting 
platform GitHub. Besides access to code, this platform has a wide range of features, 
including consistent version control and change tracking. There are several ways to 
access a GitHub repository. On the one hand, there is the command line where you use 
commands to perform the desired actions. On the other hand, there is GitHub Desktop 
which allows for most actions within a graphical user interface.  The latter is often a 
relief, especially for beginners. 

1. Visit the website of [GitHub Desktop](https://desktop.github.com/). Select your 
operating system, download and install it.
2. After you have completed the installation, search in your Applications for `GitHub 
Desktop` and start it. If you already have a GitHub account, you can sign in with it, but 
it is not necessary to sign in to follow the next steps. 
3. To access the code for this workshop, click on `Clone a Repository`, `URL`, enter as 
`Repository URL` `https://github.com/stefan-scholz/python-workshop-2023` and select as 
`Local Path` the folder where you want to save the materials on your local computer. If 
your clone worked out, you can now see the files in your local path. These files should 
be the same as the ones online when you open up the [website](https://github.com/stefan-scholz/python-workshop-2023) 
via your web browser.


## Course Schedule

### Thursday, November 2, 2023:

1. Python basics and programming fundamentals ([notebook](1_basics.ipynb))
2. Working with structured data ([notebook](2_structured_data.ipynb))
3. Using application programming interfaces ([notebook](3_news_api.ipynb))

### Friday, November 3, 2023:

4. Web scraping ([notebook](4_web_scraping.ipynb))
5. Text processing and machine learning ([notebook](5_nlp_ml.ipynb))


## Additional Information

To get a first experience on how to use Python, here are references to introductory 
Python courses and books.

- [Coursera/Google "Crash Course on Python"](https://www.coursera.org/learn/python-crash-course)
- [Coursera/IBM "Python for Data Science and AI"](https://www.coursera.org/learn/python-for-applied-data-science-ai)
- [Anand Chitipothu "Python Practice Book"](https://anandology.com/python-practice-book/index.html)
- ["The (Official) Python Tutorial"](https://docs.python.org/3/tutorial/index.html)
- [Kushal Das "Welcome to Python for you and me"](https://pymbook.readthedocs.io/en/latest/index.html)

To get a first experience on how to use Anaconda, Jupyter Lab and GitHub Desktop, we 
recommend you to take a look at the following resources.

- [Anaconda Installation Guide](https://docs.anaconda.com/free/anaconda/install/windows/)
- [Getting Started With Jupyter Lab](https://jupyterlab.readthedocs.io/en/stable/getting_started/overview.html)
- [Getting Started With GitHub Desktop](https://docs.github.com/en/desktop/overview/getting-started-with-github-desktop)


## Credits

- [Sebastian Nagel](https://github.com/sebastian-nagel) has already held this course in 
2021 and 2022. He has kindly given me permission to use his materials, to which I have 
added more.


## Licenses

- [Apache 2.0](./LICENSE) for the Python code and documentation
- [Listing of data sources and licenses](data/README.md) for data shared in this 
repository
