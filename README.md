# code-for-multiplication-table-using-loops
# multiplication table using for loops and while loops
n = int(input("Multiplication Table: "))
for i in range(1 ,11):
    print(f"{n} X {i} = {n * i}")

n = int(input("Multiplication table: "))
i = 0
while i < 10:
    i +=1
    print(f"{n} X {i} = {n * i}")
