## Data Structures
---
- forms of organization of memory 
- has different ways to organize memory
- *Abstract data types* - data types that are conceptually imaginable
	- Learn CONCEPTUAL data structures first (makes it easier to implement CONCRETE data stuctures)

## Queues
---
- form of an abstract data structure
- have properties such as: FIFO (First in, First Out)
	- ex. supermarket line
- may enqueue or dequeue
- expressed in code
``` C
const int CAPACITY = 50 

typedef struct
{
	person people[CAPACITY];
	int size
} queue;
```
Notice that array ``people`` is of type ``person``. ``CAPACITY`` is how high the queue could be. The integer ``size`` is how full the queue actually is, regardless how much it *can* hold.

## Stacks
---
- contrast of queue
- have properties such as: LIFO (Last in, First Out)
	- ex. clothes stack
- may push or pop
- expressed in code
``` C
const int CAPACITY = 50

typedef struct
{
	person people[CAPACTIY];
	int sieze
} stack;
```
- same code as queue
- can be improved by having a dynamic stack adjusting size

## Arrays
---
#arrays 
- a block of contiguos memory
- ``list.c`` ver 1
``` C
// list of numbers in fixed size

#include <stdio.h>
{
	// List of size 3
	int list[3];
	
	// Initialize list with numbers
	list[0] = 1;
	list[1] = 2;
	list[2] = 3;
	
	// Print list
	for (int i = 0; i < 3; i++)
	{
		printf("%i\n", list[i]);
	}
}
```
- try to add a ``4``  to the memory (list), how?
- how to connect to different locations in memory?
- in memory, other programs use memory and store them elsewhere, which may cause some overlap. Though, many of these values are unused (garbage values)
	  ![[Pasted image 20260803122451.png]]
-  copy numbers to garbage values and add ``4``
		![[Pasted image 20260803122733.png]]
		![[Pasted image 20260803122743.png]]
-  use of pointers to execute this in code
``` C
// Implements list of numebrs with an array of dynamic size

#include <stdio.h>
#include <stdlib.h>

int main(void)
{
	// List size 3
	int *list = malloc(3 * sizeof(int));
	if (list == NULL)
	{
		return 1;
	}
	
	// Initialize list of size 3 with numbers
	list[0] = 1;
	list[1] = 2;
	list[2] = 3;
	
	// List of size 4
	int *tmp = malloc(4 * sizeof(int));
	if (tmp == NULL)
	{
		free(list);
		return 1;
	}
	
	// Copy list of size 3 into list of size 4
	for (int i = 0; i < 3; i++)
	{
		tmp[i] = list[i];
	}
	
	// Add number to list of size 4
	tmp[3] = 4;
	
	// Free list of size 3
	free(list);
	
	// Remember list of size 4
	list = tmp;
	
	// Print list 
	for (int i = 0; i < 4; i++)
	{
		printf("%i\n", list[i]);
	}
	
	// Free list
	free(list);
	return 0;
}
```
 - list of 3 integers created
 - 3 mem addresses are assigned to 1, 2, and 3
 - New list of 4 (``tmp``) is created
 - orig values copied to ``tmp``
 - 4 added to ``tmp``
 - original list ``list`` freed with ``free(list)``
 - ``list`` pointer updated to point to ``tmp``
 - print
 - ``tmp`` (pointed to by ``list``) freed
 
- Can also be coded using ``realloc`` instead of a ``for`` loop
``` C
// Implements list of numbers with array of dynamic size using realloc

#include <stdio.h>
#include <stdlib.h>

int main(void)
{
	// List size 3
	int *list = malloc(3 * sizeof(int));
	if (list == NULL)
	{
		return 1;
	}
	
	// Initialize list of size 3 with numbers
	list[0] = 1;
	list[1] = 2;
	list[3] = 3;
	
	// Resize list to be of size 4
	int *tmp = realloc(4 * sizeof(int));
	if (tmp == NULL)
	{
		free(list);
		return 1;
	}
	list = tmp;
	
	// Add number to list
	list[3] = 4;
	
	// Print list
	for (int i = 0; i < 4; i++)
	{
		printf("%i\n", list[i]);
	}
	
	// Free list
	free(list);
	return 0;
}
```
- REMINDER: *don't allocate more memory than what is required, since it taxes more system requirements that what is needed*

