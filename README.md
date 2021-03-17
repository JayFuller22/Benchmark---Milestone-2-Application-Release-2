# Benchmark---Milestone-2-Application-Release-2
Use modular code by using user functions and Use of an array or a pointer
//Use modular code by using user functions 

#include <stdio.h>

int main()
{
	int x = 2 + 3 * 4 / (3 - 2);
	int y = 5 % 2; //modulus operator - remainder (integers)
	printf("%i\n", x);
	return 0;
}


//Use of an array or a pointer 

#include <stdio.h>

int main()
{
	int slices = 20;
	int* p = &slices;

	printf("Slices: %d\n", slices);
	printf("Slices (through pointer): %d\n", *p);

	slices = 21; //direct

	printf("Slices: %d\n", slices);
	printf("Slices (through pointer): %d\n", *p);

	*p = 25; //indirect

	printf("Slices: %d\n", slices);
	printf("Slices (through pointer): %d\n", *p);

	return 0;
}
