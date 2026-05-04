# Assignment-1-ITPM
Assignment 1 ITPM   https://www.pixelssuite.com/chat-translator
"# IT23820678-Test-cases"

    Project Title and Student Details

    Project Name: IT3040-ITPM Assignment 1

    Student Registration Number: IT23820678

    Target System: Swift Translator (Option 1 - Singlish to Sinhala)
📂 Repository Structure
       test_automation.py` - The main Python Playwright script that automates the browser interaction.
       Assignment_1 Test Cases.xlsx` - The Excel file containing the 50 negative test cases designed to fail the application's transliteration logic. The script reads inputs from here and automatically writes the Actual Outputs and Statuses back to the file.
       README.md` - Documentation and execution instructions.


    List the software required to run the project.

    Install Phython 

    Node.js.

    Installation Instructions

    git clone - https://github.com/LashanRavihara/test_automation.git

     from current directory in Command Prompt (i.e., D:\test_automation), run the following 
     commands: 
    • pip install -U pip 
    • pip install playwright openpyxl 
    • playwright install
    
    Running the Tests



    Run tests cmd terminal : python test_automation.py --excel "Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 8000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
    

   

    

  
