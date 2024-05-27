# spiring-project


OAuth는 제3의 서비스에 계정 관리를 맡기는 방식이다. 



def ctof(x):
    return (x * 9.0 / 5.0) + 32

def ftoc(x):
    return (x - 32) * 5.0 / 9.0

while True:
    cmd = input("메뉴: 1=섭씨->화씨, 2=화씨->섭씨, q=종료 >> ")

    if cmd == "1":
        temp = int(input(("섭씨 온도를 입력하세요: ")))
        print("{:.2f}도는 화씨로 {:.2f}도입니다.".format(temp,(ctof(temp))))

    elif cmd == "2":
        temp = int(input("화씨 온도를 입력하세요: "))
        print("{:.2f}도는 섭씨로 {:.2f}도입니다.".format(temp,(ftoc(temp))))

    else:
        print("프로그램을 종료합니다.")
        break



