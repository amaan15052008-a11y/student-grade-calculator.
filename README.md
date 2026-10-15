# student-grade-calculator.

# STUDENT GRADE CALCULATOR

name = "Amaan"
maths = 85
physics = 75
programming = 90

total = maths + physics + programming
percentage = (total / 300) * 100

if percentage >= 90:
    grade = "A+"
elif percentage >= 80:
    grade = "A"
elif percentage >= 70:
    grade = "B"
elif percentage >= 60:
    grade = "C"
elif percentage >= 40:
    grade = "D"
else:
    grade = "F"

print("=== STUDENT RESULT ===")
print("Name:", name)
print("Maths:", maths)
print("Physics:", physics)
print("Programming:", programming)
print("Total Marks:", total, "/ 300")
print("Percentage:", round(percentage, 2), "%")
print("Grade:", grade)
