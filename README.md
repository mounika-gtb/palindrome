# palindrome
num=int(input())
sum=0
p=num
while num>0:
   r=num%10
   sum=sum*10+r
   num=num//10
if sum==p:
   print("palindrome")
else:
   print("not a palindrome")
   
   

