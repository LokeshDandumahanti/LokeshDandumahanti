num = 8
factorial = 1
for i in range (1,num+1):
  factorial = factorial*i

print(factorial)

print(8*7*6*5*4*3*2*1)

baby = "rockstar"
print(type(baby))

baby =999
print(type(baby))

bro = 6
if bro % 2 == 0:
    print("even")
else:
    print("odd")


a = ("Python laboratory")
b = a.split()
print(b)
c = b.pop()
d = b.pop()
e = c[0:2]
print(e)

number = 323
num_str = str(number)
num_dig = len(num_str)
armstrong_sum = sum(int(digit)**num_dig for digit in num_str)
if armstrong_sum == number:
  print("yes")
else:
  print("no")


word = "Malayalam"

doc = reversed(cod)
if list(cod) == list(doc):
    print("yes")
