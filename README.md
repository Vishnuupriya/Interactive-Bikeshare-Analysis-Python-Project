US Bikeshare Data Explorer
=========================

Project Overview
----------------
This project is a terminal-based Python application that explores and analyzes
bikeshare data for three major cities in the United States: Chicago, New York
City, and Washington.

The program allows users to interactively select a city and apply optional
filters based on month and day. It then computes descriptive statistics to
provide insights into bikeshare usage patterns. The application uses raw user
input to create an interactive experience in the terminal.


Objectives
----------
- Explore bikeshare data using Python
- Analyze usage patterns across different cities
- Allow users to filter data by month and day
- Display meaningful statistics related to trips and users
- Build an interactive command-line application


Key Features
------------
- Interactive terminal-based user input
- City selection:
  - Chicago
  - New York City
  - Washington
- Optional filtering by:
  - Month
  - Day of week
  - No filter (all data)
- Filter confirmation checkpoint before analysis
- Graceful handling of empty datasets
- Displays:
  - Most common month, day, and start hour
  - Most popular start and end stations
  - Most frequent trip combination
  - Total and average trip duration
  - User type counts
  - Gender counts
  - Birth year statistics
- Option to view raw trip data in chunks (5 rows at a time)
- Restart or exit option for clean program termination


Technologies Used
-----------------
- Python 3
- Pandas
- NumPy


Project Files
-------------
- bikeshare.py         : Main Python script
- chicago.csv          : Bikeshare data for Chicago
- new_york_city.csv    : Bikeshare data for New York City
- washington.csv       : Bikeshare data for Washington
- README.txt           : Project documentation


How to Run the Project
----------------------
1. Ensure Python 3 is installed on your system.
2. Install required libraries:
   pip install pandas numpy
3. Place all CSV files in the same directory as the Python script.
4. Run the program using:
   python bikeshare.py
5. Follow the on-screen instructions in the terminal.


Sample Program Flow
-------------------
- Select a city
- Choose month and day filters or select 'all'
- Confirm selected filters
- View computed statistics
- Optionally view raw trip data
- Restart or exit the program


Concepts Demonstrated
---------------------
- Python functions and loops
- Conditional statements
- User input validation
- Data filtering and aggregation
- Datetime manipulation
- Handling missing data
- Modular programming
- Interactive terminal application design


Notes
-----
- If no data matches the selected filters, the program notifies the user and
  allows retrying.
- Some datasets may not contain Gender or Birth Year information; the program
  handles such cases gracefully.


Future Enhancements
-------------------
- Add data visualizations
- Support additional cities
- Export results to files
- Improve user interface with menus or colors


Author
------
Developed by: Vishnuu Priya

License
-------
This project is intended for educational and learning purposes.
