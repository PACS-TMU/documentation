# Jupyter Notebook Docs - Getting Started
<sup style="display: inline-block;">**Note:** This document is meant for internal PACS use only.</sup>

This documentation covers how to start Jupyter Notebook and a few basic commands to get you started with the interface.

## Quick Links
#### [Creating and Running a Notebook](#creating-and-running-a-notebook)
#### [Common Keyboard Shortcuts](#common-keyboard-shortcuts)

## Creating and Running a Notebook
- Navigate to the folder/directory you want to create your Jupyter Notebook in
- Open that folder/directory in your terminal/powershell/command prompt
- Run the command
  ```
  jupyter notebook
  ```
- Jupyter will open in a new tab in your default browser
- In the top right corner of the interface, click on a collapsible button labelled `New`

  >Note: for the upcoming steps, if prompted at any point to select the kernel for the notebook, select `Python 3`
- Select `Notebook` from the drop-down menu
- This should open a new tab with your notebook

## Common Keyboard Shortcuts
We use Jupyter Notebook because it allows us to use markdown cells for describing and analyzing our findings, as well as code cells to run our Python code. Jupyter runs each cell separately usually, unless it is clearly instructed to *Restart the kernel and run all cells* (the button that looks like `▶︎▶︎`).

>Sometimes, running code cells multiple times might impact the data you're processing in your notebook. To avoide such a problem, when editing code blocks that have been previously executed (especially when other blocks have been executed since), it is recommended to restart the kernet and run all cells (i.e., press the `▶︎▶︎` button).

Since we run cell-by-cell in Jupyter, it is much more convenient to utilize keyboard shortcuts that press the `▶︎` button for every cell. Given that, here are the most common keyboard shortcuts that we will be using:

>Note: For Mac users, `ctrl` below stands for the command key `⌘`

| Keyboard Shortcut | Utilization | Notes |
| :-: | :-: | :-: |
| `M` | Converts cell to markdown cell | The cell (not text-editing space) must be selected, i.e., you must press outside the text box |
| `Y` | Converts cell to code cell | The cell (not text-editing space) must be selected, i.e., you must press outside the text box |
| `A` | Insert cell above current cell and select it | The cell (not text-editing space) must be selected, i.e., you must press outside the text box |
| `B` | Insert cell below current cell and select it | The cell (not text-editing space) must be selected, i.e., you must press outside the text box |
| `Shift + Enter` | Run current cell and move to next cell | If there is no cell below, one is created, otherwise, next cell is selected |
| `Ctrl + Enter` | Run current cell without moving the cursor | - |
| `Ctrl + S` | Save and create a checkpoint | Jupyter Notebook has autosave by default, but we can save at any time using this |

There are many more shortcuts that Jupyter Notebook has, those can be found by selecting the `Help` menu followed `Show Keyboard Shortcuts`, or by pressing `Ctrl + Shift + H`.

You are ready to use Jupyter Notebook for data science now!
