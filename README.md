# assignment2-Mandapati
# Manisha Mandapati
###### Fried rice
>Fried rice is a dish of cooked rice that has been **stir-fried** in a wok or a frying pan and is usually mixed with other ingredients such as eggs, vegetables, seafood, or meat. It is often eaten by itself or as an accompaniment to another dish

---
**Steps to create github repository**
1. Create and use a repository
2. Start and manage a new branch
  1. Go to new repository
  2. Click the drop down at the top of the file list that says branch:main.
  3. Type the branch name
3. Make changes to a file and push them to GitHub as commits
4. Open and merge a pull request

- Internet Connection
- Github Account

---
## best places to visit 
These are my favourite places that i would recommend someone to visit
| Location | Spending hours | Expenditure |
| :---: | :---: | :---: |
| Florida | 6 | $1000 |
| Oregon | 10 | $1200 |
| Newyork | 48 | $2000 |

---
# quotes
> “ The purpose of our lives is to be happy.” — *Dalai Lama*

> “ Life is what happens when you're busy making other plans.” — *John Lennon*

> “ Get busy living or get busy dying.” — *Stephen King*

---
> Java is a class-based, object-oriented programming language that is designed to have as few implementation dependencies as possible. It is a general-purpose programming language intended to let application developers write once, run anywhere (WORA),meaning that compiled Java code can run on all platforms that support Java without the need for recompilation.


Source link <https://en.wikipedia.org/wiki/Java_(programming_language)>

```

//sample code to write 100 random ints to a file, 1 per line

import java.io.PrintStream;
import java.io.IOException;
import java.io.File;

import java.util.Random;

public class WriteToFile
{	public static void main(String[] args)
	{	try
		{	PrintStream writer = new PrintStream( new File("randInts.txt"));
			Random r = new Random();
			final int LIMIT = 100;

			for(int i = 0; i < LIMIT; i++)
			{	writer.println( r.nextInt() );
			}
			writer.close();
		}
		catch(IOException e)
		{	System.out.println("An error occured while trying to write to the file");
		}
	}
}

```
code source <https://www.cs.utexas.edu/~scottm/cs307/javacode/codeSamples/WriteToFile.java>