## Linked List
---
- ``struct`` data type that you make A ``.`` allows to access variables in that struct
- ``*`` operator used to declare pointer or dereferencing a variable
- NEW operator ``->`` allows user to go to address and look inside a struct
	- uses ``ptr->age = 18``, rather than ``(*ptr).age = 18``
	- easier to when both ``*`` and ``.`` are needed
-  One of the most powerful data structure in C.
-  Allows user to include values located in varying areas of memory.
- Allows to dynamically grow and shrink lists
- ![[Pasted image 20260803145800.png]]
	- boxes are called node
		- node contains item and a pointer called ``next``
		``` C
		typedef struct node
		{
			int number;
			struct node *next;
		} node;
		```

- recreation of ``list.c`` with linked list
``` C
// Uses a sort of Insertion Sort Mecchanism

#include <cs50.h>
#include <stdio.h>
#include <stdlib.h>

typedef struct node
{
	int number;
	struct node *next;
} node;

int main(void)
{
	// Memory for numbers
	node *list = NULL
	
	// Build list
	for (int i = 0; i < 3; i++)
	{
		node *n = malloc(sizeof(node));
		if (n == NULL)
		{
			return 1;
		}
		n->number = get_int("Number: ");
		n->next = NULL;
		
		// If list is empty
		if (list == NULL)
		{
			list = n;
		}
		
		// If number belongs at beginning of list
		else if (n->number < list->number)
		{
			n->next = list;
			list = n;
		}
		
		// If number belongs later in list
		else
		{
			// Iterate over nodes in list
			for (node *ptr = list; ptr != NULL; ptr = ptr->next)
			{
				// If at end of list
				if (ptr->next == NULL)
				{
					// Append node
					ptr->next = n;
					break;
				}
				
				if (n->number < ptr->next->number
				{
					n->next = ptr->next;
					ptr->next = n;
					break;
				}
			}
		}
	}
	
	// Print numbers 
	node *ptr = list;
	while (ptr != NULL)
	{
		printf("%i\n", ptr->number);
		ptr = ptr->next;
	}
	// Free memory
	unload(list);
	return 0; 
}	

void unload(node *list)
{	
	node *ptr = list;
	while (ptr != NULL)
	{
		node *next = ptr->next;
		free(ptr);
		ptr = next;
	}
	return 0;
}
```

## Trees 
---
- non-linear hiearchial data structure composed of nodes, and connected directed lines called edges
- root is top node of the tree
- child / parent - if Node A points down to Node B, Node A is parent and Node B is child
- leaf node - very bottom no children (points to NULL)

``` C
bool search(node *tree, int number)
{
    if (tree == NULL)
    {
        return false;
    }
    else if (number < tree->number)
    {
        return search(tree->left, number);
    }
    else if (number > tree->number)
    {
        return search(tree->right, number);
    }
    else if (number == tree->number)
    {
        return true;
    }
}
```

## Hashing and Hash Tables
---
-  goal is to get *O*(1) 
-  Hashing is taking a value and outputting a value that becomes a shortcut to it later
	- ex. apple = 1, berry = 
- hash function is an algorithm that simplifies a value to something small and predictable
	- takes item to add to hash table, returns integer (representing array index, where item should be placed)
- hash table is a combination or arrays and linked lists.
	- in code, hash tables are arrays of pointers to nodes
- example of a hash table:
![[Pasted image 20260803172615.png]]
- can be represented in code as follows
``` C
#include <ctype.h>

unsigned int hash(const chat *word)
{
	return toupper(word[0] - "A");
}
```
- still uses *O*(n)

## Tries
---
- trees of arrays
- always searchable in constant time
- cons: uses alot of memory 
	- ex. 26 * 4 = 104
- finally uses *O*(1)