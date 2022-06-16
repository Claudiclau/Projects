# Primero Python first project
def CalcTotal (q1,q2,q3,q4,q5):
  average= (q1+q2+q3+q4+q5)/5
  return average

def PrintTitle():
  print("GradeAvg")
  print("=======\n")
  
PrintTitle()
name=input ("Enter user name ==>")
q1=input ("Enter q1")
q2=input ("Enter q2")
q3=input ("Enter q3")
q4=input ("Enter q4")
q5=input ("Enter q5")
if (avg>90):
    return "A"
if (avg>80):
    return "B"
if (avg>70):
    return "C"
if (avg>60):
    return "D"
else (avg<60):
    return "F"
  
print(name+"your grade is ==> " +str(p))
