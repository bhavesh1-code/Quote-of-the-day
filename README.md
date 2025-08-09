# Quote-of-the-day
A Simple Python CLI Tool for your daily  dose of  motivation
import random

quotes = [
    "Believe in yourself.",
    "Stay positive, work hard, make it happen.",
    "Success is not final, failure is not fatal: It is the courage to continue that counts.",
    "Dream big and dare to fail.",
    "Every moment is a fresh beginning."
]

def show_quote():
    print("\n💡 Quote of the Day:")
    print(random.choice(quotes))

if __name__ == "__main__":
    show_quote()
