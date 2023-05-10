import random

# List of quotes
quotes = [
    "Life is like a box of chocolates, you never know what you're gonna get.",
    "In three words I can sum up everything I've learned about life: it goes on.",
    "You only live once, but if you do it right, once is enough.",
    "The only way to do great work is to love what you do.",
    "Believe you can and you're halfway there."
]

# Generate a random index for the quotes list
random_index = random.randint(0, len(quotes) - 1)

# Print the randomly selected quote
print("Here's a random quote for you:\n")
print(quotes[random_index])
