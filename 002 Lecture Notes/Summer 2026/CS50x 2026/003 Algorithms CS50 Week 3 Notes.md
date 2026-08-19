## Linear Search 
---
- as the name suggests, the computer searches in a linear manner—left to right from location ``0`` to ``n amount of arrays`` 
- human pseudocode looks like:
``` C
For each door from left to right
	If 50 is behind door 
		return true
return false
```

- translated with math;
``` C
For i from 0 to n - 1
	If 50 is behind doors[i]
		return true
return false
```

## Binary Search 
---
- if numbers are arranged and sorted pseudocode for binary search looks like
``` C
If no doors left
	return false
If 50 is behind middle door 
	return true
Else if 50 < middle door
	search left half
Else if 50 > middle door
	search right half
```

- modified with math
``` C
If no doors left
	return false
If 50 is behind doors[middle]
	return true
Else if 50 < doors[middle]
	search doors[0] throught doors[middle - 1]
Else if 50 > doors[middle]
	search doors[middle + 1] through doors[n - 1]
```

## Running Time
---
- how much time it takes an algorithm to solve a problem
- can be expressed in *big O* notation ![[Pasted image 20260630192914.png]]
- Computer scientists discuss efficiency in terms of order of various running times (how long an algorithm runs when input size n increases)
- Common running times are as follows
	- $O(n^2)$
	- $O(n  log  n)$
	- $O(n)$ // Linear Search
	- $O(log n)$ // Binary Search
	- $O(1)$ // Constant Time
- Having $O(n^2)$ being the slowest and $O(1)$ being the fastest
- Programmers not worst and best cases aka upper bound and lower bound
- Ω symbol is used to denote the best case of an algorithm, such as $Ω(logn)$
- Θ symbol is used to denote that both upper and lower bound cases are the same. // Run times are the same.
- *Asymptotic notation* is the measure of how well algorithms perform as the input gets larger and larger

## search.c
---
- implementing linear search ``search.c`` 
``` C
#include <cs50.h>
#include <stdio.h>

int main(void)
{
	// array of integers
	int number[] = {20, 500, 10, 5, 100, 1, 50};
	
	// search for number
	int n = get_int("Number: ");
	for (int i = 0; i < 7; i++)
	{
		if (numbers[1] == n)
		{
			printf("Found\n");
			return 0;
		}
	}
	printf("Not found\n");
	return 1;
}
```

- can also use a string in an array
- uses ``strcmp`` (string compare) from ``string.h`` library
``` C
#include <cs50.h>
#include <stdio.h>
#include <string.h>

int main(void)
{
	// array of strings
	string strings[] = {"Nat", "Snow", "Virn", "Kirby"};
	
	// search for string
	string s = get_string("String: ");
	for (int i = 0; i < 4; i++)
	{
		if (strcmp(strings[i], s) == 0)
		{
			printf("Found\n");
			return 0;
		}
	}
	printf("Not found\n");
	return 1;
}
```

## phonebook.c
---
``` C
#include <cs50.h>
#include <stdio.h>
#include <string.h>

int main(void)
{
	// array of strings
	string names[] = {"Nat", "Snow", "Virn"};
	string numbers[] = {"123", "123", "321"};
	
	// search for name
	string name = get_string("Name: ");
	for (int i = 0; i < 3; i++)
	{
		if (strcmp(names[i], name) == 0)
		{
			printf("Found %s\n", numbers[i]);
			return 0;
		}
	}
	printf("Not found\n");
	return 1;
}
```

## Structs
---
- feature in C that allows to create own data type
- ``person`` struct with ``name`` and ``number`` 
``` C
typedef struct
{
	string name;
	string number;
} person; // name of struct
```

- improved ``phonebook.c``
``` C
#include <cs50.h>
#include <stdio.h>
#include <string.h>

typedef struct
{
	string name;
	string number;
} person;

int main(void)
{
	person people[3]; // make array with new data type
	
	people[0].name = "Nat";
	people[0].number = "123";
	
	people[1].name = "Snow";
	people[1].number = "123";
	
	people[2].name = "Virn";
	people[2].number = "321";
	
	// get name
	string name = get_string("Name: ");
	for (int i = 0; i < 3; i++)
	{
		if (strcmp(people[i].name, name) == 0)
		{
			printf("Found %\n", people[i].number);
			return 0
		}
	}
	printf("Not found\n")
	return 1;
}
```

