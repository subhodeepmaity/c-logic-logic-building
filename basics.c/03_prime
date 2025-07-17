#include <stdio.h>

int main() {
    int num, i, count = 0;

    // Ask the user to enter a number
    printf("Enter a number: ");
    scanf("%d", &num);

    // 0 and 1 are not prime numbers
    if (num <= 1) {
        printf("%d is not a prime number.\n", num);
        return 0;
    }

    // Check how many times the number is divisible
    for (i = 1; i <= num; i++) {
        if (num % i == 0) {
            count++; // Increase count if i divides num completely
        }
    }

    // A prime number has exactly 2 divisors: 1 and itself
    if (count == 2) {
        printf("%d is a prime number.\n", num);
    } else {
        printf("%d is not a prime number.\n", num);
    }

    return 0;
}
