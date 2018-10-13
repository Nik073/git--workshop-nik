a=int(input())
l=n//2-1
r=n//2+1
for i in range(0,n):
	if(i<n/2):
		l=l-1
		r=r+1
	else:
		l=l+1
		r=r-1
	for j in range(0,n):
		if(j==l or j==r):
			print("*",end="")
		else:
			print(" ",end="")
	print()
	
	
