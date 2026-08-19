Date: 2026-06-21
Tags: #arrays #cs50 #C #strings #CLA #exitstatus

refer to [[001 C CS50 Week 1 Notes]] for syntax notes
## Debugging 
---
- use breakpoints to add a "stop"
	- red thing on the left side of text editor 
- ``step over`` and ``step into`` 
	- ``step over`` runs code
	- ``step into`` goes step by step
-  try figuring it out yourself and solve problems by yourself

## Arrays
---
 - ``bool`` ``char`` 1 byte
 - ``int`` ``float`` 4 bytes
 - ``long`` ``double`` 8 bytes
 - ``string`` x bytes

- ``int scores[3]`` tells the compiler to make 3 b2b places is memory in size ``int`` (4 bytes) aka three ``scores``
``` C
#include <cs50.h>
#include <stdio.h>

int main(void)
{
    // Scores
    int scores[3]; // use of an array (hardcoded numbers bad)
    scores[0] = 72;
    scores[1] = 73;
    scores[2] = 33;

    // Print average
    printf("Average: %f\n", (scores[0] + scores[1] + scores[2]) / 3.0);
}
```

- use of loop in code (revised) if want user input
``` C
#include <cs50.h>
#include <stdio.h>

int main(void)
{
    // Get scores
    int scores[3];
    for (int i = 0; i < 3; i++) // loops 3 times ONLY
    {
        scores[i] = get_int("Score: "); // ask user input
    }

    // Print average
    printf("Average: %f\n", (scores[0] + scores[1] + scores[2]) / 3.0);
}
```

- use of a constant—doesn't need to lengthen code, easily "upgradable" for future updates
``` C
// Averages three numbers using an array, a constant, and a helper function

#include <cs50.h>
#include <stdio.h>

// Constant
const int N = 3;

// Prototype
float average(int length, int array[]);

int main(void)
{
    // Get scores
    int scores[N];
    for (int i = 0; i < N; i++) // use of N for x amount of loops
    {
        scores[i] = get_int("Score: ");
    }

    // Print average
    printf("Average: %f\n", average(N, scores));
}

float average(int length, int array[]) // Calculates average calls from previous line ``average(N, scores)`` sub length for n and array[] for scores
{
    // Calculate average
    int sum = 0;
    for (int i = 0; i < length; i++) // uses N amount to loop
    {
        sum += array[i]; // 0+score1= sum1+ sum2 = sum12 + sum3
    }
    return sum / (float) length; // divides by N amount of times
}
```

## Strings
---
- array of values using type ``char``; array of characters
- ``NUL`` character ``\0`` is aka the end of a string
	-  different from ``NULL``
- can be expressed as ``char`` ``int`` or ``string``
	- a ``string`` is an array of chars

- Array of strings
``` C
#include <cs50.h>
#include <stdio.h>

int main(void)
{
    string words[2];

    words[0] = "HI!";
    words[1] = "BYE!";

    printf("%s\n", words[0]);
    printf("%s\n", words[1]);
}
```

- Array of array of strings

``` C
#include <cs50.h>
#include <stdio.h>

int main(void)
{
    string words[2];

    words[0] = "HI!";
    words[1] = "BYE!";

    printf("%c%c%c\n", words[0][0], words[0][1], words[0][2]);
    printf("%c%c%c%c\n", words[1][0], words[1][1], words[1][2], words[1][3]);
}
```

## String Length
---
- common problem in programming—to find length of string

- finding string length
``` C
#include <cs50.h>
#include <stdio.h>

int main(void)
{
	// prompt
	string name = get_string("Name: ");
	
	// count number of characters till NUL '\0'
	int n = 0;
	while (name[n] !- '\0')
	{
		n++;
	}
	printf("%i\n", n);
}
```

- revised code with function 
``` C
#include <cs50.h>
#include <stdio.h>

int string_length(string s);

int main(void)
{
    // Prompt for user's name
    string name = get_string("Name: ");
    int length = string_length(name);
    printf("%i\n", length);
}

int string_length(string s)
{
    // Count number of characters up until '\0' (aka NUL)
    int n = 0;
    while (s[n] != '\0')
    {
        n++;
    }
    return n;
}
```

- also can use ``strlen()`` function from ``string.h`` 
``` C
#include <cs50.h>
#include <stdio.h>
#include <string.h>

int main(void)
{
    // Prompt for user's name
    string name = get_string("Name: ");
    int length = strlen(name);
    printf("%i\n", length);
}
```

- uppercase.c program
``` C
#include <cs50.h>
#include <stdio.h>
#include <string.h>

int main(void)
{
    string s = get_string("Before: "); // Before
    printf("After:  "); // After
    for (int i = 0, n = strlen(s); i < n; i++) // ASCII loop
    {
        if (s[i] >= 'a' && s[i] <= 'z') // check for lowercases
        {
            printf("%c", s[i] - 32; // if lowercase -32 in ASCII because -32 are uppercases
        }
        else
        {
            printf("%c", s[i]);
        }
    }
    printf("\n");
}
```

- same program but with ``ctype.h`` using ``islower`` and ``toupper`` 
	- no more ``if`` ``else`` statements because ``toupper`` only knows lowercase to uppercase
``` C
#include <cs50.h>
#include <ctype.h>
#include <stdio.h>
#include <string.h>

int main(void)
{
    string s = get_string("Before: ");
    printf("After:  ");
    for (int i = 0, n = strlen(s); i < n; i++)
    {
        printf("%c", toupper(s[i]));
    }
    printf("\n");
}
```

## Command-Line Arguments
---
- ``argc`` - number of command line arguments
- ``argv`` - array of strings in terminal interacting with code

``` C
#include <cs50.h>
#include <stdio.h>

int main(int argc, string argv[])
{
    if (argc == 2)
    {
        printf("hello, %s\n", argv[1]);
    }
    else
    {
        printf("hello, world\n");
    }
}
```

- ./filename insertstringhere
- prints insertstringhere
``` C
// Prints command-line arguments

#include <cs50.h>
#include <stdio.h>

int main(int argc, string argv[])
{
    for (int i = 0; i < argc; i++)
    {
        printf("%s\n", argv[i]);
    }
}
```

## Exit Status
---
- when program ends exit code is provided
- no error ``0``
- error ``1``

- if fail to provide ``./status insertstringhere`` exit ``1`` else ``0``
``` C
// Returns explicit value from main

#include <cs50.h>
#include <stdio.h>

int main(int argc, string argv[])
{
    if (argc != 2)
    {
        printf("Missing command-line argument\n");
        return 1;
    }
    printf("hello, %s\n", argv[1]);
    return 0;
}
```