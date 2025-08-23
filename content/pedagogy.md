---
title: "Pedagogy"
hide_title: true
---

# Teaching Assistant at Penn
[**STAT 432** - *Fall 2023* - University of Pennsylvania](https://apps.wharton.upenn.edu/syllabi/2022A/STAT432001/)
<br>
[**STAT 961** - *Fall 2022* - University of Pennsylvania](https://katsevich-teaching.github.io/stat-9610-fall-2022/)
<br>
[**STAT 432** - *Spring 2022* - University of Pennsylvania](https://apps.wharton.upenn.edu/syllabi/2022A/STAT432001/)

---
title: "Academic Experience"
output: html_document
---

```{r setup, include=FALSE}
# This chunk sets a global option to prevent code from being displayed in the output.
knitr::opts_chunk$set(echo = FALSE)
```

<!-- Add custom CSS to style the table and define the color variable -->
<style>
  :root {
    --olive-color: #556B2F; /* Define a CSS variable for the olive color */
  }
  
  /* Style the main title */
  h2 {
    color: var(--olive-color);
  }
  
  /* Style the table to remove borders and padding */
  .ta-table td {
    border: none;
    padding: 10px 0; /* Adjust padding to control spacing between rows */
  }
  
  .ta-table {
    border-collapse: collapse; /* Prevents gaps between cells */
    width: 100%;
  }

  /* Style the first column specifically for the year and semester text */
  .ta-table td:first-child {
    font-weight: bold;
    color: var(--olive-color);
    padding-right: 20px; /* Add some space between the columns */
  }
  
  /* Add a border to the bottom of each row for separation */
  .ta-table tr:not(:last-child) {
    border-bottom: 1px solid #ddd;
  }
</style>

## Teaching Assistantships at Penn

```{r data-frame-preview}
# Load the knitr package for the kable() function
library(knitr)

# Create a data frame from your LaTeX content
# We'll use a specific pattern for the syllabi links
base_url <- "[https://github.com/Abhinandan-Dalal/website/blob/main/docs/course_syllabi/](https://github.com/Abhinandan-Dalal/website/blob/main/docs/course_syllabi/)"

ta_data <- data.frame(
  period = c(
    "Fall 2025", "Spring 2025", "Spring 2025",
    "Fall 2024", "Fall 2023", "Spring 2023",
    "Spring 2022"
  ),
  course = c(
    "STAT 9210: Observational Studies (for Graduate Students)",
    "STAT 5330: Stochastic processes (for Undergraduate Students)",
    "STAT 1110: Introductory Statistics (for Undergraduate Students)",
    "STAT 4320: Mathematical Statistics (for Undergraduate Students)",
    "STAT 4300 & STAT 5100: Probability (for Undergraduate/Graduate Students)",
    "STAT 9700: Mathematical Statistics (for Graduate Students)",
    "STAT 521: Applied Econometrics II (for Graduate Students)"
  )
)

# Function to create a hyperlink for a course
# This is a bit manual, but ensures correct links based on the text
create_link <- function(course_string) {
  # Extract the course number(s) from the string
  # This pattern matches any STAT followed by numbers and an optional '&'
  course_match <- regmatches(course_string, regexpr("STAT\\s+[0-9&\\s]+", course_string))
  
  # Remove extra spaces and split multiple course numbers if present
  course_number <- gsub(" ", "", course_match)
  course_numbers <- unlist(strsplit(course_number, "&"))
  
  # Create a link for each course number and join them with a separator
  links <- sapply(course_numbers, function(num) {
    syllabus_url <- paste0(base_url, num, ".pdf")
    sprintf('<a href="%s" target="_blank">%s</a>', syllabus_url, num)
  })
  
  # Replace the original course number string with the formatted links
  for (i in seq_along(course_numbers)) {
    course_string <- sub(course_numbers[i], links[i], course_string, fixed = TRUE)
  }
  
  # Use bold for the course name as requested
  course_name <- regmatches(course_string, regexpr(": .*", course_string))
  course_string <- sub(course_name, paste0(":**", course_name, "**"), course_string, fixed = TRUE)
  
  return(course_string)
}

# Apply the function to each row
ta_data$course <- sapply(ta_data$course, create_link)

# Display the data frame in the R console output for review.
# The table will be visible in the knitted HTML file's output.
ta_data
```{r table-generation, results='asis'}
# Use knitr::kable() to format the table.
# 'escape = FALSE' is crucial to render the HTML tags in our data frame.
# 'col.names = NULL' removes the column headers.
# 'table.attr' adds a CSS class for styling.
knitr::kable(
  ta_data, 
  format = "html", 
  col.names = NULL, 
  escape = FALSE,
  table.attr = "class='ta-table'"
)
```





<!-- Add a style tag with CSS to control the layout -->
<style>
  .content-container {
    display: flex;
    align-items: flex-start;
  }
  .text-container {
    flex-grow: 1;
  }

  .side-image {
    margin-top: 5px;
    margin-left: 30px; /* Adjust the space between the image and the text */
    max-width: 40%; /* Adjust the width of the image */
    border-radius: 2%; /* Make the image circular */
    overflow: hidden; /* Hide anything outside of the circle */
  }

  /* Responsive design for smaller screens */
  @media (max-width: 768px) {
    .side-image {
      max-width: 100%;
      margin-left: 0;
      margin-bottom: 20px;
    }

    .content-container {
      flex-direction: column;
    }
  }
</style>
