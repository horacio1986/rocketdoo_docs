# Get Started

Before we launch our environment, we'll review the tools you need to get started without worry.

## Tools Needed

1. Operating System: 
    - Linux, recommended distributions “Ubuntu” or “Debian”.
    - Windows 10/11 (more on how to use Rocketdoo with Windows later).
2. Terminal CLI
3. Python installed (you can use Python virtual environments to work more securely). 
4. Install or have GIT installed in the terminal.
5. An account in GITHUB
6. Generate an SSH key on your machine and then configure it in your GITHUB account.
7. Install Docker and Docker Compose
8. GITMAN (it is installed by default in the container).
9. Install Visual Studio Code
10. Necessary extensions of Visual Studio Code:
    - Dev Container
    - Docker

These extensions are the basic and fundamental ones, but later we will detail some more that will be very useful.

## Remarks

Although this list of necessary tools may be a bit scary for a developer with little experience or knowledge, don't panic!,
because our automated environment “Rocketdoo” will manage everything for you and
in an effective and efficient way; without the need for you to learn how to use each and every one of these tools.

You only need to know how to handle the basics and fundamentals of a developer, tools such as, Git,
GitHub and Visual Studio Code.

Although it would clearly be a plus if you can understand and manage for example Docker. However, it is not
necessary at all, and you will see it more clearly when we start the step by step.


## Why use Docker? 

Docker is a worldwide tool for every software development company that understands the seriousness of working in a contained and prepared
with the maximum conditions necessary for our development to be 100% functional.
As it is well known, working in Docker provides us with the reliability of knowing that our developments will run properly in any
environment and browser that we use and that the client uses.
With this we avoid the famous phrase:

> “On my machine if it works”.

Besides saving us these user/developer issues, with Docker we will use the official Odoo images provided by Odoo.
Official images that provide us with all the basic requirements for Odoo to run correctly.

On the other hand, working with Docker provides us with an ephemeral development environment; a quality that is unique to Docker and Docker
Compose make it easy to develop and throw away when no longer needed.

Among other things, we will be able to raise our environment with a simple command, pause or
when we have finished or put on hold the continuity of our development, avoiding to occupy our PC's resources.

To then return to the same state in which we had left our development.

Don't you think this is great?

Finally, we will mention that Docker Compose will create a web container where Odoo will run and a database container,
where Postgresql will run. This allows us to have both Odoo and Postgresql isolated;
allowing us to pause, restart, or stop each service separately if necessary.

### Guide to install Docker and Docker Compose

[Official Docker Guide](https://docs.docker.com/engine/install/ubuntu/)

## What is GITMAN and why use it?

Gitman is a tool that allows us to manage in a yamel type “yml” file 
all kinds of public repositories that may be necessary to address our developments. 
With this tool we will be able to have all the repositories or packages from third party repositories
ready to install in our instance without the need of having to download each and every one of them by hand,
and then move or copy them to our working directory.

You “developer” will be able to have all the necessary repos at your disposal just by copying and pasting the links of each repo or third party 
links of each repo or repository package, too, without the need to move around in the different Odoo versions of each repository,
since Rocketdoo will dynamically ask you which version you want to work with in each of these repositories.

For those who work with Odoo SH, or who have knowledge of submodules, Gitman offers the same experience.


It is important to emphasize that you do not need to install GITMAN on your PC, as this tool will
will be installed by default in your development container once the Rocketdoo launcher is started.

As a bonus, in addition to installing gitman by default and cloning all the necessary third-party repositories
ready to be installed, Rocketdoo also scans each repository for “requirements.txt” files and installs them,
avoiding the waste of time and
of time and having to install each and every one of them by hand. We know from our own experience that 
more than once we have seen frustrated the creation of a database in Odoo because it indicates us an error or lack of library.

Rocketdoo comes to facilitate this task too!!!

Gitman is undoubtedly an essential and necessary tool to work quickly and comfortably, especially because in many cases,
for example the localizations of some countries are not contemplated or complete in the Odoo core,
so it is necessary to count on third party developments that come to cover these necessary functionalities. 

A clear example of this is the complete Odoo Accounting
which is not included in the Community Edition and many of us use the “Odoo Mates” repository.

If you want to know more about GITMAN features, we invite you to read its documentation.

[Official Gitman Guide](https://gitman.readthedocs.io/en/latest/)

## Linux or Windows ?

As we commented at the beginning of this documentation, this environment is designed and recommended to be used on a Linux operating system.
and this is not a whim, but it has to do with a reality, and is that Linux by default
reality, and that is that Linux by default consumes much less resources of your PC, and it is also a system where
for example Docker works perfectly and this does not happen with Windows.

But anyway, we are not going to leave aside the most popular operating system in history.
Yes! we have also thought about Windows, or not really! well, the point is that you can develop with **Rocketdoo**
by installing WSL2 on your Windows system. 

We will see this in the next section.
