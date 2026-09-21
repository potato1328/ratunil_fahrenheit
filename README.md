# ratunil_fahrenheit
#include <stdio.h>

int main() {

    //declare variables
    float fahrenheit;
    float celsius;
    
    //input: fahrenheit
    printf("Write the fahrenheit value: ");
    scanf("%f", &fahrenheit);
    printf("Fahrenheit = %.2f",fahrenheit);
    
    //process: celsius = (fahrenheit - 32) * 5 / 9
    celsius = (fahrenheit - 32) * 5 / 9;
    
    //output: fahrenheit
    printf("Celsius = %.2f",celsius);
    
    return 0;
}