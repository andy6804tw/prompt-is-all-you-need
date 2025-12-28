
## 不只是搜集 Prompt，而是學會「表達需求」

這個專案收錄了一些實用的提示詞（Prompt），**主要來源是我自己在日常工作與實際使用 AI 時，覺得「真的有用」的紀錄**。
因此這些內容會整理在 Issue 中，目的是方便我（以及有需要的人）能快速複製、快速使用。

> 但即便如此，**我仍然不建議把「一直搜集 Prompt」當成使用 AI 的主要方式**。

### Prompt 不是重點，需求才是

在現在這個階段，Prompt 並不是固定公式，也不是照抄就一定有效。
真正關鍵的能力，其實是——**你能不能把「想做什麼」說清楚**。

比起找一條「看起來很強的 Prompt」，更好的做法是：

1. **先用自己的話描述需求**
   不需要專業、不需要完整，只要是真實想法。

2. **請 AI 幫你整理、補齊與通順化**
   讓 AI 協助你把模糊的意圖轉成結構化的需求。

3. **針對不符合預期的地方持續導正**
   告訴 AI 哪裡不對、哪裡需要更精準。

4. **最後自然會產出一份「為你量身打造」的專業 Prompt**
   這份 Prompt 才是真正能穩定產出你要結果的關鍵。

<img width="632" height="355" alt="Screenshot 2025-12-28 at 2 29 50 PM" src="https://github.com/user-attachments/assets/9b0ab6ae-9027-447d-abf1-feb79805ee52" />

圖源為 **大力士的 AI 天地**，如果你是 **剛開始接觸 Prompt，或常常不知道該怎麼把需求講清楚**，非常推薦閱讀以下文章：

👉 **[《新手完全不懂 Prompt，也能讓 AI 幫你生出專業 Prompt》](https://ai-tairona.blogspot.com/2025/12/prompt-1-prompt-ai-prompt.html)**

---


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
