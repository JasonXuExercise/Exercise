# Exercise
A lightweight code editor
Welcome!
This is a lightweight code editor including some awesome editor features!

Q & A

1.How to RUN:
You can download all the documents and click on the html file to RUN it.

2.Input suggestions:
The user types in the first(left) pane, considering that it is a textarea, please input keep in one line and do not use the ENTER key.

3.Main Idea:
There are six main steps to complete this lightweight code editor. Includes processing code, extracting keywords, using computed functions, matching keywords, matching objects, and keyword highlighting.

Step 1: Processing code:
Let's use "space" to cut the code, block the code and get an array

Step 2: Extracting keywords:
Let’s take the last array element to make the matching attributes and keywords

Step 3: Using the computed function provided by VUE, as long as the code attribute changes, solveCode will recalculate

Step 4: Matching keywords: 
Determine whether the last array element matches the key words: “var” , “class” and “function”. If it matches, construct an object and put it into the pre-selected array.

{
    Name: ''
    ，
    Value: ''
}
Then use the v-for command to loop out

Step 5: Matching objects:
Let’s use the last array element to cut with “ . ” to get an array

Judge the length of the array
If it is one, it means there is no “ . ”
If it is multiple, there is a “ . ”
And then corresponding value processing

Step 6: Keyword highlighting:
Let’s use regular matching first, then replace it.
