<!--
Comment space
-->

![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)

# AirBnB Project
### Washington, D.C. and Amsterdam Market Analysis

> This project seeks to introduce you to analysis in excel by processing listings from the AirBnB website.

## Overview
In this project, an investor is seeking to invest in a short-term rental property (AirBnB listing) and wants to make a data-driven decision. You are tasked with answering some of their questions about regional AirBnB market trends. There are two possible routes of study - the Washington, D.C. market, and the Amsterdam market. You will be selecting _one_ of these markets and proposing a strategy and case for or against investment in property there.


## Quick Links
- [Getting Started](#getting-started)
- [Project Repo Structure](#project-repo-structure)
- [Tableau](#tableau)

## Getting Started

- There are two possible paths for completing this project (Washington, D.C. and Amsterdam). Follow the directions of your instructor to decide which to pursue. 
- After selecting a path, open the `dc_data.csv` or `ams_data.csv` file corresponding to the Washington or Amsterdam projects, respectively. This `csv` file will be the raw data you will process during your analysis.
- Open the `dc_instructions.docx` or `ams_instructions.docx` files for a list of prompts (questions) you will answer in your analysis. Also included in this instructions document are guidelines on how to proceed, and an outline of deliverables to submit when completed.
- If you get stuck, don't worry. There are solutions included in the `/solution` folder of each respective project path. In here are suggested solutions to the projects which may help you overcome obstacles or clarify objectives.
  - Note that in these solution folders are also tableau files. These are included _for reference only_, should you decide to pursue the project further in tableau or a similar application. These are included to illustrate some of the more advanced functionality available in other applications.
  - See [project repo structure](#project-repo-structure) for more details on file descriptions.
- When your project is completed, you will be presenting your findings to your classmates in the form of a powerpoint presentation. You will also submit an excel workbook with your analysis and formulas organized for review.
- Grading of your presentation, and analysis, will be done in accordance with the rubric in the `/assets` folder of this repo.

## Project Repo Structure

- In this repo, you will find the following folder hierarchy:
| Folder | Description |
| -------- | ------------------ |
| `/uk`    | The root of the Amsterdam market study |
| `/us` | The root of the Washington, D.C. market study |
| `/assets` | Shared assets between the two markets |
- Both projects (`/us` and `/uk` folders) include the following, where 'mkt' (market) is either 'dc' for Washington, D.C., or 'ams' for Amsterdam:
| Filename | Description |
| -------- | ------------------ |
|`mkt_data.csv` | This is the raw data from which you will start your study |
| `mkt_instructions.docx` | This is a list of prompts you will answer |
| `solutions/mkt_solution.xlsx` | This is an excel workbook containing the result of your analysis on the .csv file |
| `solutions/mkt_solution.pptx` | This is a powerpoint presentation containing the answers to the prompts in mkt_instructions.docx |
| `solutions/mkt_solution.twb` | This is a tableau file which references `mkt_solution.xlsx` and presents an alternative method of analysis to `mkt_solution.pptx`. This is for your reference only and is not a requirement of the exercise |
| `solutions/mkt_solution.pdf` | This is a `.pdf` file of the 'tableau story' contained in `mkt_solution.twb`. This is for your reference only and is not a requirement of the exercise |
- The `/assets` folder contains the following:
| Filename | Description |
| -------- | ------------------ |
| `rubric.xlsx` | This is the grading rubric to be used to assess your deliverable presentation and analysis |

## Tableau

As discussed in the project structure section, this repo contains a sample tableau solution of the exercise. Tableau is free to download and use for a 14-day trial period. Here are some things to note:

- Installing [from the website](https://www.tableau.com/products/desktop/download) normally requires some type of sales lead capture form, asking for your organization name, position, email, etc. You can bypass all that noise by getting the executable installer [here](https://www.tableau.com/support/releases). 
  - Choose the highest number version number from the list. At the time of writing, the list was sorted descending chronologically (newest at top)
  - Use a year number (i.e. '2018.x.x') release instead of a 10-number (i.e. '10.x.x') release. This is confusing because [tableau said they were deprecating the 10.x.x nomenclature](https://www.tableau.com/about/blog/2018/1/changing-our-version-numbering-new-software-releases-80853) in Jan 2018 but as of Dec 2018 they're still releasing it.
- After the installer is complete and the application is started locally, the application will once again ask you for an email address prior to starting your 14-day trial. This email address, at the time of writing, did not need to be verified to proceed with the trial. In other words, you could technically enter an email you couldn't validate, like support@tableau.com.
- At the time of writing, the tableau application can be run within a virtualized windows environment (tested with Windows 10 on Virtualbox 5.2.18)

---

*Copyright 2019, General Assembly Space. Licensed under [CC-BY-NC-SA, 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)*
