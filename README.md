a='This is ZOHO and ZOHO is good'
z=a.split()
x=[]
x1=' '
for i in z:
    if i not in x:
        x+=[i]
for j in x:
    x1+=j 
    x1+=' '
print(x1)
