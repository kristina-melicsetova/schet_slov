# schet_slov
b = input()
a = 0
c = 0
while c < len(b):
    for i in b:
        c+=1
        a+=1
        if i ==' ':
            a-=1 #число букв в одном слове
            print(a)
    print(a)
