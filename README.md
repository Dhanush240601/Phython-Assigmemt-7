# Phython-Assigmemt-7 


[26/06, 8:44 pm]  n=int(input("enter a number"))
sum=0
i=0
while(i<=n):
	sum=sum+i
	i=i+1
print("sum is",sum)
[26/06, 8:45 pm] n=int(input("enter a number"))
count=0
while(n>0):
	count=count+1
	n=n//10
print("no.of digits in given num is",count)
[26/06, 8:45 pm]  n=(1,2,3,4,5,6,7,8,9,10)
odd=0
even=0
for x in n:
	if x%2:
		odd=odd+1
	else:
		even=even+1
print("odd numbers",odd)
print("even numbers",even)
[26/06, 8:46 pm]  n=int(input("enter a number"))
temp=n
rev=0
while(n>0):
	dig=n%10
	rev=rev*10+dig
	n=n//10
if(temp==rev):
		print("number is palindrome")
else:
		print("number is not a palindrome")
[26/06, 8:46 pm] n=int(input("enter n"))
sum=0
for i in range(1,n):
	if(n%i==0):
		sum=sum+i
if(sum==n):
	print("perfect number")
else:
	print("Not a perfect number")
[26/06, 8:47 pm]  for x in range(6):
	if(x==3 or x==6):
		continue
	print(x)
[26/06, 8:47 pm] for i in range(1,10):
	if(i%2!=0):
		print(i)
[26/06, 8:48 pm]  n=int(input("enter the value of n:"))
rev=0
while (n>0):
	r=n%10
	rev=(rev*10)+r
	n=n//10	
print("reverse of a number is",rev)
[26/06, 8:48 pm]  a=(1,2,3,4,5)
for i in a:
	print(i**2)
[26/06, 8:49 pm]  n=5
sum=0
avg=0
for num in range(0,n+1,1):
	sum=sum+num
	avg=sum/n
print("sum is",sum)
print("avg is",avg)
[26/06, 8:49 pm]  n=int(input("enter a number"))
for i in range(0,n):
	for j in range(0,n):
		if(i==j):
			print(1)
		else:
			print(0)
