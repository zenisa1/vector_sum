#define _CRT_SECURE_NO_WARNINGS
#include <stdio.h>
#include <string.h>
struct vector {
	float x;
	float y;
};

struct vector get_vector_sum(struct vector a, struct vector b) {
	struct vector result;
	result.x = a.x + b.x;
	result.y = a.y + b.y;
	return result;
}

int main(void) {

	struct vector a = { 2.0, 3.0 };
	struct vector b = { 5.0, 6.0 };

	struct vector get_vetcor_sum(struct vector a, struct vector b);
	printf("벡터의 합은 (%f, %f)입니다.\n", get_vector_sum(a, b).x, get_vector_sum(a, b).y);

	return 0;
}
