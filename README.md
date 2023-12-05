# BizCardX-Extracting-Business-Card-Data-with-OCR
In Business development, while attending networking events, I get a lot of business cards from contacts/potential prospects. This solution can save a lot of time in extracting all those data in a digitalised data format

## EasyOCR: Effortless Optical Character Recognition for Python Developers
EasyOCR, as the name implies, is a Python package specifically designed for computer vision developers to seamlessly perform Optical Character Recognition (OCR) tasks. It enables effortless text extraction from images and scanned documents. In my project, I employed EasyOCR to extract text from business cards.
### EasyOCR: A Straightforward Approach to OCR
EasyOCR stands out as the most straightforward approach to OCR, offering several advantages:
•	Easy Installation: The EasyOCR package can be installed with a single pip command.
•	Minimal Dependencies: EasyOCR's minimal dependencies make it easy to set up your OCR development environment.
•	Simple Integration: Once installed, EasyOCR can be integrated into your project with a single import statement.
•	Streamlined OCR Process: OCR can be performed with just two lines of code: one to initialize the Reader class and another to apply OCR using the readtext function.
## BizCardX: A User-Friendly Tool for Business Card Data Extraction
BizCardX is a user-friendly tool that leverages OCR technology to extract information from business cards. The extracted data is classified using regular expressions and stored in a SQL database. A graphical user interface (GUI) built with Streamlit provides seamless user interaction.
### BizCardX: A Simple and Intuitive Interface
The BizCardX application features a simple and intuitive user interface that guides users through the entire process, from uploading business card images to extracting information. The extracted information is presented in a clean and organized manner, allowing users to add it to the database with a single click. The data stored in the database can be easily read, updated, and deleted as per user requirements.
## Project Demonstration
To experience BizCardX in action, visit the demo video by clicking here: [link to demo video]
## Technologies Employed
BizCardX utilizes various libraries to achieve its functionality:
 * Pandas: For creating a DataFrame to store the scraped data
 * mysql.connector: For storing and retrieving data from the SQL database
 * Streamlit: For building the graphical user interface
 * EasyOCR: For extracting text from images
## Workflow
To get started with BizCardX Data Extraction, follow these steps:
* Install the required libraries using pip install commands:
  - **pip install [Name of the library]**
* Execute the "main.py" script using the streamlit run command
  - **streamlit run main.py**
* A webpage will open in your browser. The app has three menu options: **HOME, UPLOAD & EXTRACT, MODIFY**.
  - **HOME:** Provides an overview of the project
  - **UPLOAD & EXTRACT:** Allows users to upload business card images and extract information
  - **MODIFY:** Enables users to modify and manage extracted data
* NOW, Upload a business card image.Once you do this, EasyOCR will extract the text from the uploaded image.
* The extracted text is then automatically processed and classified into various fields, such as **_company name, cardholder name, designation, mobile number, email address, website URL, area, city, state, and pin code_.**
* The classified data is displayed on the screen and can be edited by the user if necessary.
* Clicking the **"Upload to Database"** button stores the classified data in the MySQL database.
* The **"MODIFY"** menu allows users to access, **read, update, and delete** the uploaded data in the SQL database.

