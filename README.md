def is_palindrome(s):
    s = s.lower().replace(" ", "")
    return s == s[::-1]

word = input("Enter a word to check palindrome: ")
if is_palindrome(word):
    print("f is a palindrome.")
else:
    print("f is not a palindrome.")
