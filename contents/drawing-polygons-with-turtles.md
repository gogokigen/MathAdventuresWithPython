# 1. Drawing Polygons with Turtles

## 學習重點

* 數學\
  四則運算、外角內角
* 程式\
  Turtle module的應用、\
  變數、迴圈、函數的寫法

## 程式

### 練習迴圈的寫法

* range(2)：表示 \[ 0 , 2 )，所以只有 0、1
* for i in range(2)：表示 i = 0 時，完成這區塊的事，然後對 i 加 1。所以，\
  　現在 i = 1，再做一次這個區塊的事。

```
for i in range(2):
    print('hello')
```

#### 輸出結果

![](<../.gitbook/assets/圖片 (1).png>)

### Turtle module的應用

#### Example 1

* from turtle import \*：\
  from：要匯入 turtle 這個模組\
  import：我想要使用 turtle  裡面有用的 code。但如果是 \*\
  　則表示我要匯入所有turtle 這模組裡的東西
* forward(100)：往前走 100 步

```
from turtle import *

forward(100)
shape('turtle')
```

**輸出結果**

![](<../.gitbook/assets/圖片 (4) (1).png>)

#### Example 2

* right(120)：往右轉 120度，這就是外角。

```
from turtle import *

def triangle(sidelength = 100):
    for i in range(3):
        forward(sidelength)
        right(120)

triangle()
```

**輸出結果**

![](<../.gitbook/assets/圖片 (7) (1).png>)

#### Homework

* 把 Example 2 的 120 改成 60，圖會是怎樣呢？
* 上面兩個例子中，哪個是函數？

### 函數的寫法

我們會把可以重複利用的行為與事，獨立寫成函數，之後可以重複使用！\
函數的開頭會是：def \*\*\*\*:\
之後的行為與敘述要**縮排**!!!

### **變數的操作**

#### **想想看**

* \= 在這邊是什麼意思？
* \==  在這邊是什麼意思？

#### Example 1

輸出結果是什麼呢？

```
length = 5

length = length + 7

print(length)
```

#### Example 2

寫個小程式證明這個敘述：\
count = count + 1\
跟\
count += 1\
一樣!

#### Example 3

輸出結果是什麼呢？

```
radius = 20

radius == 20
```

## 數學

### 外角

![](<../.gitbook/assets/圖片 (5) (1) (1).png>)

### 內角？

上圖的內角是幾度？\
外角和內角的關係是…？
