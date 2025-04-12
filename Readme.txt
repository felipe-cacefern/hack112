Readme.txt

Semester schedule generator

user will choose a major and the program will output a sample schedule with courses

1. Fetch classes needed to be taken from official CMU website
2. courses to be taken will be organized in a tree data structure
3. through searching the tree, program will create a list of courses could be
   taken. This will include genEds, major reqs, etc
4. Then utilizing a backtracking algorithm, the program will output a possible
   schedule with time compatibility checked.
    #could make a 2d array of time schedule and then mark taken as 1 not as 0
5. animation output course schedule