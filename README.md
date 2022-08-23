# List-in-Python 
marks = [95,96,97,98,99]

print(marks)

print(marks[0:2])
print(marks[3])
# for loop in list
for score in marks:
    print(score) 
# while loop in list 
i=0
while i<len(marks):
    print(marks[i])
    i=i+1

 # operation in list 
 # 1. 
marks.append(100)   
print(marks)

#2.
print(len(marks))
#3.
marks.insert(2,102)
print(marks)

print(marks[0:2])
print(marks[3])
