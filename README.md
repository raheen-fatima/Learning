# The Backend Development Path!

i learn echo , nano , touch , mkdir , rmdir commands

find command to find the file and dir 
- find . -type f/d (f for file and d for dir) 
- find . -type f -iname "FileName*"
    // ends with .txt
    find . -type f -iname "*.txt"

    // contains "log" anywhere
    find . -type f -iname "*log*"

    // starts with "data" and ends with .csv
    find . -type f -iname "data*.csv"

mv command for rename and move item

- syntax : mv [name] [new name] - syntax : mv [name] [new location]

cp command is for copy

- Syntax : cp [original name] [copy name]
- Copy file : cp team.txt team_backup.txt
- Copy Dir : cp -r cities cities_backup
- `-r option , means that every item inside the directory at any lvl copied individually`
