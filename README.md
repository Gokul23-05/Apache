def is_palindrome(s):
    s = s.lower().replace(" ", "")
    return s == s[::-1]

word = input("Enter a word to check palindrome: ")
if is_palindrome(word):
    print(f"'{word}' is a palindrome.")
else:
    print(f"'{word}' is not a palindrome.")