## Sorting and Selection Sort
---
- making unsorted list sorted
- makes it less taxing on the computer
``` C
For i from 0 to n - 1
	Find the smallest number between numbers[i] and numbers[n - 1]
	Swap smallest number with numbers[i]
```

- Summary: first iteration takes ``n - 1`` steps, then second ``n - 2`` steps, so forth
```
(n - 1) + (n - 2) + (n - 3) + ... + 1
```

- can be further simplified to $n(n - 1)/2$ or more simply, $O(n^2)$. 
- In the worst case or upper bound, selection sort is in the order of $O(n^2)$. 
- In the best case or lower bound, selection sort is in the order $Ω⁡(n^2)$ 

## Bubble Sort
---
- Bubble sort - sorting algorithm wherein numbers are swapped to "bubble" larger elements to the end.
``` C
Repeat n - 1 times
	For i from 0 n - 2
		If numbers[i] and numbers [i + 1] out of order
			Swap
	If no swaps
		Quit
```

- can be analyzed as follows:
	- $(n - 1) * (n-1)$
	- $n^2 - n - n + 1$
	- $n^2 - 2n + 1$
	- $O(n^2)$
- In the worse case or upper bound, bubble sort is in the order of $O(n^2)$
- In the best case or lower bound, bubble sort is in the order of $O(n)$
## Recursion
---
- How could we improve efficiency in sorting?
- Recursion - when function calls itself
``` C
If no doors left
    Return false
If number behind middle door
    Return true
Else if number < middle door
    Search left half
Else if number > middle door
    Search right half
```

- no recursion
``` C
1  Pick up phone book
2  Open to middle of phone book
3  Look at page
4  If person is on page
5      Call person
6  Else if person is earlier in book
7      Open to middle of left half of book // implement recursion to this
8      Go back to line 3
9  Else if person is later in book
10     Open to middle of right half of book
11     Go back to line 3
12 Else
13     Quit
```

- with recursion
``` C
1  Pick up phone book
2  Open to middle of phone book
3  Look at page
4  If person is on page
5      Call person
6  Else if person is earlier in book
7      Search left half of book
9  Else if person is later in book
10     Search right half of book
12 Else
13     Quit
```

- ``mario-less`` example from [[001 C CS50 Week 1 Notes]]  [[mario.c]] 

- ``iteration.c`` - similar to my solution, which did not use recursion
``` C
#inlcude <cs50.h>
#include <stdio.h>

void draw(int n);

int main(void)
{
	// get height
	int height = get_int("Height: ");
	
	// draw pyramid
	draw(height);%
}

void draw(int n);
{
	// draw pyramid of height n
	for (int = 0; i < n; i++)
	{
		for (int j = 0; j < i + 1: j++)
		{
			printf("#");
		}
		printf("#");
	}
}
```

- ``recursion.c``
	-  use of own code in the same function
``` C
#include <cs50.h>
#include <stdio.h>

void draww(int n);

int main(void)
{
	// get height
	int height = get_int("Height: ");
	// draw pyramid
	draw(height);
}

void draw(int n)
{
	// if nothing to draw
	if (n <=0)
	{
		return;
	}
	// Draw pyramids of height n - 1
	draw(n - 1);
	
	// Draw one more row of width n 
	for (int i = 0; i < n, i++)
	{
		printf("#");
	}
	printf("\n");
}
```

## Merge Sort
---
- very efficient sorting algorithm
``` C
If only one number 
	Quit
Else
	Sort left half of numbers
	Sort right half of numbers
	Merge sorted halves
```

- Example:
```
6341
```
- algorithm asks "is this one number?" else, continue
```
63|41
```
- split
```
6|3
```
- sort
```
36|41
```
- check other and do same process
```
36|14
```
- merge and complete
```
1346
```
- quit