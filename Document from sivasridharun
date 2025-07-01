import random

def guessing_game():
    number = random.randint(1, 100)
    attempts = 0

    while True:
        try:
            guess = int(input("Guess the number (1–100): "))
            attempts += 1
            if guess < number:
                print("Too low.")
            elif guess > number:
                print("Too high.")
            else:
                print(f"Correct! Attempts: {attempts}")
                break
        except ValueError:
            print("Enter a valid number.")

guessing_game()
