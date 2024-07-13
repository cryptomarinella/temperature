# temperature
# Function to convert Celsius to Fahrenheit
def celsius_to_fahrenheit(celsius):
    return (celsius * 9/5) + 32

# Ask the user for the temperature in Celsius
celsius_temp = float(input("Enter temperature in Celsius: "))

# Convert the temperature to Fahrenheit
fahrenheit_temp = celsius_to_fahrenheit(celsius_temp)

# Print the temperature in Fahrenheit
print(f"{celsius_temp}°C is equal to {fahrenheit_temp}°F.")
