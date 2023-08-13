# mygrep
This is a basic command on linux based terminal used for searching a pattern in a file linewise. It is made using Data Structures and c language. 
# Setup
1. Download the mygrep folder
2. Open the terminal and use the  `make` command this will triger the Makefile
3. Now you can use the mygrep

# Usage
Below are the sample usage of the command:

./mygrep -i pattern sample.txt

./mygrep -v pattern sample.txt

./mygrep -w pattern sample.txt

./mygrep -q pattern sample.txt

./mygrep -b pattern sample.txt

./mygrep -h pattern sample.txt

./mygrep -H pattern sample.txt

./mygrep -m 6 pattern sample.txt

./mygrep -r pattern


./mygrep -e pattern -e pattern sample.txt

./mygrep -c grep sample.txt
./mygrep -f test.txt -e pattern sample.txt

./mygrep [pattern] sample.txt

./mygrep [pattern-pattern] sample.txt

./mygrep patte?rn sample.txt

./mygrep pat.tern sample.txt

./mygrep ^pattern sample.txt

./mygrep pattern$ sample.txt

./mygrep pat/te/r/n sample.txt
./mygrep [pattern][pattern] sample.txt
