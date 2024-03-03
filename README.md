# factorial
s,e = map(int,input().split())
s=0
for i in range(s,e+1):
  r=1
  for j in range(1,i+1):
    r=r*j
  s=s+r 
print(s)  

  
