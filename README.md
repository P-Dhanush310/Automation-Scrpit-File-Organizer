# File Organizer Automation Script

This Python script automatically organizes files in a target directory by categorizing them into folders based on their file types (e.g., Documents, Images, Videos, Others).

## Features

- Scans a specified directory for all files
- Classifies files based on their extensions
- Automatically creates folders for:
  - Documents
  - Images
  - Videos
  - Others
- Moves files into the appropriate folders
- Ensures clean and organized directory structure

## Technologies Used

- **Python 3.13.3**
- Built-in modules:
  - `os`
  - `shutil`

## File Categories & Supported Extensions

| Category  | File Extensions                          |
|-----------|------------------------------------------|
| Documents | `.pdf`, `.docx`, `.txt`, `.pptx`, `.xls` |
| Images    | `.jpg`, `.jpeg`, `.png`, `.gif`          |
| Videos    | `.mp4`, `.avi`, `.mov`, `.mkv`           |
| Others    | Any other file types not listed above    |

##  How to Use

1. **Clone this repository**:
   ```bash
   git clone https://github.com/yourusername/File_Organizer.git
   cd File_Organizer
   
