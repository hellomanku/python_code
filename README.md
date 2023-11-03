def Add(a , b ):

    print( a + b )


def Sub (a , b ):
    print(a - b)

while True:


    choice = int(input("press 1 for add 2 for sub and 3 for exit"))

    if choice == 1 :
      Add(int(input()),int(input()))

    elif choice == 2 :
       Sub(int(input()),int(input()))

    elif choice == 3 :
        break

    else:

        print("wrong choice...")




