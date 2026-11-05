**NOVEMBER 4, 2026**<br>
**MPAD 2003A & Data Storytelling**<br>
**Muhannad Mahdi**<br>
**Presented to Jean-Sébastien Marier**<br>

# Deliverable 2: Exploratory Data Analysis (EDA)

Use one hashtag symbol (`#`) to create a level 1 heading like this one.

## Foreword

For this assignment, you must clean and analyze the dataset from Deliverable 1, create exploratory charts/visualizations, and identify a potential story. Your assignment must clearly detail your process. You are expected to write about 1,000-1,200 words, and to include several screen captures showing the different steps you went through. Your assignment must be written with the Markdown format and submitted on GitHub.

I have been assigning different versions of this project to my digital journalism and data storytelling students for a few years now. Its structure was inspired by the main sections/chapters of [*The Data Journalism Handbook*](https://datajournalism.com/read/handbook/one/). This version was further inspired by the [Key Capabilities in Data Science](https://extendedlearning.ubc.ca/programs/key-capabilities-data-science) program offered by the University of British Columbia (UBC).

**Here are some useful resources for this assignment:**

* [GitHub's *Basic writing and formatting syntax* page](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
* [The template repository for this assignment in case you delete something by mistake](https://github.com/jsmarier/jou4100_jou4500_mpad2003_project2_template)

Did you notice how to create a hyperlink? In Markdown, we put the clickable text between square brackets and the actual URL between parentheses.

And to create an unordered list, we simply put a star (`*`) before each item.



## 1. Getting Data


1- for this data of financial security, I decided to do a quick analysis of the percentage of people who are living in Ottawa-Gatineau part and see the percentage of the people who responded in a (1) "very easy or easy" for the question, "In the past 12 months- how difficult or easy was it for your household to meet its financial needs in terms of transportation- housing- food- clothing and other necessary expenditures?" 

2- Data Link: https://open.ottawa.ca/datasets/7dc44d40bbaa4a85a6123a9c825b0994_0/explore

3- Importing data from Google sheets:
to import data into Google sheets. I firstly clicked on files in the menu bar then import. It will pop up an import file window I clicked upload and then browse my data file from my desktop.

4- screen capture:


5- Public Link to my Google sheet:
https://docs.google.com/spreadsheets/d/1UtVkUDePxuuj5qoNmi4nnKvAze5fXYie_CfPQqkrhag/edit?usp=sharing

6- General Observation:
there are 18 columns and 385 rows in the data set.
The data look almost clean and cohesive, although it needs albeit cleaning to make it simpler and cleaner and accurate.

7- Specific Observations:
Column A shows the date the data was collected and it rages between 2020 and 2024.
Column B shows the region and, apparently, it is all in one region’s Ottawa-Gatineau part.
Column C represents the question in both English and French 
Column D shows the answer response to the question and it varies between 1 - 3
1-  is very easy or easy 
2 -Neither difficult nor easy 
3- very difficult or difficult.  What surprised me when I looked into the data is column H and column I. I did not understand what it stands for, since the title for it is F95ucl, which does not make any sense to me!


8- Questions about the data:
does subgroup column F really matter for the dataset ?
Column M in the object I don't see any necessity to be in the data set, since it's counting the numbers of the column only without providing any clear information.  

Use two hashtag symbols (`##`) to create a level 2 heading like this one.

To include a screen capture, use the sample code below. Your images should be saved in the same folder as your `.md` file.

![](import-screen-capture.png)<br>
*Figure 1: The "Import file" prompt on Google Sheets.*

**Here are examples of functions and lines of code put in grey boxes:**

1. If you name a function, put it between "angled" quotation marks like this: `IMPORTHTML`.
1. If you want to include the entire line of code, do the same thing, albeit with your entire code: `=IMPORTHTML("https://en.wikipedia.org/wiki/China"; "table", 5)`.
1. Alternatively, you can put your code in an independent box using the template below:

``` r
=IMPORTHTML("https://en.wikipedia.org/wiki/China"; "table", 5)
```
This also shows how to create an ordered list. Simply put `1.` before each item.

## 2. Understanding Data

### 2.1. VIMO Analysis

Use three hashtag symbols (`###`) to create a level 3 heading like this one. Please follow this template when it comes to level 1 and level 2 headings. However, you can use level 3 headings as you see fit.

Insert text here.

Support your claims by citing relevant sources. Please follow [APA guidelines for in-text citations](https://apastyle.apa.org/style-grammar-guidelines/citations).

**For example:**

As seen in Bounegru & Gray (2011), a data visualization should be clear...

### 2.2. Cleaning Data

Insert text here.

### 2.3. Analyzing Data

Insert text here.

**This section should include a screen capture of your pivot table, like so:**

![](pivot-table-screen-capture.png)<br>
*Figure 2: This pivot table shows...*

**This section should also include a screen capture of your exploratory chart, like so:**

![](chart-screen-capture.png)<br>
*Figure 3: This exploratory chart shows...*

## 3. Delivering Data

Insert text here.

## 4. References

Include a list of your references here. Please follow [APA](https://apastyle.apa.org/style-grammar-guidelines/references) or [MLA](https://www.mla.org/MLA-Style) guidelines for references. Hanging paragraphs aren't required though.

**Here's an example:**

Bounegru, L., & Gray, J. (Eds.). (2021). *The Data Journalism Handbook 2: Towards A Critical Data Practice*. Amsterdam University Press. [https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153](https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153)
