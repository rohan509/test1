s=input()
l=list(s.strip())
d=[]
le=[]
for i in l:
    if i not in d:
        d.append(i)
    else:
        d=[]
        d.append(i)
    le.append(len(d))
print(max(le)-1)
        
