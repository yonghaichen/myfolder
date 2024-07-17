`variableName=/dir1/dir2/dir3/my.file.txt`  

`${#variableName}`    　　　　　　　　　 to print the length of a string  　

`${string:position}`        --> returns a substring starting from `$position` till end.   
`${string:position:length}` --> returns a substring of `$length` characters starting from `$position`.









`${string#substring}`  To delete the shortest substring match from front of `$string`.   
`${string##substring}`  To delete the longest substring match from front of `$string`.  

`${string%substring}`  To delete the shortest substring match from back of `$string`   
`${string%%substring}` To delete the longest substring match from back of `$string`







　　　　　　　　     