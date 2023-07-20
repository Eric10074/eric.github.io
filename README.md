# eric.github.io
print("歡迎來到猜數字遊戲")
i=0
玩=input("您是否要要玩？(Y)要 (N)否：").upper()
if 玩=="Y":
    import random
    num=random.randint(1,100)
    while i<10:
        i+=1
        數字=int(input("請從1到100猜一個數字:"))
        if 數字>num:
            print("小一點")
        elif 數字==num:
            print("遊戲結束,你贏了!")
            break
        else:
            print("大一點")
elif 玩=="N":
    print("下次再來玩吧,掰掰")
else:
    print("下次再來玩吧,掰掰")
