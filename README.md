num=int(input("Enter the range:"))
for n in range(1,num):
  for i in range(2,n):
    if(n%i==0):
      break
  else:
    print(n)  



OUTPUT:

Enter the range:12
1
2
3
5
7
11
