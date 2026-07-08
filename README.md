# myfirstproject
def calculate_grade(marks):
    average = sum(marks) / len(marks)
    if average >= 90:
        grade = "A+"
    elif average >= 75:
        grade = "A"
    elif average >= 60:
        grade = "B"
    elif average >= 40:
        grade = "C"
    else:
        grade = "F"
    return average, grade
marks = [85, 78, 92, 88, 76]
average, grade = calculate_grade(marks)

print("Marks:", marks)
print("Average:", average)
print("Grade:", grade)contains my internship projects and practice code
