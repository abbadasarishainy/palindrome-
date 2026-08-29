# palindrome-
palindrome 
num = input("Enter a number: ")

reverse = ""

for i in range(len(num) - 1, -1, -1):
    reverse = reverse + num[i]

if num == reverse:
    print("Palindrome")
else:
    print("Not Palindrome")