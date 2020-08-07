def Insert():
    n=int(input("Enter the number of terms - "))
    for i in range(n):
        key=input("Key - ")
        value=eval(input("Value - "))
        hashtable[key]=value

def delete():
    if(len(hashtable)>=1):
        l=int(input("1. Clear Data  2. Specific Term\n"))
        if(l==1):
              hashtable.clear()
        elif(l==2):
            key=input("Enter the term to delete - ")
            if(key in hashtable):
                del hashtable[key]
            else:
                print("Invalid Entry")
        else:
            print("Invalid Entry")
    else:
        print("Hash Table is empty")
        
def update():
    key=input("Key - ")
    value=eval(input("Value - "))
    hashtable[key]=value
    
def display():
    if(len(hashtable)>=1):
        print(hashtable)
    else:
        print("Hash Table is empty")

def Operations():
    n=int(input("1. Insert  2. Delete   3. Update   4. Print\n"))
    if(n==1):
        Insert()
    elif(n==2):
        delete()
    elif(n==3):
        update()
    elif(n==4):
        display()
    else:
        print("Invalid Entry")

print("Hashtable")
hashtable=dict()
Operations()
while True:
    conti=input("Continue Y/N - ")
    if(conti=='y' or conti=="Y"):
        Operations()
    elif(conti=='n' or conti=="N"):
        break
    else:
        print("Invalid Entry")
