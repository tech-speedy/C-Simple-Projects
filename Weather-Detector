#include <stdio.h>
#include <string.h>

// Function to determine weather based on temperature
void get_weather_status(double temperature) {
    if (temperature <= 0) {
        printf("Weather Status: Freezing! It's below freezing point.\n");
    } else if (temperature > 0 && temperature <= 15) {
        printf("Weather Status: Cold! It's a chilly day.\n");
    } else if (temperature > 15 && temperature <= 25) {
        printf("Weather Status: Mild! It's a pleasant day.\n");
    } else if (temperature > 25 && temperature <= 35) {
        printf("Weather Status: Warm! It's a hot day.\n");
    } else {
        printf("Weather Status: Hot! It's scorching hot outside!\n");
    }
}

// Function to ask for weather condition (sunny, rainy, etc.)
void get_weather_condition(char condition[]) {
    if (strcmp(condition, "sunny") == 0) {
        printf("The weather is sunny. Wear your sunglasses!\n");
    } else if (strcmp(condition, "rainy") == 0) {
        printf("The weather is rainy. Don't forget your umbrella!\n");
    } else if (strcmp(condition, "cloudy") == 0) {
        printf("The weather is cloudy. It might rain later.\n");
    } else if (strcmp(condition, "snowy") == 0) {
        printf("The weather is snowy. Bundle up and stay warm!\n");
    } else {
        printf("The weather condition is unknown.\n");
    }
}

int main() {
    double temperature;
    char condition[20];

    // Asking for temperature input
    printf("Enter the current temperature in Celsius: ");
    scanf("%lf", &temperature);

    // Get the weather status based on temperature
    get_weather_status(temperature);

    // Asking for weather condition input
    printf("\nEnter the weather condition (sunny, rainy, cloudy, snowy): ");
    scanf("%s", condition);

    // Get the weather description based on condition
    get_weather_condition(condition);

    return 0;
}
