# calculator
program of simple calculator

// Program To Create Simple Calculator

#include<stdio.h>
#include<math.h>

int sum_of_numbers(int *a, int p)
{
	int i;
	p+=a[i];

	return p;
}

int difference_of_numbers(int *b, int q)
{
	int j;
	q-=b[j];

	return q;
}

int product_of_numbers(int *c, int r)
{
	int k;
	for(int x=0;x<sizeof(c);x++)
	{
		r=(c[x])(c[x+1]);
	}
	return r;
}

int division_of_numbers(int *d, int s)
{
	int l;
	for(y=0;y<sizeof(d);y++)
	{
		s=(d[y])/(d[y+1]);
	}
	return s;
}


int main()
{
	result1=sum_of_numbers(int, int);
	result2=difference_of_numbers(int, int);
	result3=product_of_numbers(int, int);
	result4=division_of_numbers(int, int);

	return 0;
}
