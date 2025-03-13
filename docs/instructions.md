# Instructions for Use

In this section of the documentation we will prepare our PC to start developing in Odoo using
ROCKETDOO.

***For developers who prefer to work with Windows and WSL2, as we saw in the previous page, you should already have your PC ready with all the initial tools installed.
You should already have your PC ready with all the initial tools installed.

For those who work on Linux operating systems, we will detail the necessary tools that you should have installed to get started.
For those of you working on Linux operating systems, we will detail the necessary tools you must have installed in order to get started.

## Tools prior to Rocketdoo:

1. Keep Linux packages updated.
2. Install or verify that you have GIT installed.

~~~
git --version
~~~

or install:

~~~
sudo apt install git -y
~~~

3. Have Visual Studio Code installed
4. Have installed the Python package manager “pip”.
5. Install Docker and Docker Compose using the official guide shared on the “Get Started” page.
6. Install in VSCode the basic extensions 
    - Docker 
    - Dev Container

And the most important thing is to install the ROCKETDOO library:

~~~
sudo pip install rocketdoo
~~~
[Official Rocketdoo](https://pypi.org/project/rocketdoo/)