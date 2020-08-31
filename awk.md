# AWK
## Structure
```
# run once at the begin
BEGIN {
		
}
# run for each line in the document
{

}
# run once at the end
END {

}

```

## Separator
```
BEGIN {
	# input field separator
	FS=";"
	# output field separator
  	OFS=" "
	# example: "a;b;c" ==> "a b c"
	
	# input record separator
	RS="\n"
	# output record separator
	ORS="\r"
	# example: "a;b;c\nd;e;f" ==> "a;b;c\rd;e;f"
}
```

## Variable
```
{
	# output field 1 and 3
	print $1, $3
	# example: "1 2 3" ==> "1,3"

	# number of field
	print $NF
	# example: "1 2 3" ==> "3"
	
	# number of records
	print $NR
	# example: "1 2 3\n4 5 6 7" ==> "3,4"
}
```

## Print
```
{
	
}
```






