# PYTHON
find marks 


  name=['GILL',"SARA","DHONI"",SHAKSHI","NANDU"]
marks=[70,30,80,38,95]
pos=1
for i in range(5):
    if marks[i]>40:
       print("{}.{} has scored {}%".format (pos,name[1],marks[i]))
       pos=pos+1
