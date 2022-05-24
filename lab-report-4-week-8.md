[Link to Markdown-Parser](https://github.com/ayushs2725/markdown-parser)

[Link to Reviewed File](https://github.com/ayushs2725/markdown-parser-review)



## Snippet One

### JUnit Test
![](R4P11.png)

### Expected Output
![](R4P1.png)

### JUnit test on Markdown-Parser
![](R4P5.png)

## JUnit test on Reviewed File 
![](R4P6.png)

I do have a fix in mind but I'm not exactly sure how to implement it. We can do it by checking if any of the square bracket, either opening or closing, is contained between ```" "```. At the same time, we have to make sure that it's not a single ```"``` but it should be between two of them 


## Snippet Two

### JUnit Test
![](R4P12.png)

### Expected Output
![](R4P2.png)

### JUnit test on Markdown-Parser
![](R4P7.png)

## JUnit test on Reviewed File 
![](R4P8.png)

I do have a fix in mind but not exactly sure how to change it. We can implement a code that that only considers the first opening square bracket and the last closing bracket before the opening paratheses.

## Snippet Three

### JUnit Test
![](R4P13.png)

### Expected Output
![](R4P3.png)

### JUnit test on Markdown-Parser
![](R4P9.png)

## JUnit test on Reviewed File 
![](R4P10.png)

One of the simple fixes that I have in mind is to include a conditional that checks if the input file contains any new line characters. If it does, then, we can continue.