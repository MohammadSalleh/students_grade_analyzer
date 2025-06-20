def Disply_studnet_summary(students):
    names = []
    grades = []
    for i in students:
        name = input("Inter the name of the student:")
        grade = get_avg_grade("Inter the grade of: (name)")
        names.append(name)
        grades.append(grade)
    result names, grades

def get_avg_grade (students):
    total = 0
    for y in students:
        total = total + students
        average = total / len (students)
        return average
    
def get_highest_grade(student):
    highest = student 
    for i in student:
        if student > highest :
         return highest

def count_passed(names):
    count = 0
    for x in names :
        if names >= 60:
            count += 1
    return count
