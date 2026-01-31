import random

words = ['apple", "banana", "grapes", "orange", "mango"]

word = random.choice(words)

guessed = []

attempts = 6

print("Welcome to Hangman Game')

while attempts > 0:

display =

for letter in word:

if letter in guessed:

else

display += letter

display

print("Word", display)

if not in display:

print("Congratulations! You won

break

guess input('Guess a letter")

If guess in guessed:

print("Already guessed")

elif guess in word:

guessed.append(guess)

print("Correct guess!")

else:

attempts -=

print("Wrong guess! Attempts left", attempts)

if attempts 0

print("You lost The word was", word)

↓# First-
Hangman game 

