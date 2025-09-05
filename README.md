# Programming Fundamentals Fall 2025.
** Is it Bold** *and italic*
~~is it bold~~ is it right?
, Code block

# Task List
- [ ] Use GitHub Branching and Commit a File
- [ ] Write a C Program with Variables and Input
- [ ] Demonstrate Escape Sequences in C
- [x] Write a C Program to Calculate Age

``` C program for age and height
#include <stdio.h>
#include <conio.h>
int main() {
	int age;
	float height;
	printf("Enter Your Age");
	scanf("%d", &age );
	printf("Enter your Height");
	scanf("%f", &height );
    printf("Your age is %d", &age);
    printf("Your height is %f", &height);
    return 0;
}
