# Exam Template Using R Markdown

This repo contains a customizable R Markdown template.

# Downloading the Repo

## Method 1: Using R

Install and load the `usethis` package and download with `use_github`:

`install.packages("usethis")`
`library("usethis")`
`usethis::use_github("hubchev/temp_exam", destdir = "path/to/destination")`

Replace "path/to/destination" with the desired location on your system where you want to download the repo.

## Method 2: Using the Terminal

If you have Git installed on your system, you can download this repository using the command line:

- Open the Terminal or Command Prompt.
- Navigate to the directory where you want to download the repo using the cd command (e.g., cd ~/Documents).
- Run the following command to clone the repo: 

`git clone https://github.com/hubchev/temp_exam.git`

## Method 3: Using the mouse

In GitHub click the green `<> Code v` button that you find at this repo. In the context menu that opens, you find a button named `Download ZIP`. Click that and you have the a zipped copy of the repo which you can unzip and use.

# How to Use the Template

Once you've downloaded the repo, navigate to the directory where you downloaded it and open the `exam_template.Rmd` file in RStudio or your preferred R Markdown editor. Customize the template to create your own exam!

To convert the R Markdown file into a formatted document (such as a PDF or HTML), knit the exam_template.Rmd file. You can do this in RStudio by opening the file and clicking the "Knit" button, or by running the following command in the R console:

rmarkdown::render("path/to/temp_exam.Rmd")

Replace "path/to/exam_template.Rmd" with the actual path to the file.
Contribute

If you have any questions or need help with the template, feel free to open an issue or contact me. Happy exam-writing!
