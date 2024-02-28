![image](https://github.com/Rizwans-github/DSA/assets/141806496/652ceaf2-d074-4ab9-a7a7-200807ca434a)
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
