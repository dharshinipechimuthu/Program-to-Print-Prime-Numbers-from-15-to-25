# Program-to-Print-Prime-Numbers-from-15-to-25
# Program to print prime numbers from 15 to 25

# Loop through the range
for num in range(15, 26):  # 26 is exclusive
    if num > 1:
        # Check for factors
        for i in range(2, int(num**0.5) + 1):
            if num % i == 0:
                break
        else:
            print(num, end=" ")

Output:
17 19 23
