# Machine Learning for OpenCV

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/PacktPublishing/Machine-Learning-for-OpenCV-Second-Edition/master)

The content is available on [GitHub](https://github.com/PacktPublishing/Machine-Learning-for-OpenCV-Second-Edition).
The code is released under the [MIT license](https://opensource.org/licenses/MIT).

## Running the Code

There are at least two ways you can run the code:
- Using [Binder](https://mybinder.org/v2/gh/PacktPublishing/Machine-Learning-for-OpenCV-Second-Edition/master) (no installation required).
- Using Jupyter Notebook on your local machine.

The code in this book was tested with Python 3.6.


### Using Binder

[Binder](http://www.mybinder.org) allows you to run Jupyter notebooks in an interactive Docker container.
No installation required!

Launch the project: [PacktPublishing/Machine-Learning-for-OpenCV-Second-Edition](https://mybinder.org/v2/gh/PacktPublishing/Machine-Learning-for-OpenCV-Second-Edition/master)



### Using Jupyter Notebook

You basically want to follow the installation instructions in Chapter 1 of the book.

In short:

1. Download and install [Python Anaconda](https://anaconda.com/download/).
   On Unix, when asked if the Anaconda path should be added to your `PATH` variable, choose yes. Then either open a new terminal or run `$ source ~/.bashrc`.

2. Fork and clone the GitHub repo:
   - Click the
     [`Fork`](https://github.com/PacktPublishing/Machine-Learning-for-OpenCV-Second-Edition#fork-destination-box)
     button in the top-right corner of this page.
   - Clone the repo, where `YourUsername` is your actual GitHub user name:

   ```
   $ git clone https://github.com/YourUsername/Machine-Learning-for-OpenCV-Second-Edition
   $ cd Machine-Learning-for-OpenCV-Second-Edition
   ```
   
   - Add the following to your remotes:
   ```
   $ git remote add upstream https://github.com/PacktPublishing/Machine-Learning-for-OpenCV-Second-Edition
   ```
   
4. Create a conda environment for OpenCV-ML with all required packages:

   ```
   $ conda env create -f environment.yml
   ```

5. Activate the conda environment.
   On Linux / Mac OS X:

   ```
   $ source activate OpenCV-ML
   ```

   On Windows:

   ```
   $ activate OpenCV-ML
   ```

   You can learn more about conda environments in the
   [Managing Environments](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html)
   section of the conda documentation.

6. Launch Jupyter notebook:

   ```
   $ jupyter notebook
   ```

   This will open up a browser window in your current directory.
   Navigate to the folder `Machine-Learning-for-OpenCV-Second-Edition`.
   The README file has a table of contents.
   Else navigate to the `notebooks` folder, click on the notebook of your choice,
   and select `Kernel > Restart & Run All` from the top menu.
   
   
## Getting the latest code

If you followed the instructions above and:
- forked the repo,
- cloned the repo,
- added the `upstream` remote repository,

then you can always grab the latest changes by running a git pull:

```
$ cd Machine-Learning-for-OpenCV-Second-Edition
$ git pull upstream master
```

## Acknowledgment

This book was inspired in many ways by the following authors and their corresponding publications:
- Jake VanderPlas, Python Data Science Handbook: Essential Tools for Working with Data. O'Reilly, ISBN 978-149191205-8, 2016, https://github.com/jakevdp/PythonDataScienceHandbook
- Andreas Muller and Sarah Guido, Introduction to Machine Learning with Python: A Guide for Data Scientists. O'Reilly, ISBN
978-144936941-5, 2016, https://github.com/amueller/introduction_to_ml_with_python
- Sebastian Raschka, Python Machine Learning. Packt, ISBN 978-178355513-0, 2015, https://github.com/rasbt/python-machine-learning-book

These books all come with their own open-source code - check them out when you get a chance!
