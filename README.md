
godina = int(input("Koju godinu želite da proverite? "))

if godina % 4 == 0:
    if godina % 100 == 0:
        if godina % 400 == 0:
            print("Prestupna godina.")
        else:
            print("Nije prestupna godina.")
    else:
        print("Prestupna godina.")
else:
    print("Nije prestupna godina.")
