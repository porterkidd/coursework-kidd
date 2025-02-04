# Shell Assignment
author: Porter Kidd
date: 2025-01-22

# Task 1
cd classes/GPGN268/coursework-kidd 
mkdir short-assignments

# Task 2
mv ~/Downloads/north-pacific-gyre ~/classes/GPGN268/coursework-kidd/short-assignments
cd north-pacific-gyre
ls -F

# Task 3
mkdir NENE-A NENE-B
mv *A.txt NENE-A
mv *B.txt NENE-B

# Task 4
cd NENE-A
NENE-A % wc N* | sort -r
cd ..
cd NENE-B
NENE-B % wc N* | sort -r
## The file NENE02018B.txt has the least number of lines.

# Task 5
cd ..
rm NENE*Z.txt

# Task 6
:wq
