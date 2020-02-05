# Useful-Tips
A repository for sharing useful tricks and tools

My suggestion is that we use this as a place to share any useful tricks we learn about duering the semester. Just add them to this README.md file and then send me a "pull request", to ask that your changes are included in this Master version.


# Knitting to HTML file on Github
Problem: Can't find a way to make html markdown outputs look nice on github for a human to read

Solutions:
Change output in the beginning of your rmarkdown file to either
1. output: rmarkdown::github_document
2. output: 
  html_document:
    keep_md: true
    
Choose whichever you like. These will knit a file that ends with ".md" which should be uploaded

# Uploading figure files
problem: Figures do not show on GitHub.

Solutions: Go to the folder containing the .md file and find another folder, created at the same time, called something like “figure-gfm”. Upload or commit the folder along with the .md file. 
