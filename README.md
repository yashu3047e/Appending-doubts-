# Appending-doubts-

# Step 1: Create an empty list to store numbers
numbers = []


# Step 2: Take user input to fill the list with numbers
n = int(input("Enter the number of elements you want in the list: "))
for i in range(n):
    num = float(input(f"Enter number {i + 1}: "))
    numbers.append(num)

# Step 3: Find and remove the largest number in the list
largest_number = max(numbers)  # Find the largest number
numbers.remove(largest_number)  # Remove the largest number from the list

# Step 4: Display the largest number and the updated list
print(f"The largest number removed from the list is: {largest_number}")

print(f"The updated list after removing the largest number is : ", ' '.join({numbers}))


VERIFY BETWEEN THESE TWO


# Why this is not possible if the above code is possible 

# Program to print the words starting with an alphabet in a user-entered string

# Input the string from the user
user_string = input("Enter a string: ")

# Split the string into individual words
words = user_string.split()

# Initialize a list to store words that start with an alphabet
words_starting_with_alphabet = []

# Loop through each word in the list
for word in words:
    # Check if the first character of the word is an alphabet
    if word[0].isalpha():
        words_starting_with_alphabet.append(word)

# Output the words that start with an alphabet
print("Words starting with an alphabet are:", ' '.join(words_starting_with_alphabet))

