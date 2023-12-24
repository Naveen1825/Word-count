# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Decleare number of words is 0
### Step 2: 
open it with txt file
### Step 3: 
Give range for i
### Step 4:  
Then next split the words
### Step 5: 
count the number of words
### Step 6: 
Giving print statement for getting output
## PROGRAM:
```
num_words =0
with open('trty','r') as file1:
 for i in file1:
  word =i.split()
  num_words += len(word)
print("Number of words={}".format(num_words))
```
### OUTPUT:
### trty.txt
<img width="960" alt="292415600-5ebe3d43-d35f-4ecc-b3c2-cb40c71bdb73" src="https://github.com/Naveen1825/Word-count/assets/138969868/9f049d0b-77f3-475b-9888-296fda3252e4"><br>
### python file
<img width="960" alt="292415375-b2bc09bc-ae45-4f63-aeaa-a4a33aaa7a23" src="https://github.com/Naveen1825/Word-count/assets/138969868/c7589645-45cc-48bf-b73c-c6bf1476693b"><br>
### output image
<img width="804" alt="292418556-097ca691-d8bf-473b-bd2b-136b294b1e38" src="https://github.com/Naveen1825/Word-count/assets/138969868/0a761078-bc19-4971-8762-ff90342ac708">

## RESULT:
Thus the program is written to find the word count from a text.
