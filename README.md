The Zip File Extractor is a Python script that extracts the contents of ZIP files in a specified directory to a destination folder. It utilizes the pathlib module for working with file paths and the zipfile module for extracting ZIP archives.

Clone the repo:

``git clone https://github.com/your-username/zip-file-extractor.git``

Run the script:

``python zip_file_extractor.py``

Features:

- Recursively iterates through a directory and its subdirectories to find ZIP files.
- Extracts the contents of each ZIP file to a destination folder.
- Supports extracting multiple ZIP files in one run.

Config:

- Modify the root_dir variable to specify the directory containing the ZIP files to be extracted.
- Adjust the destination_path variable to specify the destination folder where the contents of the ZIP files will be extracted.

Ex., Suppose you have the following directory structure:

``
project/
    ├── file1.zip
    ├── folder1/
    │   └── file2.zip
    ├── folder2/
    │   └── file3.zip
    └── folder3/
        └── folder4/
            └── file4.zip
``

After running the script, the contents of the ZIP files will be extracted to the destination folder:

``
destination/
    ├── file1/
    ├── file2/
    ├── file3/
    └── file4/
``
