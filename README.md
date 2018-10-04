# BullsAndCows

For this exercise, you will only need to concern yourself with the following files:
- Default.aspx
- Default.aspx.cs

You may make any changes required to these files.

The goal is to generate a Secret, comprised of 8 non-repeating digits, which the user must try to guess.

When the user submits a guess, you must print the result in the format "xByC":
- B or Bulls are the number of digits that exist in the Secret and are in the same position in the user's guess
- C or Cows are the number of digits that exist in the Secret but are not in the same position in the user's guess

Default.aspx.cs contains comments that will further explain the rules around the Secret and the user's guesses.

# Example
- Secret: 12345678
- Guess: 19999928
- Result: 2B1C

The Bulls in this example are 1 and 8. The Cow is 2. The 9s are not present in the Secret so do not count towards anything.
