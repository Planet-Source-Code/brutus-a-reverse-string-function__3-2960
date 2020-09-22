<div align="center">

## A reverse string function\.


</div>

### Description

This is a simple function that I wrote to reverse a string. I'm a newbie to this language so please have a look and give feedback.
 
### More Info
 
A string

A reversed string


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Brutus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/brutus.md)
**Level**          |Beginner
**User Rating**    |4.0 (24 globes from 6 users)
**Compatibility**  |Microsoft Visual C\+\+
**Category**       |[Strings](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/strings__3-26.md)
**World**          |[C / C\+\+](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/c-c.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/brutus-a-reverse-string-function__3-2960/archive/master.zip)





### Source Code

```
#include <iostream>
using namespace std;
int main()
{
	const int max = 80; //size of array
	char str[max]; //the array of characters
	int count = 0;
	int i = 0;
	cout << "Enter a string:\n"; //Prompt user to enter a string
	cin.getline(str,max,'\n'); //Read in the string
	while(str[count] != '\0')
		count++; //count the characters in the string, until a char 13 is found
	for(i = count; i >=0; i--) /loop from length of string to 0
	{
		cout << str[i]; /Display the reversed string
	}
 return 0;
}
```

