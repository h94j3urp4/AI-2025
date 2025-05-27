# Google Colab
## Example:
### %%bash
告訴 Jupyter Notebook 接下來的區塊是用 Bash（終端機指令）執行，而不是 Python。
### mkdir -p demo
建立一個叫做 demo 的資料夾。
-p 表示如果資料夾已存在，不會報錯。
### ls -al
顯示目前目錄下的所有檔案與資料夾（包括隱藏檔案），詳細資訊（如權限、大小、修改時間等）。
### cd demo
進入剛剛建立的 demo 資料夾。
### pwd
印出目前的路徑（Print Working Directory），也就是你現在所在的資料夾。
##touch TA2025.txt
建立一個空的檔案，檔名是 TA2025.txt。
### ls -al
再次列出目前目錄下的所有檔案與資料夾，這次會顯示 TA2025.txt。
  
# 五個挑戰
## 1.
for i in range(10, 1, -2):
    print('test:', i)
    
PI13IB5: please write a program to calculate 1+2+3+...+10 = 55
sum = 0
for i in range(1, 11):
    sum += i
print('1+2+3+...+10 = 55, and your result?', sum)

## 2.
P0409E, Challenge

for i in range(1, 11):      
    print(i, 'T' * i)      

for i in range(10, 0, -1):  
    print(i, '+' * i)       

## 3.
stage = input('Input stage number: ')
ss = int(stage)

for i in range(1, ss + 1):
    print(i, 'T' * i)

for i in range(ss, 0, -1):
    print(i, '+' * i)

## 4.
Challenge 3
for i in range(1, 10):
    print("9 X %d = %d" % (i, 9 * i))
Challenge 4
for i in range(8, 9):  # 這樣會只跑 i = 8
    for j in range(1, 4):  # j 從 1 到 3
        print("%d X %d = %d" % (i + 1, j, (i + 1) * j))

## 5.
YourName = 'Grace'

CheckName = input('Input Your Name:')

if CheckName == YourName:
    print('You are a right user!!')
else:
    print('User name is NOT found!')
YourPassword = 'hello2024'

CheckPassword = input('Input Your Password:')

if CheckPassword == YourPassword:
    print('Correct password!')
else:
    print('Wrong password!')

