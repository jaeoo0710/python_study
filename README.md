# 2023-07-26

print(i,and=" ") 세로말고 가로로 출력
a=int(input())
b=int(input())
print(b,a)

a=input("당신의 나이는 몇살입니까?")
print("당신의 나이는",a,"살이군요")

a=input()
print(a*5)

for i in range(10):
    print("python program")

a=int(input())
for i in range(a):
    print("c언어 프로그래밍")

i=0
while i<=10:
    print("python")
    i=i+1

a=int(input())
i=0
while i<=a:
    print('python')
    i=i+1

a=int(input("찍고싶은 별의 갯수를 입력해주세요"))
for i in range(1,a+1):
     print("*"*i)

a=int(input("찍고싶은 별의 갯수를 입력해주세요"))
i=0
k=a-1
while  True:
    if(i<=a):
        print("*"*i)
        i=i+1
    else:
        if(k==0):
            break
        print("*"*k)
        k=k-1

a=int(input())
if(a%3==0):     #if(a%2==0)
    print("3의배수")
if(a%3!=0):   #else
    print("3의배수가 아님")
"""
a=1
sum=0
count=0
while(a!=0):
    a=int(input())
    sum+=a
    count=count+1
print("입력된 자료의수 ", count-1)
print("입력된 자료의 합계",sum)
print("입력된 자료의 평균",sum/(count-1))
