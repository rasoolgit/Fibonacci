# Fibonacci
Fibonacci-Series in Python - Code




def Fibbunachi(n):
  a,b=0,1

  while (a+b<=n) :
    if a==0:
      print (a,)
      print (b,)
      print (b+a)
      a = 1
    if b+a<=n:
      a=a+b  
   # a=a+b
      print(a,)
    if b+a<=n:
      b=a+b
      print(b,)
    
Fibbunachi(2111485077978050)

