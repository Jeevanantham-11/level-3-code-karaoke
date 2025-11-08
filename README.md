
<img width="5400" height="2383" alt="Code Karaoke-min" src="https://github.com/user-attachments/assets/cf9296ba-8410-4592-8df0-bac4afd7fdba" />
#TEAM NAME:VIBECODERS

# Level-3-code-karaoke
Level 3 questions for code karaoke event, there are 2 scenario based  fork and upload in git hub 

# 1st Question :
1.You are building a billing system for a small café.
The café sells:
•	Coffee → ₹60
•	Sandwich → ₹120
•	Cake → ₹80
You need to write a Python program that:
1.	Asks the user what they want to order.
2.	Asks how many of that item they want.
3.	Calculates and displays the total bill.

# Code:
```
prices = {"coffee":60,"sandwich":120,"cake":80}
item=input("What would you like to order (coffee/sandwich/cake)?").lower()
if item in prices:
    qty=int(input(f"How many {item}s do you want?"))
    total=prices[item]*qty
    print(f"Your total bill is Rs.{total}")
else:
    print("Sorry,item not available.")
```

# OUTPUT:
```
What would you like to order (coffee/sandwich/cake)?coffee
How many coffees do you want?3
Your total bill is Rs.180
```
PICTURE:
<img width="1273" height="298" alt="{213762D2-7DB9-4776-8F5D-0C62DA9C4C75}" src="https://github.com/user-attachments/assets/ecf4ab4a-7762-49fe-9bc4-fefc67df61bc" />

# Question 2:
2. You’re designing a program for a college portal that evaluates a student’s final grade based on their marks in 3 subjects.
Rules:
•	If the average is 90 or above → Grade A+
•	If the average is 75–89 → Grade A
•	If the average is 60–74 → Grade B
•	If the average is 40–59 → Grade C
•	Below 40 → Fail
The program should:
1.	Take marks for 3 subjects from the user
2.	Calculate the average
3.	Print the average and the grade
________________________________________
# Example Input / Output:
Enter mark for Subject 1: 85
Enter mark for Subject 2: 78
Enter mark for Subject 3: 90
Average = 84.33
Grade = A





# Code:
```
m1=float(input("Enter mark for Subject1: "))
m2=float(input("Enter mark for Subject2: "))
m3=float(input("Enter mark for Subject3: "))

avg=(m1+m2+m3)/3
print(f"Average = {avg:2f}")

if avg>=90:
    grade ="A+"
elif avg>=75:
    grade ="A"
elif avg>=60:
    grade ="B"
elif avg>=40:
    grade = "C"
else:
    grade="Fail"

print(f"Grade = {grade}")
```

# OUTPUT:
```
Enter mark for Subject1: 98
Enter mark for Subject2: 99
Enter mark for Subject3: 90
Average = 95.666667
Grade = A+
```
PICTURE:
<img width="830" height="639" alt="{42193A5B-8151-491B-BA3B-B06D0A2282DB}" src="https://github.com/user-attachments/assets/1bc9a18e-6ace-4b1d-a953-f28da2254950" />
