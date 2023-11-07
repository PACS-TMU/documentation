# Data Science Documentation - Getting Started
<sup style="display: inline-block;">🕗 10-minute read.</sup> <br/>
<sup style="display: inline-block;">**Note:** This document is meant for internal PACS use only.</sup>

This documentation is going to cover all the necessary installations to start using Data Science in PACS.

## Section 1: Installing Python 3
1. Check if you already have python:
   <br />
   <details>
	<summary>For Windows</summary>

 	<br />

   	Open Command Prompt
   
 	<br />
 
    </details>
    <details>
	<summary>For MacOS</summary>

 	<br />

   	Open Terminal
   
 	<br />
 
    </details>
2. Check your Python version:
   <br />
   <details>
	<summary>For Windows</summary>

 	<br />

   	>In your command prompt, type:
   
 	<br />
  
	```
	python --version
	```
 
    </details>
    <details>
	<summary>For MacOS</summary>

 	<br />

   	>In your terminal, type:
   
 	<br />
  
	```
	python3 --version
	```
 
     </details>

3. Check the output:
    - If the output says `Python 3.XX.X`, python is already installed. You can proceed to [Section 2](#section-2-installing-pycharm-or-other-ide).
    - If the output says `Python 2.XX.X` or `python is not recognized` (or a message along those lines), python is not installed. Proceed to the windows installation below.

4. Installing Python 3:
    - For Windows,
        - Follow the link to the <a href="https://www.python.org/downloads/windows/" target="_blank">official python Windows releases</a>
    - For MacOS,
        - Follow the link to the <a href="https://www.python.org/downloads/macos/" target="_blank">official python MacOS releases</a>
    - Select the latest Stable Release
    - For Windows,
        - Scroll to the bottom and select `Windows installer (32-bit)` or `Windows installer (64-bit)`, depending on your Windows system (64-bit is usually more common)
    - For MacOS,
    	- Scroll to the bottom and select `macOS 64-bit universal2 installer`
    - After the installer download is complete, open it and go through the installation steps
    - If asked to add Python to PATH, select that option.

## Section 2: Installing PyCharm (or other IDE) 
Some common IDEs used for Python projects are:
- <a href="https://www.jetbrains.com/help/pycharm/installation-guide.html" target="_blank">PyCharm (recommended)</a>
- <a href="https://code.visualstudio.com/download" target="_blank">Visual Studio Code (VSCode)</a>
- <a href="https://docs.spyder-ide.org/3/installation.html" target="_blank">Spyder</a>
- and many more...

For Data Science purposes, we will mainly be using Jupyter Notebook. However, we strongly recommend PyCharm as your day-to-day IDE for Python projects and scripts. Follow the links above to install the IDE of your choice.

## Section 3: Installing `NumPy` and `pandas` - pip
`NumPy` and `pandas` are the main Python libraries used for numerical analysis and data science. They increase the efficiency of the Python code we run, all while providing built-in functions that make analysis and data processing a lot easier. `pip` is a package installer that comes with Python, and we use it to download these libraries. If Python is installed correctly, pip can be used.
<details>
    <summary>For Windows</summary>

- Open Command Prompt

- To install NumPy:

```
pip install numpy
```
or
```
python -m pip install numpy
```

- To install pandas:
```
pip install pandas
```
or
```
python -m pip install pandas
```
    
</details>

<details>
    <summary>For MacOS</summary>

- Open Terminal

- To install NumPy:

```
pip3 install numpy
```

- To install pandas:
```
pip3 install pandas
```

</details>


## Section 4: Installing and Running Jupyter Notebook
Jupyter Notebook is going to be the main interface we use for Data Science at PACS. We use it because it allows us to insert markdown cells and code cells separately. Markdown cells are usually utilized to draw conclusions and analyze the code blocks we run, while the constant feedback for each code cell helps us keep track.
<details>
    <summary>For Windows</summary>

- Open Command Prompt

- To install Jupyter Notebook:

```
pip install jupyter notebook
```
or
```
python -m pip jupyter notebook
```
    
</details>

<details>
    <summary>For MacOS</summary>

- Open Terminal

- To install NumPy:

```
pip3 install jupyter notebook
```

</details>

#### To run Jupyter Notebook
- Create a new folder where you want to create your notebook for data processing
- Open your terminal/command prompt for that directory
- Run
```
jupyter notebook
```
- A new tab will open in your default browser. In that tab, create a new notebook
- When the notebook starts, you're good to go! You can start using Jupyer Notebook to process data.

<sup style="display: inline-block;">**Note:** Moving forward, basic knowledge of python is required (conditionals, logic operators, loops, etc.).</sup>
