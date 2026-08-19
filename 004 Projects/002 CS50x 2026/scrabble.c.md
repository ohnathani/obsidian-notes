- step by step mind process ni nats
- review and redo
## IDEAS
---
-  make array with said values of letters only in CAPS
-  get user input
-  toupper user input (use for loop)
-  get string
-  get length
-  get value of letters from previous array, add to
-  get sum
-  compare sum a to sum b
-  print higher number, else tie


## ASK TO SELF??
---
- How do I make an array for ``letter_values``?
- how do I use ``toupper`` without printing?
- if not ``break`` on `isalpha` what?



## WHAT I KNOW
---
 - get user input using ``get_string`` from ``cs50.h``
 - 


## WHAT I DID WRONG
---
- 


## ISSUES:
---
- ``strlen`` gets length not letters themselves.... how to solve?


# CODE
---
``` C
// code by @ohnathani
#include <cs50.h>
#include <ctype.h>
#include <stdio.h>
#include <string.h>

int compute_scores(string word);

int main(void)
{
    string p1;
    string p2;
    int score1;
    int score2;
    
    // get words
    p1 = get_string("Player 1: ");
    p2 = get_string("Player 2: ");
    
    // compute scores
    score1 = compute_scores(p1);
    score2 = compute_scores(p2);
    
    // compare
    if (score1 > score2)
    {
        printf("Player 1 Wins!\n");
    }
    else if (score1 < score2)
    {
        printf("Player 2 Wins!\n");
    }
    else
    {
        printf("Tie!\n");
    }
}

int compute_scores(string word)
{
    int score = 0;
    int POINTS[] = {
        1, 3, 3, 2,  1, 4, 2, 4, 1, 8, 5, 1, 3,
        1, 1, 3, 10, 1, 1, 1, 1, 4, 4, 8, 4, 10 // letter values
    };
    for (int i = 0, n = strlen(word); i < n; i++)
    {
        // checks if alphabetical
        if (isalpha(word[i]))
        {
            // capitalizes
            char c = toupper(word[i]);
            // gets value of letter
            int index = c - 'A';
            // score add index
            score += POINTS[index];
        }

    }
    // return for main
    return score;

}
```


## INSIGHTS:
---
- 