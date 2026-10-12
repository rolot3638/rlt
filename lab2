#include <stdio.h>
#include <math.h>

void task17()
{
	printf("Task: 17\n");
	printf("|ln((y - sqrt(|x|)) * (x - y / (x + x^2 / 4)))|");

	double x = 0, y = 0, z = 0;

	printf("\n\nInput X:");
	scanf("%lf", &x);

	printf("Input Y:");
	scanf("%lf", &y);

	if (x + x * x / 4 == 0)
	{
		printf("No solutions at X = %g, Y = %g", x, y);
	}
	else if ((y - sqrt(fabs(x))) * (x - y / (x + x * x / 4)) <= 0)
	{
		printf("No solutions at X = %g, Y = %g", x, y);
	}
	else
	{
		z = fabs(log((y - sqrt(fabs(x))) * (x - y / (x + x * x / 4))));
		printf("Z(%g, %g) = %g", x, y, z);
	}

	printf("\n\n");
}

void task19()
{
	printf("Task: 19\n");
	printf("(1 + sin(sqrt(x + 1))) / cos(12y - 4)");

	double x = 0, y = 0, z = 0;

	printf("\n\nInput X:");
	scanf("%lf", &x);

	printf("Input Y:");
	scanf("%lf", &y);

	if (x + 1 < 0)
	{
		printf("No solutions at X = %g, Y = %g", x, y);
	}
	else if (cos(12 * y - 4) == 0)
	{
		printf("No solutions at X = %g, Y = %g", x, y);
	}
	else
	{
		z = (1 + sin(sqrt(x + 1))) / cos(12 * y - 4);
		printf("Z(%g, %g) = %g", x, y, z);
	}

	printf("\n\n");
}

void task20()
{
	printf("Task: 20\n");
	printf("2ctg(3x) - ln(cos(x)) / ln(1 + x^2)");

	double x = 0, z = 0;

	printf("\n\nInput X:");
	scanf("%lf", &x);

	if (sin(3 * x) == 0)
	{
		printf("No solutions at X = %g", x);
	}
	else if (cos(x) <= 0)
	{
		printf("No solutions at X = %g", x);
	}
	else if (log(1 + x * x) == 0)
	{
		printf("No solutions at X = %g", x);
	}
	else
	{
		z = 2 / tan(3 * x) - log(cos(x)) / log(1 + x * x);
		printf("Z(%g) = %g", x, z);
	}

	printf("\n\n");
}

void task21()
{
	printf("Task: 21\n");
	printf("e^x - x - 2 + (1 + x)^x");

	double x = 0, z = 0;

	printf("\n\nInput X:");
	scanf("%lf", &x);

	if (1 + x <= 0)
	{
		printf("No solutions at X = %g", x);
	}
	else
	{
		z = exp(x) - x - 2 + pow(1 + x, x);
		printf("Z(%g) = %g", x, z);
	}

	printf("\n\n");
}

void task22()
{
	printf("Task: 22\n");
	printf("x ln(x) + y / (cos(x) - x / 3)");

	double x = 0, y = 0, z = 0;

	printf("\n\nInput X:");
	scanf("%lf", &x);

	printf("Input Y:");
	scanf("%lf", &y);

	if (x <= 0)
	{
		printf("No solutions at X = %g, Y = %g", x, y);
	}
	else if (cos(x) - x / 3 == 0)
	{
		printf("No solutions at X = %g, Y = %g", x, y);
	}
	else
	{
		z = x * log(x) + y / (cos(x) - x / 3);
		printf("Z(%g, %g) = %g", x, y, z);
	}

	printf("\n\n");
}

int main()
{
	int n;

	printf("Input task number (17, 19, 20, 21, 22): ");
	scanf("%d", &n);

	switch (n)
	{
	case 17:
		task17();
		break;
	case 19:
		task19();
		break;
	case 20:
		task20();
		break;
	case 21:
		task21();
		break;
	case 22:
		task22();
		break;
	default:
		printf("Wrong task number");
	}

	return 0;
}
