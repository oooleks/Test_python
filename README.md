# Test_python
==============
Script:

Functionality of script: script should recursively walk the directory and detect all the files under that dir contains “keywords” and count the number of files for that sub dir. All results should be saved in a key: value array.

App creates data files with keywords and then detects all the files under certain dir for containing “keywords” and counts the number of files.

To execute: 
•	Place the script (Test.py) into the "C:\Test" folder;
•	Run it.

Parts of script:
1. Creates random number of files (no more than 30) in the root_dir with random number of keywords:
keyword1 = "^[a-zA-Z]+_TESTResult.* "
keyword2 = "abc "
keyword3 = "abcd ";

2. Recursively walks the “root_dir” and detects all the files under that dir contains “keywords”.
