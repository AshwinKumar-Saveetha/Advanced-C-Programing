## Ex. No. 01 Write a C program to find the distance between the two points using structure.
## DATE:07.02.2024
## AIM:
To Write a C program to find the distance between the two points using structure.
## ALGORITHM:
1. **Set Up**: We begin by including some tools we'll need, like being able to read and write from the console and perform mathematical calculations.

2. **Define Points**: We create a way to store points on a graph using a special box (a struct). Each box holds two numbers - one for the position on the horizontal line (x-axis) and another for the vertical line (y-axis).

3. **Main Job**: We start the main part of our program.

4. **Get Points**: We ask the user to tell us where two points are on the graph by giving us their x and y coordinates.

5. **Calculate Distance**: Using a special formula, we figure out how far apart these two points are on the graph.

6. **Show Result**: Finally, we tell the user how far apart these points are by printing out the distance.
## PROGRAM:
```
#include <stdio.h>
#include <stdlib.h>
#include<math.h>
struct point {
    int x, y;
}a,b;
int main()
{
    scanf("%d %d", &a.x, &a.y);
    scanf("%d %d", &b.x, &b.y);
    float n;
    n=sqrt(pow(b.x - a.x, 2) + pow(b.y - a.y, 2) * 1.0);
    printf("Distance between a and b: %f", n);
    return 0;
}
```
## OUTPUT:
![image](https://github.com/AshwinKumar-Saveetha/Advanced-C-Programing/assets/155129814/82f5b296-f786-42b9-b389-6bbc6a461794)

## RESULT:
Thus, a C program has been written to find the distance between the two points using structure.
