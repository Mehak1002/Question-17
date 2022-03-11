# Question-17
def check_duplicates():
    l = []
    l2 = []
    n = int(input("Please enter the number of elements you wish to add to the list  :  "))
    for i in range(n):
        x = int(input("Enter element  :"))
        l.append(x)
    print("Your entered list is : ", l )

    for i in range(n):
        if l[i] not in l2:
            l2.append(i)
        else:
            print("element repeated is : ", i)

