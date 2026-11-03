#include <math.h>
#include <stdlib.h>
#include <stdio.h>



/**
 * @brief вычисляет а, принимает:
 * @param x первый параметр
 * @param y второй параметр
 * @param z третий параметр
 * @return число а
 */
double geta(const double x, const double y, const double z);

/**
 * @brief вычисляет б, принимает:
 * @param x первый параметр
 * @param y второй параметр
 * @param z третий параметр
 * @return число б
 */
double getb(const double x, const double y, const double z);

/**
 * @brief начало выполнения программы
 * @return если все успешно, 0
 */
int main(void) {
	const double x = -4.8;
	const double y = 17.5;
	const double z = 3.2;
	
	double a = geta(x, y, z);
	double b = getb(x, y, z);
	
	printf("x = %.1lf\n", x);
	printf("y = %.1lf\n", y);
	printf("z = %.1lf\n", z);
	
	printf("a = %.10f\n", a);
	printf("b = %.10f\n", b);
	
	return 0;
}

double geta(const double x, const double y, const double z) {
    return y * z * pow(x, 2) - z / pow(sin(x / z), 2);
}

double getb(const double x, const double y, const double z) {
    return z * exp(-z) * cos((y * x) / z);
}
