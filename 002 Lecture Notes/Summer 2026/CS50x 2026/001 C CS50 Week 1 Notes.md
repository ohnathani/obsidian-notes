Date: 2026-06-19
Tags:  #C #cs50 
## Linux
---
- "compiler" used ``make``
- CLI commands
	- ``cd``  - change dir
	- ``cp`` - copy file & dir
	- ``ls `` - file list
	- ``mkdir`` - make dir
	- ``mv`` - move file & dir
	- ``rm`` - remove file
	- ``rmdir`` - remove dir

## Conditionals
---
```C
if (x < y)
{
	printf("x is less than y\n")
}
else if (x > y)
{
	printf("x is greater than y\n")
}
else
{
	printf("x is equal to y\n")
}
```
- **NOTE:** don't use ``else if`` if not needed, ALWAYS use less computing for more efficient code

## Data Types
---
- Types of data in c
```
	  bool
	  char
	  float
	  int
	  long
	  string
	  etc...
```

## Format Codes in C
---
- Placeholders that start with ``%`` and used alongside ``printf`` are called **format codes**
- List of format codes and their use cases
	- ``%c`` char
	- ``%f`` float
	- ``%i`` int
	- ``%li`` long
	- ``%s`` string
## Variables
---
- you can assign values to ints
	- ``int counter = 0``
	- to add to ``counter``
		- ``counter = counter + 1;``
		- ``counter += 1;``
		- ``counter++;``
	-  same logic with subtraction
		- ``counter--;``

## compare.c
---

```C
#include <cs50.h>
#include <stdio.h>

int main (void)
{
	// promts user for int
	int x = get_int("What is x? ");
	int y = get_int("What is y? ");
	
	// compare
	if (x < y)
	{
		printf("x is less than y\n")
	}
	else if (x > y)
	{
		printf("x is greater than y\n")
	}
	else
	{
		printf("x is equal to y\n")
	}
}
```

## agree.c
---
```C
#include <cs50.h>
#include <stdio.h>

int main(void)
{
	 // prompt
	 char c = get_char("Do you agree? y/n ");
	 // check
	 if (c == 'y' || c == 'Y') // || means OR
	 {
		 printf("agreed\n");
	 }
	 else if // no need (c == 'n' || c == 'N') ALWAYS use less computing
	 {
		 printf("not agreed\n");
	 }
}
```

## Loops
---
- use of ``for`` loop (count)
```C
#include <stdio.h>

int main(void)
{
	for (int i = 0; i > 3; i++) // set i = 0; count 0 to 3; add +1 till 3
	{
		printf("meow\n");
	}
}
```
- use of ``while`` loop (wait)
```C
#include <stdio.h>

int main(void)
{
    int i = 0;
    while (i < 3)
    {
        printf("meow\n");
        i++;
    }
}
```
- ask for ``n``, also restricts user from typing 0 and below
``` C
#include <cs50.h>
#include <stdio.h>

int main(void)
{
    int n;
    do // initialize do while loop
    {
        n = get_int("What's n? ");
    }
    while (n < 0);

    for (int i = 0; i < n; i++)
    {
        printf("meow\n");
    }
}
```

| Feature   | while                             | for                       |
| --------- | --------------------------------- | ------------------------- |
| Structure | condition only                    | init + condition + update |
| Best for  | unknown loops                     | counted loops             |
| Control   | external                          | built-in                  |
| Risk      | forgetting update → infinite loop | less error-prone          |

## Functions
---
- ``void`` function doesn't return values; set to ``3`` in this example

``` C
#include <stdio.h>

void meow(void);

int main(void)
{
	for (int = 0; i < 3; i++)
	{
		meow(); // uses function "meow"
	}
}

void meow(void) // function meow
{
	printf("meow\n");
}
```

- Dynamic Code. Ask user for ``n`` input before output

``` C
#include <cs50.h>
#include <stdio.h>

// helper
int get_positive_int(void);
void meow(int n);

int main(void)
{
    int n = get_positive_int(); // number n
    meow(n); // n number of meows
}

// Get number of meows
int get_positive_int(void)
{
    int n;
    do
    {
        n = get_int("Number: "); // prompt user
    }
    while (n < 1);
    return n;
}

// Meow some number of times
void meow(int n)
{
    for (int i = 0; i < n; i++)
    {
        printf("meow\n");
    }
}
```

## Correctness, Design, and Style
---
- code is evaluated in 3 axes
	- "Does the code run as intended?"
	- "How well is the code designed?"
	- "How aesthetically pleasing is the code?"

## Mario
---
- copy with ``#``
![[Pasted image 20260619193931.png]]

``` C
#include <stdio.h>

void print_row(int width);

int main(void)
{
	const int i = 3;
	for (int i = 0; i < n; i++) 
	{
		print_row(n); // prints row
	}
}

void print_row(int width)
{
	for (int i = 0; i < width; i++) // still uses int i cause different scope
	{
		printf("#");
	}
	printf("\n"); // puts new line inbetween every 3#
}
```
## Operators
---
- math operations
	-  ``+`` add
	-  ``-`` subtract
	-  ``*`` multiply
	-  ``/`` division
	-  ``%`` remainder
		- only works with ``int
		- even/odd checks
		- turn systems
		- hash tables
		- date & time
