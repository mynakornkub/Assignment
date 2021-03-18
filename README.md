# Assignment
Python

lst = [] 

n = int(input("ใส่จำนวนเอเลี่ยน : ")) 
print("กรอกชื่อเอเลี่ยน")
for i in range(0, n): 
	ele = input()
  
	lst.append(ele) 
	
print(lst) 

m = int(input("กรอกจำนวนรอบที่่เอเลี่ยนจะได้รับอาหาร :" ))


for i in range(0, m):
    f = lst[:]+lst[0:1]+lst[0:1]
    del(f[0])
    lst[:]=f[:]
    print(lst);


print("ตอบ : ",lst[-1])
