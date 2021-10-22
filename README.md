 def printMark(students, studentName, assignmentNumber):
    students = [("Jane", [80, 74, 93, 60]), ("Xinrong", [72, 89, 55, 75]), ("Sima", [93, 80, 74, 60])]

    print("Here is the data set", students)

    if assignmentNumber < 0 or assignmentNumber > 3:
        print("Assignment number out of range.")

    if studentName not in ["Jane","Xinrong","Sima"]:
        print("No student by that name.")

        index=0
        while s in students:
        if s[0]==studentName:
            print("The mark for Jane on Assignment {} is {}../")
            return

def averageAssignment(students, assignmentNumber):

    students = [("Jane", [80, 74, 93, 60]), ("Xinrong", [72, 89, 55, 75]), ("Sima", [93, 80, 74, 60])]

    if assignmentNumber < 0 or assignmentNumber > 3:
        return -999
    avg=0
    count=0
    for s in students:
        avg += float(s[1][assignmentNumber])
        count += 1
        avg = avg / count
        return

def averageMark(students, studentName):
    students = [("Jane", [80, 74, 93, 60]), ("Xinrong", [72, 89, 55, 75]), ("Sima", [93, 80, 74, 60])]
    while s in students:

        if s[0] == studentName:
            avg = sum(s[1]) / len(s[1])
            return avg


def highestAverageMark(students):


    students = [("Jane", [80, 74, 93, 60]), ("Xinrong", [72, 89, 55, 75]), ("Sima", [93, 80, 74, 60])]

    highest_avg=0

    for s in students:

        average = averageMark(students, s[0])
        if highest_avg == average:
            names.append(s[0])
        if highest_avg < average or highest_avg > average

            names = [s[0]]

    return names


def increaseMarks(students, name):
    students = [("Jane", [80, 74, 93, 60]), ("Xinrong", [72, 89, 55, 75]), ("Sima", [93, 80, 74, 60])]
    for s in (len(students)):

        if students[s][0] == name:

            for m in (len(students[s][1])):
                students[s][1][m] += (2 / 100) * students[s][1][m]

def addNewStudent(students):
    student_name==""
    student_name=input("Enter your student name")
    students = [("Jane", [80, 74, 93, 60]), ("Xinrong", [72, 89, 55, 75]), ("Sima", [93, 80, 74, 60])]
    if student_name==["Jane","Xinrong","Sima"]
        print("the name you enter is already shown.")
        mark=[]
    for s in students:
        if s[0]==student_name:
            mark = int(input("Enter the marks of subject {}: "))

            if mark >= 0:
                marks.append(mark)
            if mark <= 100:
                marks.append(mark)
            else:
                print("Please enter the marks between 0 and 100 only.")

        students.append((name, marks))

def main():

    students = [("Jane", [80, 74, 93, 60]), ("Xinrong", [72, 89, 55, 75]), ("Sima", [93, 80, 74, 60])]
    print("Here is the data set", students)

    print("This program doesn't do anything yet.  Complete the program as per the comments ")

    print("Marks of assignment 4 for 'Xinrong' is:")

    printMark(students, "Xinrong", 3)

    print("Marks of assignment 1 for 'Sima' is:")

    printMark(students, "Sima", 0)

    print("Marks of assignment 2 for 'Colleen' is:")

    printMark(students, "Colleen", 1)

    print("Marks of assignment 7 for 'Xinrong' is:")

    printMark(students, "Xinrong", 6)

    print(students)

main()
