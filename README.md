# Automated File Sorter

A simple Python script that automatically organizes files in a folder by sorting them into subfolders based on file type (CSV, PNG, TXT).

## What it does

- Scans a given folder for files
- Creates subfolders: csv files, png files, text files
- Moves each file into its matching subfolder based on extension
- Skips files that have already been moved (avoids duplicate errors)

## How to run

1. Clone this repository or download the notebook/script
2. Open it in Jupyter Notebook (or run as a .py file)
3. Run the code
4. When prompted, enter the full path of the folder you want to organize

Example input:
Enter the folder path to sort: D:/Downloads

## Tech used

- Python
- os module
- shutil module

## What I learned

This was a beginner project to practice:
- Working with file paths and directories
- Automating repetitive file-handling tasks
- Using os.listdir(), os.makedirs(), and shutil.move()

## Future improvements

- Support more file types (pdf, jpg, docx, etc.)
- Use os.path.join() for better cross-platform path handling
- Add error handling for invalid paths
