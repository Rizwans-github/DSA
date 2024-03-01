![image](https://github.com/Rizwans-github/DSA/assets/141806496/1a28c171-445f-4fb7-b0ee-a2067b35e002)![image](https://github.com/Rizwans-github/DSA/assets/141806496/652ceaf2-d074-4ab9-a7a7-200807ca434a)
![image](https://github.com/Rizwans-github/DSA/assets/141806496/ad744e11-8843-46e8-80a4-20986e3fe3a0)
![image](https://github.com/Rizwans-github/DSA/assets/141806496/ae8631be-3e78-4335-9c9e-bf9f753b1307)
```py
#your code goes here
vowels = ["a", "e", "i", "o", "u"]
str = input()
count = 0
for i in str:
    if i in vowels:
        count += 1
print(count)
```
![image](https://github.com/Rizwans-github/DSA/assets/141806496/e8b47f09-1570-4d19-a22f-8eb89fe94571)
![image](https://github.com/Rizwans-github/DSA/assets/141806496/f02b5ab3-de7d-45a5-8f32-330feda2235b)
![image](https://github.com/Rizwans-github/DSA/assets/141806496/a5632ac6-b62d-4bd9-a864-be8c516db1da)
```py
text = "Amy has 128 dollars, while David has 54 dollars. Amy is going to the zoo. David watches soccer."
old = input()
new = input()
print(text.count(old))
print(text.replace(old, new))
```
![image](https://github.com/Rizwans-github/DSA/assets/141806496/13b1f896-4b1b-4ee3-810e-31cfd8e88697)
```py
#your code goes here
text = input()
letter = input()
freq = (text.count(letter)/ len(text)) * 100
print(int(freq))
```
![image](https://github.com/Rizwans-github/DSA/assets/141806496/5e261ae0-cd8b-4461-b1dc-2f925cc3a2bd)
```py
data = [
  [23, 11, 5, 14],
  [8, 32, 20, 5]
]
color = input()
#your code goes here
males=0
females=0
for i in data[0]:
  males+= i
for i in data[1]:
  females+= i
people = males + females
colors = ["brown", "blue", "green", "black"]
Total = ((data[0][colors.index(color)] + data[1][colors.index(color)])/ people)*100
print(int(Total))
```
```py
Better version from ChatGPT
data = [
    [23, 11, 5, 14],
    [8, 32, 20, 5]
]
color = input()

males = sum(data[0])
females = sum(data[1])
people = males + females

colors = ["brown", "blue", "green", "black"]
color_index = colors.index(color)

total_color = (data[0][color_index] + data[1][color_index]) / people * 100
print(int(total_color))
```

![image](https://github.com/Rizwans-github/DSA/assets/141806496/af40ec03-3a98-4ca3-b748-c5d864069fe7)
```py
prices = [125000, 78000, 110000, 65000, 300000, 250000, 210000, 150000, 165000, 140000, 125000, 85000, 90000, 128000, 230000, 225000, 100000, 300000]
#your code goes here
Total = sum(prices)
houses = len(prices)
avgPrice = Total/houses
count = 0
for i in prices:
    if i > avgPrice:
        count += 1

print(count)
```
![image](https://github.com/Rizwans-github/DSA/assets/141806496/c88ed906-ac4b-48ee-8ac4-12d5fcead09f)

```py
n = int(input())
list = [ n*2**x for x in range(12)]
print(list)
```
![image](https://github.com/Rizwans-github/DSA/assets/141806496/73e1edb2-5bd4-4392-8fac-79514ccd10fc)
```py
text = input()
words = text.split()
totalWords = len(words)
letters =sum(len(word) for word in words)
print(letters/totalWords)
```
![image](https://github.com/Rizwans-github/DSA/assets/141806496/372f4e2e-a8b3-451b-8c07-e07e9ca6056b)
![image](https://github.com/Rizwans-github/DSA/assets/141806496/01727685-8a2f-4429-a2da-6f404294fef8)
![image](https://github.com/Rizwans-github/DSA/assets/141806496/ed0ad49e-33e7-4352-9145-dffbf8fdcdf5)
```py
contacts = {
    "David": ["123-321-88", "david@test.com"],
    "James": ["241-879-093", "james@test.com"],
    "Bob": ["987-004-322", "bob@test.com"],
    "Amy": ["340-999-213", "a@test.com"]
}
#your code goes here
search = input().capitalize()
if search in contacts:
    print(contacts[search][1])
else:
    print("Not found")
```
![image](https://github.com/Rizwans-github/DSA/assets/141806496/c652c233-489c-46e2-9bea-e42e11905066)
![image](https://github.com/Rizwans-github/DSA/assets/141806496/0335d9e8-9863-447a-a67e-f003acff9891)
```py
points = [
    (12, 55),
    (880, 123),
    (64, 64),
    (190, 1024),
    (77, 33),
    (42, 11),
    (0, 90)
]
#your code goes here

val=[]
for i in points:
    x,y = i
    val.append((x**2 + y**2)**0.5)
print(min(val))
```
![image](https://github.com/Rizwans-github/DSA/assets/141806496/9caa5eac-0d29-4db9-a9f8-bc93f857c10e)

```PY
nums = {1, 2, 1, 3, 1, 4, 5, 6}
print(nums)
nums.add(-7)
nums.remove(3)
print(nums)
```
![image](https://github.com/Rizwans-github/DSA/assets/141806496/f0de591e-9f5d-456b-b156-90994e780736)
![image](https://github.com/Rizwans-github/DSA/assets/141806496/be98d10d-1af9-4286-9aca-7d05742529f4)
```py
first = {1, 2, 3, 4, 5, 6}
second = {4, 5, 6, 7, 8, 9}

print(first | second)
print(first & second)
print(first - second) 
print(second - first) #Why this gives the output {8, 9, 7} and not {7, 8, 9} 
                      #found the ans my bad so Sets are unordered collections of unique elements.ordered
print(first ^ second)
```
![image](https://github.com/Rizwans-github/DSA/assets/141806496/dbf3f873-7a4d-4d96-8107-50a5ae14c5e7)
![image](https://github.com/Rizwans-github/DSA/assets/141806496/c386bc0e-02e5-45c7-b074-2ed6f046c4e1)

```py
s1 = input()
s2 = input()

s1_words = {i for i in s1.split()}
s2_words = {i for i in s2.split()}

print(len(s1_words&s2_words))
```
![image](https://github.com/Rizwans-github/DSA/assets/141806496/b004f60a-dcd3-48e6-b764-5c0bc6b7fb4b)
![image](https://github.com/Rizwans-github/DSA/assets/141806496/5932f515-d1bd-4e4a-a5f5-01cf77f11384)
![image](https://github.com/Rizwans-github/DSA/assets/141806496/f95d2341-8dd1-4204-84ec-3c05a20d554f)

```py
data = {
    "100-90": 25, "42-01": 48, "55-09": 12, "128-64": 71, "002-22": 18, "321-54": 19, "097-32": 33, "065-135": 64, "99-043": 80, "111-99": 11, "123-019": 5, "109-890": 72, "132-123": 27, "32-908": 27, "008-09": 25, "055-967": 35, "897-99": 44, "890-98": 56, "344-32": 65, "43-955": 59, "001-233": 9, "089-111": 15, "090-090": 17, "56-777": 23, "44-909": 27, "13-111": 21, "87-432": 15, "87-433": 14, "87-434": 23, "87-435": 11, "87-436": 12, "87-437": 16, "94-121": 15, "94-122": 35, "80-089": 10, "87-456": 8, "87-430": 40
}
age = int(input())
#your code goes here
normalSale = []
newSale = []
for i in data:
    if data[i] >= 18:
        normalSale.append(20)
    else:
        normalSale.append(5)
for i in data:
    if  data[i] >= age:
        newSale.append(20)
    else:
        newSale.append(5)
print(int(((sum(newSale) -sum(normalSale))/sum(normalSale))*100))
```
![image](https://github.com/Rizwans-github/DSA/assets/141806496/8fbfb2b0-f29d-4dcc-9446-b4261dc87c06)
![image](https://github.com/Rizwans-github/DSA/assets/141806496/79a7b26a-adc8-444a-99db-2d42035856f0)
![image](https://github.com/Rizwans-github/DSA/assets/141806496/8d9aeb05-fae7-4736-ad00-39491061c21a)

```py
class Stack:
    def __init__(self):
        self.items = []
    
    def is_empty(self):
        return self.items == []

    def push(self, item):
        return self.items.insert(0, item)

    def pop(self):
        return self.items.pop(0)

    def print_stack(self):
        print(self.items)


print(Stack().is_empty())
s = Stack()

s.push(3)
s.push(2)
s.push(1)
s.print_stack()
s.pop()
s.print_stack()
```
![image](https://github.com/Rizwans-github/DSA/assets/141806496/a7b5eaef-9c18-475e-956c-bb94cf9616fd)

```py
class Browser:
    def __init__(self):
      self.links = []  
  
    def is_empty(self):
      return self.links == []
  
    def push(self, link):
      self.links.insert(0, link)
    
    def pop(self):
      return self.links.pop(0)
    
  
x = Browser()
x.push('about:blank')
x.push('www.sololearn.com')
x.push('www.sololearn.com/courses/')
x.push('www.sololearn.com/courses/python/')

while not x.is_empty():
    print(x.pop())
```
![image](https://github.com/Rizwans-github/DSA/assets/141806496/4779c8a8-469b-4ad9-8167-7b636e0cd72d)
![image](https://github.com/Rizwans-github/DSA/assets/141806496/7d11cb35-4ae4-4338-80f0-c325089c477f)
![image](https://github.com/Rizwans-github/DSA/assets/141806496/3e2aef0d-1e8a-4fe3-9f82-e03cba3ddca8)

```py
class Queue:
    def __init__(self):
        self.items = []

    def is_empty(self):
        return self.items == []

    def enqueue(self, item):
        self.items.insert(0, item)

    def dequeue(self):
        return self.items.pop()

    def print_queue(self):
        print(self.items)

q = Queue()
q.enqueue('a')
q.enqueue('b')
q.enqueue('42')
q.print_queue()

q.dequeue()
q.print_queue()
```

![image](https://github.com/Rizwans-github/DSA/assets/141806496/bcf9f601-073a-46bd-8297-bb01b33e1d4e)

![image](https://github.com/Rizwans-github/DSA/assets/141806496/cc430a6e-8e23-4f7e-9d3c-2c9270b14e3b)

```py
class CallCenter:
    def __init__(self):
      self.customers = []

    def is_empty(self):
      return self.customers == []

    def add(self, x):
      self.customers.insert(0, x)

    def next(self):
      return self.customers.pop()


c = CallCenter()

while True:
    n = input()
    if n == 'end':
        break
    c.add(n)
time = 0
#your code goes here
while not c.is_empty():
  if c.customers[-1] == "general":
    time += 5
    c.next()
  else:
    time += 10 
    c.next()

print(time)


First Approach:
'''class CallCenter:
    def __init__(self):
      self.customers = []

    def is_empty(self):
      return self.customers == []

    def add(self, x):
      self.customers.insert(0, x)

    def next(self):
      return self.customers.pop()


c = CallCenter()

while True:
    n = input()
    if n == 'end':
        break
    c.add(n)
time = 0
#your code goes here
print(c.customers)
for i in c.customers:
  if i == "general":
    time += 5
    c.next()
  else:
    time += 10
    c.next()
print(time)'''
```
![image](https://github.com/Rizwans-github/DSA/assets/141806496/7d3e5492-f8c3-45d7-9402-4b1dc7bcb5cb)
