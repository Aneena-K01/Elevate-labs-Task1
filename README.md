Objective:To clean and prepare the raw Netflix dataset by handling missing values, removing duplicates, standardizing formats, and correcting data types to make it analysis-ready.
What I did in this task is,
Checked and handled missing values using isnull() and fillna().
Removed duplicate records using drop_duplicates().
Standardized text columns by removing extra spaces and ensuring consistent formatting.
Converted the date_added column to proper datetime format.
Renamed column headers to lowercase and replaced spaces with underscores.
Verified and corrected data types (e.g., ensured release_year is integer).
Split the duration column into duration_value (numeric) and duration_unit (minutes/seasons) for better structure.
