print("im Ahmed and lerning python!")
name = input("your username: ")
print("welcome " + name + " in python world")

while True:
    print("welcome to rateings grades")
    score = int(input("write your grades to 100 (or write -1 to exit): "))
    
    if score == -1:
        print("good bye " + name + "!")
        break
        
    if score >= 80:
        print("goodjob (A)")
    elif score >= 75:
        print("nice (B)")
    elif score >= 70:
        print("your fine (C)")
    else:
        print("you need to be better goodluck (D)")
