# -Paz-_Fahrenheit_
#include <stdio.h>

int main() {
    // declare variables
    float fahrenheit;
    float celcius;

    // input: fahrenheit
    printf("Write if the Fahrenheit value: ");
    scanf("%f", &fahrenheit);
    printf("Fahrenheit = %.2f\n", fahrenheit);

    // process: celcius
    celcius = (fahrenheit - 32.0) * 5.0 / 9.0;

    // output: celcius
    printf("Celcius = %.2f\n", celcius);

    return 0;
}
