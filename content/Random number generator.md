---
{"publish":true,"created":"2025-06-24T10:47:40.000-04:00","modified":"2025-08-17T16:23:43.119-04:00","tags":["Coding/python","project","project/learningtocode"],"cssclasses":""}
---

#Coding/python 

[[Random Module]]
[[if statement python]] 

The lines that are comments are an alternative way to do this
	We could define a [[Functions in coding\|function]] that generates a random number
```python
import random

#def generate_random_number():
 #   """Generates a random number between 1 and 100."""
  #  return random.randint(1, 100)

def main():
    while True:
        user_input = input("Do you want to generate a random number? (yes/no): ").strip().lower() #.strip() removes leading and trailing whitespace, .lower() converts to lowercase
        '''
        This function prompts the user to generate a random number.
        If the user inputs 'yes', it generates a random number between 1 and 100,
        checks if it is greater than 50, and prints the result.
        If the user inputs 'no', it exits the program.
        If the user inputs anything else, it prompts for valid input again.
        '''
        if user_input == 'yes':
            print("Welcome to the Random Number Generator!")
            #random_number = generate_random_number()
            random_number = random.randint(1, 100)
            print(f"Your random number is: {random_number}")
            if random_number > 50:
                print("The random number is greater than 50.")
            else:
                print("The random number is less than 50.")
        elif user_input == 'no':
            print("Exiting the random number generator.")
            return
        else:
            print("Invalid input. Please enter 'yes' or 'no'.")
    """Main function to run the random number generator."""




if __name__ == "__main__":
    main()


```