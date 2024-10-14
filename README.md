#include <stdio.h> ;
#include <math.h>
int main()
{
	float a = 16.01;
	float b = 2.19;
	float x = -8.23;

	float y = sin(a * x) / (b - x) * exp(2 - pow(b-x, 1.0/5));
	printf("Result:%f ", y);
	
	return 0;
}
