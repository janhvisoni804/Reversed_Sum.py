test_case=int(input("enter no of turns "))
i=1
while i<=test_case:
    print("enter two numbers")
    a,b=input().split()
    a=int(a[::-1])
    b=int(b[::-1])
    add=a+b
    final_ans=int(str(add)[::-1])
    print("final reversed sum is ",final_ans)
    i=i+1
