# hello-world
# my first repository
while True :
   
    print("我是人工智能，我心里想着一个数，你能猜中吗？退出请输入quit")
    x = input('请输入一个整数：')
    
    if x == 'quit':
        print("游戏结束")
        break
    else:
        x = eval(x)
        
        a = random.randint(1,10)
        while x != a :

            if x < a:
                print("小了")
                x = eval(input('请输入一个整数：'))
            else:
                print("大了")
                x = eval(input('请输入一个整数：'))
        print("恭喜你猜对了！")
