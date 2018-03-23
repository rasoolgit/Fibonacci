# Fibonacci
Fibonacci-Series in Python - Code
def Fibbunachi(n):
  a,b=0,1
  #No negative nummbers
  if n<=0:
    print("n musst be a positive nummber !!")
  #doing the algorithm
  else:
   
   while (a+b) <=n:
    
    #IF  the Sum of a and b if is grether than n Programm will doNothing more
    if a == 0:          #CASE
      print(a)      #OF
      print(b)      #THE
      print(b+a)     #FIRST TWO NUMMBERS
      a = 1           #PASSING THROW 1+0 TO 1+1 and ON
    elif a+b<=n:      
      a=a+b  
      print(a)
    if b+a<=n:
      b=a+b
      print(b)
      
#Fibbunachi(144)  calling the method     
      
 
#Getting USER_INPUT
while True:
  try:
    num = int(input("INPUT YOUR END VALUE OF SERIES: "))
    break
  except Exception:
    print ("Please enter a valid  positive Integer Value")
Fibbunachi(num)

   
