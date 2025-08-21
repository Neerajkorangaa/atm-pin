attempt=3
stored_pin=1234
while chances>0:
    pin=int(input("enter pin"))
    if pin==stored_pin:
        print("access granted")
        break
    else:
        attempt-=1
        if attempt>0:
              print("wrong pin")
        else:
             print("account locked")

