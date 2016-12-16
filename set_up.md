## PSTAT 193

### Setting up your machine

To teach the basics of R programming this quarter, we will use Jupyter Notebooks (also known as iPython Notebooks). Programming notebooks are a very common tool in data science and analytics, as it allows the creator to intertwine their code with explanations written in markdown. This design allows us, the instructors, to better explain code segments and syntax, making the lectures are easier to follow. We will also use RStudio at the end of the quarter when we get into using ggplot2.

It may look like a lot to install, but you probably have a lot of this downloaded already if you are a student in PSTAT or have taken one of the club tutorials before.

### Steps

- Download and install R
	- [Click here](https://cran.cnr.berkeley.edu)
	- Click the link for your operating system
		- For OSX and Windows, choose the first option on the following page
		- For Linux, select your flavor on the following page and follow the subsequent instructions
- Download and install RStudio
	- [Click here](https://www.rstudio.com/products/rstudio/download/)
	- Select your operating system under "Installers for Supported Platforms"
	- Open the downloaded file and follow the installer's instructions
- Download and install Jupyter
	- Jupyter runs on Python, so you must have Python installed on your machine
		- Preferabally version 3.3 or greater; 2.7 also works.
	- [Click here](https://www.continuum.io/downloads) to download Anaconda
		- Scroll down, then select your operating system in one of the 3 tabs
- Test R and RStudio
	- Open RStudio and try entering the following commands:
		- install.packages("ggplot2")
		- library(ggplot2)
	- Any warning messages can be ignored, read and troubleshoot any errors.
	- If R and RStudio are functioning properly **and** you are connected to the internet you have now installed ggplot2 and can proceed.
- Download and install the R kernel for Jupyter
	- In RStudio, enter the following commands...
		- install.packages(c('repr', 'IRdisplay', 'crayon', 'pbdZMQ', 'devtools'))
		- devtools::install_github('IRkernel/IRkernel')
		- IRkernel::installspec()
	- If you encounter any issues, the full instructions are [here](https://irkernel.github.io/installation/)
- Test the R Kernel on Jupyter
	- Go into your command prompt/terminal and enter the command "jupyter notebook". This should open your internet browser.
	- On the right side, click the "new" button.
		- In the dropdown menu, you should see "R" listed
		- Click "R" and try some commands in the notebook
	- If R is not listed in the dropdown, start a new Python notebook
		- In the new notebook, click "kernel" in the navigation bar
		- In the dropdown, click "change kernel" R should be listed there
		- Click "R" and try some commands in the notebook

### Trouble-Shooting:
If you get stuck on a step, troubleshoot your error simply by Googling your error. For example...
	- If RStudio is not recognizing your R installation on OSX, you would search "RStudio can't find R OSX".
	- Or if Jupyter is not opening in your browser on your Windows machine... "jupyter notebook not opening in chrome windows".

You can also post your question on the PSTAT 199 Piazza page. Another student might have encountered the same error and found a solution. For Jason or Aaron to respond, you **must** include in your post...
	- Any error messages
	- Your operating system
	- Something you already tried to solve the problem

