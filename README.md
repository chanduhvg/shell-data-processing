# Power Shell Commands
- ```cd```- Change directory
- ```ls```- List all the files in the given directory
- ```mkdir```- Make a new directory
- ```ni```-Creating Files with new item

# Git bash commands
## The command you used to find the most common words, sorted.
- tr transforms the file content - tr (bash) commands 
## Transform each space ' ' into a return character '\12' (aka ASCII line feed)

tr ' ' '\12' < returnedfile

## Pipe the output to sort (send the results of one command as input into another command)

tr ' ' '\12' < returnedfile | sort

## Pipe the sorted output to uniq -c to count

tr ' ' '\12' < returnedfile | sort | uniq -c

## Pipe the reduced output to sort with -nr flag

tr ' ' '\12' < returnedfile | sort | uniq -c | sort -nr

## Redirect the output to result.txt

tr ' ' '\12' < result.txt | sort | uniq -c | sort -nr > result.txt

## Data file
[returned.txt](https://github.com/chanduhvg/shell-data-processing/blob/master/returned.txt)

## Result 
[result.txt](https://github.com/chanduhvg/shell-data-processing/blob/master/result.txt)