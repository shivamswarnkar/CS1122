"This is a python code file."

def getUserID():
    ID = raw_input("Enter your ID here: ")
    return ID

def CheckID(ID):
    if ID in DataBase:
       return 1

    else:
       return -1

def LetEnter(code):
    if code == 1 :

       Let_User_Do_Work(ID)

    else: 
        print("you are not allowed to enter here!")


def main():

    ID = getUserID()
    code = CheckID(ID)
    LetEnter(code)

main()
