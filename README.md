# assignment2-11-02-22
Write a program to Generate Student Result
#Required Fields(sno,name,group,6 subjects,total,avg,grade.
sno=int(input('enter a number:'))
sname=input('enter student name:')
group=input('enter group:')
OB=int(input('online Business marks:'))                     
AS=int(input('Analytical Skills'))
EE=int(input('Environment Education:'))
Acc=int(input('Accounts:'))
java=int(input('java marks:'))
OS=int(input('Operating System:'))
#total for 6 subjects
total=OB+AS+EE+Acc+java+OS
avg=total/6
if avg>91:
    print('O-Grade')
elif avg>81:
    print('A-Grade')
elif avg>71:
    print('B-Grade')
elif avg>61:
    print('C-Grade')
elif avg>51:
    print('D-Grade')
elif avg>=35:
    print('Pass')
else:
    print('Fail')
enter a number:20
enter student name:harisha
enter group:bca
online business marks:84
analytical skills:89
environmental education:78
accounts:93
java marks:82
operating system:76
A-grade
