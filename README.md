# Digits
You are given a number A which contains only digits 0's and 1's. Your task is to make all digits same by just flipping one digit (i.e. 0 to 1 or 1 to 0 ) only. If it is possible to make all the  digits same by just flipping one digit then print 'YES' else print 'NO'.

a=input()

ones=0
zeros=0
for i in a:
    if(i=='1'):
        ones=ones+1 
    elif(i=='0'):
        zeros=zeros+1 
if(ones==1 or zeros==1):
    print("YES",end="")
else:
    print("NO",end="")
