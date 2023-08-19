

## 🐞程式碼除錯
以下是`[程式語言]`的程式碼，請幫我找出錯誤並且修正。讓我們一步一步地檢查，以確保我們得到正確答案。

```
[附上程式碼]
```

#### 範例
以下是Python的程式碼，請幫我找出錯誤並且修正。讓我們一步一步地檢查，以確保我們得到正確答案。

```
import numpy as np

x = np.array([[1, 2, 3], [4, 5, 6]])
new_data = [7, 8, 9]
x = np.append(x, new_data, axis=0)
print(x)
```

## 📖解讀程式碼
你現在是一個`[程式語言]`專家，請一步一步地解析以下程式碼功能。

```
[附上程式碼]
```

#### 範例
你現在是一個Python專家，請一步一步地解析以下程式碼功能。

```
import numpy as np

x = np.array([[1, 2, 3], [4, 5, 6]])
new_data = np.array([[7, 8, 9]])
x = np.append(x, new_data, axis=0)
print(x)
```

## 🔀程式碼轉換
請幫我將以下`[程式語言]`程式碼轉換成`[程式語言]`語言:

```
[附上程式碼]
```

#### 範例
請幫我將以下Python程式碼轉換成JavaScript語言:

```
import random
import string

def generate_random_token(token_length):
    characters = string.ascii_letters + string.digits
    token = ''.join(random.choice(characters) for _ in range(token_length))
    return token

length = 10
token = generate_random_token(length)
print("Generated token:", token)
```

## 🧹重構程式碼
將以下程式碼改寫成更簡潔的版本並說明原因。

```
［附上程式碼］
```

#### 範例
將以下Python程式碼改寫成更簡潔的版本並說明原因。

```
import numpy as np

def calculate_mean(data):
    total = sum(data)
    mean = total / len(data)
    return mean

def calculate_standard_deviation(data, mean):
    squared_diff_sum = sum((x - mean) ** 2 for x in data)
    variance = squared_diff_sum / len(data)
    standard_deviation = variance ** 0.5
    return standard_deviation

# 輸入數據
data = [[1, 2, 3, 4, 5], [6, 7, 8, 9, 10]]
results = []

for i in range(len(data)):
    # 計算平均值
    mean = calculate_mean(data[i])
    # 計算標準差
    standard_deviation = calculate_standard_deviation(data[i], mean)
    new_data = [mean, standard_deviation]
    results.append(new_data)

print(results)
```

## 👨‍💻寫程式
請幫我用`[程式語言]`語言，幫我寫一個`[功能]`的程式碼，其中須包含以下功能：

1. `[功能1]`
2. `[功能2]`

另外，需要幫我做到以下事情：

1. `[額外描述1]`
2. `[額外描述2]`

#### 範例
請幫我用Python語言，幫我寫一個物件導向的程式碼，其中須包含以下功能：

1. 產生加密且隨機token。
2. 可以指定token長度。

另外，需要幫我做到以下事情：
1. 遵循 Google Python 命名慣例與風格
2. 採用 Google Python 註解風格
3. 程式碼必須註解


## 其他優秀的Prompt
- [ExplainThis](https://www.explainthis.io/zh-hant/chatgpt)
