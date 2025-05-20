# AUTOMATED-REPORT-GENERATION

COMPANY : CODTECH IT SOLUTION

NAME : patel bhavy

INTERN ID : CT04DL1286

DOMAIN : PYTHON PROGRAMMING

DURATION : 4 WEEKS

MENTOR : NEELA SANTOSH

## Task Description – PDF Report Generation Using Python

In this task, the objective is to create a well-structured and presentable PDF report from a given dataset using Python. The report is designed to summarize student performance based on their scores. This task involves data reading, analysis, and the generation of a professional-looking PDF using the FPDF library. It demonstrates how Python can be effectively used for automating reporting tasks in real-world data-driven environments such as education, HR, and business intelligence.

# Objective
The goal of this task is to read student data from a CSV file, perform basic statistical analysis (like calculating the average, highest, and lowest scores), and then generate a PDF file that neatly displays the results. The report includes a title, table of student names and their scores, statistical summaries, and a custom footer. This kind of automation can be extremely useful for generating reports at scale without manual formatting or data entry.


# 1. Reading the Data

The first step involves importing the necessary libraries: pandas for data handling, fpdf for PDF generation, and datetime to include the current date in the footer of the report.

Using pandas, the script reads the student score data from a file named data.csv. The data is expected to contain at least two columns: "Name" and "Score". pandas.read_csv() is used here because it provides an efficient and simple way to read tabular data.


# 2. Analyzing the Data

Once the data is loaded into a DataFrame, some basic analysis is performed:

Average Score is calculated using the .mean() function.
Highest Score is determined using .max().
Lowest Score is calculated using .min().
These metrics are valuable for quickly understanding the overall performance of the class or dataset.


# 3. Creating the PDF

The FPDF library is then used to build a structured PDF report.

Page and Title: A new page is added, and a centered title "Student Score Report" is printed in bold.
Separator Line: A horizontal line is drawn to visually separate the title from the table section.
Table Section: The report then includes a table with headers for "Name" and "Score", followed by rows for each student in the dataset. For styling, the headers are bold and each row is enclosed in borders.
Statistical Summary: Below the table, the calculated average, highest, and lowest scores are displayed clearly.
Footer: A footer is added at the end of the document that includes the name of the report generator (in this case, “Bhavy Patel”) and the current date, pulled from the system using the datetime module. This gives the report a formal and professional touch.


# 4. Saving the PDF

Finally, the PDF is saved using pdf.output("report.pdf"), which creates the file in the local directory. A confirmation message is printed to let the user know that the report has been successfully generated.


# Key Highlights of This Task

Automation: This script removes the need for manually compiling student performance reports.
Data Analysis: Basic statistical metrics provide instant insight into the dataset.
Presentation: By using borders, fonts, and formatting, the report looks clean and professional.
Custom Footer: Including a dynamic date and author name makes it suitable for official documentation.
Scalability: This solution can be scaled to include additional statistics, visualizations, or multiple pages.

 
 # Conclusion
This task demonstrates the use of Python in a real-world scenario where data is not only analyzed but also presented in a professional format. Whether in academics, business, or personal projects, automating reporting using libraries like pandas and fpdf can save time and improve the consistency and quality of reporting. The output PDF generated from this script is easy to share, print, or archive, making it a practical addition to any data processing workflow.


# output

