# cheatsheet

## SSH

#### Port Forwarding
ssh -L 7000:localhost:7000 username@example.com

## Linux/Bash

#### Delete all php files in folder and subfolder
find . -name "*.php" -type f -delete

#### Find files inlcuding specific string in folder and subfolder
grep -r -l "string" .

#### Rename filenames with sed
rename s/Jubil├дumss├дule/Jubiläumssäule/ *
