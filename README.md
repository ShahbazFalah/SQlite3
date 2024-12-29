Client Information Manager

This Python script manages client information by collecting and storing data in an SQLite database. It validates user inputs to ensure accurate and clean data before saving it into the database. The data includes the client's name, phone number, and country.

Features

Database Integration: Uses SQLite to store and manage client information in a table named news.
Input Validation: Ensures the name is alphabetical, the phone number is numeric and exactly 11 digits, and the country is within a predefined list.
Dynamic Feedback: Provides real-time feedback to users about the validity of their inputs.
Country Validation: Supports a predefined list of countries, including:
IRAN
UK
USA
BAHRAIN
GERMANY
FRANCE
DENMARK
Display Records: Retrieves and displays all stored client information after new data is submitted.
How It Works

Name Validation:
Ensures the name is not empty and contains only letters.
Phone Number Validation:
Ensures the phone number is exactly 11 digits, numeric, and not empty.
Country Validation:
Ensures the country is in the predefined list and contains only alphabetic characters.
Data Storage:
Saves the validated name, phone number, and country into the SQLite database.
Display Records:
Displays all stored data in a tabular format after each submission.
Usage

Run the Script: Execute the script using Python:
python client_info_manager.py
Follow the Prompts:
Enter the required details: Name, Phone Number, and Country.
Ensure all inputs meet the validation criteria.
View Records:
After submitting data, the script will display all stored records.
Prerequisites

Python 3.6 or later.
SQLite (comes pre-installed with Python).
Example

Input:
What is your name? John
What is Your phone number? 12345678901
Where is your Country? UK
Output:
John has been registered successfully.
Thanks your phone number has been submitted.
Dear John from : UK Welcome aboard.
ID : 1, Name: John, Phone : 12345678901, Country : UK
Future Improvements

Add a GUI using Tkinter or PyQt for a more user-friendly interface.
Enable editing and deleting records from the database.
Expand the list of supported countries dynamically.
Author

[Shahbaz Falahian]
Location: London, UK
Interests: OpenCV, Robotics, AI, and Self-driving Cars.
Feel free to contribute to this project or suggest new features by submitting an issue or a pull request.

