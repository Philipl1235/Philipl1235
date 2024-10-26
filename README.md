import random
secret_number = random.randint(1, 100)
guess = int(input("Guess a number between 1 and 100: "))
if guess > secret_number:
  print("Too high")
elif guess < secret_number:
  print("Too low")
else:
  print("Correct! You guessed it!")
<!---
Philipl1235/Philipl1235 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
