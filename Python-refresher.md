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
