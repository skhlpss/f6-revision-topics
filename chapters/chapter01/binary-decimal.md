# Table of Content{#toc}
<!-- MarkdownTOC depth=2 -->

- [由十進數到二進數](#session01)
  - [例1: 如何將37化成二進數？](#eg1)
  - [例2: 如何將29化成二進數？](#eg2)
- [由二進數到十進數](#session2)
  - [例3: 如何將110111化成十進數?](#eg3)
  - [例4: 如何將10101化成十進數?](#eg4)

<!-- /MarkdownTOC -->

---

# 由十進數到二進數{#session01}

## 例1: 如何將37化成二進數？{#eg1}

由於是二進制，所以先將所小於所求數值(37)的2的次方數列出來。

### Step 1: 列出次方數{#step-1}
- $$2^0 = 1$$ 
- $$2^1 = 2$$ 
- $$2^2 = 4$$ 
- $$2^3 = 8$$ 
- $$2^4 = 16$$ 
- $$2^5 = 32$$ 

### Step 2: 減去次方數{#step-2} 
由大至小，將所求數值減去次方數，直至獲得0為止
- 37 - **32** = 5 (減去 **32** 一次)
- 5 - **4** = 1 (減去 **4** 一次)
- 1 - **1** = 0 (減去 **1**  一次)


### Step 3: 利用表列出答案{#step-3} 
將所減去次方數的次數寫於下表中。

學生可用以下圖表作對應

| $$2^5 = 32$$    | $$2^4 = 16$$    | $$2^3 = 8$$    | $$2^2 = 4$$   | $$2^1 = 2$$   | $$2^0 = 1$$    |
| --------------: | --------------: | -------------: | ------------: | ------------: | -------------: |
| 1               | 0               | 0              | 1             | 0             | 1              |

因此 37 的二進數為 $$100101_2$$

---


## 例2: 如何將29化成二進數？{#eg2}
<!--sec data-title="題解" data-id="eg2ans" data-show=true data-collapse=true ces-->

### Step 1
[參考例一](#eg1)

### Step 2

由大至小，將所求數值減去次方數，直至減獲得0為止
- 29 - **16** = 13 (減去 **16** 一次)
- 13 - **8** = 5 (減去 **8** 一次)
- 5 - **4** = 1 (減去 **4**  一次)
- 1 - **1** = 0 (減去 **1**  一次)

### Step 3
將所減去次方數的次數寫於下表中。

| $$2^4 = 16$$    | $$2^3 = 8$$    | $$2^2 = 4$$   | $$2^1 = 2$$   | $$2^0 = 1$$    |
| --------------: | -------------: | ------------: | ------------: | -------------: |
| 1               | 1              | 1             | 0             | 1              |

因此 29 的二進數為 $$11101_2$$

<!--endsec-->

---
# 由二進數到十進數{#session2}

## 例3: 如何將110111化成十進數?{#eg3}

### Step 1
[參考例一](#eg1)，由於 $$110111_2$$ 共有6個數位，所以列出6個2的次方數。

- $$2^0 = 1$$ 
- $$2^1 = 2$$ 
- $$2^2 = 4$$ 
- $$2^3 = 8$$ 
- $$2^4 = 16$$ 
- $$2^5 = 32$$ 

### Step 2: 將各數位的數字寫入下表

| $$2^5 = 32$$ | $$2^4 = 16$$ | $$2^3 = 8$$ | $$2^2 = 4$$ | $$2^1 = 2$$ | $$2^0 = 1$$ |
| ----------:  | ----------:  | ----------: | ----------: | ---------:  | ----------: |
| 1            | 1            | 0           | 1           | 1           | 1           |

### Step 3
因此，$$110111_2$$ 的十進數為

$$ 32 + 16 + 4 + 2 + 1  = 55 $$

---
## 例4: 如何將10101化成十進數?{#eg4}

<!--sec data-title="題解" data-id="eg4ans" data-show=true data-collapse=true ces-->

[參考例3](#eg3)

將各數位的數字寫入下表

| $$2^4 = 16$$ | $$2^3 = 8$$ | $$2^2 = 4$$ | $$2^1 = 2$$ | $$2^0 = 1$$ |
| ----------:  | ----------: | ----------: | ---------:  | ----------: |
| 1            | 0           | 1           | 0           | 1           |

因此，$$10101_2$$ 的十進數為

$$ 16 + 4 + 1  = 21 $$

<!--endsec-->