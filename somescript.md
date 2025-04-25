# Notes
To save the written code type:

`git checkout -b` <branchname> or
`git add .` = Adds it to the already existing branch
`git commit`
`git push --set-upstream origin` "Branch you're working in"


To change a file name:

mv "name the exact path where the file is located"
e.g. `mv projects/learning-github/somescript.sh projects/learning-github/somescript.txt`

This changes the file name from somescript.sh to somescript.txt


How to build and run a C-File

`gcc main.c -o main`
main.c is the source file
-0 main tells gcc to output an executable named main (you can call it anything)

`./main` this runs the program

If there are multiple `.c` files, list them all
`gcc file1.c file2.c -o program`
