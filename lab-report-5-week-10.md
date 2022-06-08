## Finding Tests with Different Results

To find the tests with different results, we first need to create a file that contains the outputs of all files. To do that, we use a bash for loop and store it in a different file.
The bash command to run a for loop and save it in a different file is ```bash (name_of_file) (name_of_file_to_save_in)```

From there on, we can use the ```vimdiff``` command on results.txt file to see tests which yeild different results.