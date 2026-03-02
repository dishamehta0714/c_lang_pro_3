
<img width="1507" height="956" alt="image" src="https://github.com/user-attachments/assets/f8f6c540-72c6-4a1f-9889-e9ac0664faed" />

<img width="1496" height="927" alt="image" src="https://github.com/user-attachments/assets/8b96a374-bdc4-42e1-b46f-b181d38e79ae" />

<img width="1502" height="892" alt="image" src="https://github.com/user-attachments/assets/1d282b93-c03d-472b-89a8-07b48578e38c" />

1️⃣ Alphabet Program (do-while loop)
char alpha ='a';

do
{
    printf("%c ",alpha);
    alpha = alpha + 4;
} while (alpha <= 'z');
🔹 Logic (Easy Language)

alpha = 'a' → starting letter a

do block pehle execute hota hai

Har baar:

letter print hoga

usme 4 add hoga (alpha = alpha + 4)

Jab tak letter 'z' se chhota ya equal hai tab tak loop chalega

🔹 Output kya aayega?
a e i m q u y
🔹 Iteration Samjho
Iteration	alpha value	Print
1	a	a
2	e	e
3	i	i
4	m	m
5	q	q
6	u	u
7	y	y
✅ 2️⃣ Count Total Digits Program (while loop)
while (no != 0)
{
    no = no / 10;
    count++;
}
🔹 Logic (Easy Hindi)

User number enter karega (maan lo 12345)

Jab tak number 0 nahi hota, tab tak:

Number ko 10 se divide karo

count +1 karo

🔹 Example (12345)
Step	no value	count
1	12345	0
2	1234	1
3	123	2
4	12	3
5	1	4
6	0	5

Output:

Total digits: 5

👉 Har divide se ek digit remove hoti hai.

✅ 3️⃣ First and Last Digit Sum Program
last = num % 10;

👉 % 10 se last digit milti hai.

while (num >= 10)
{
    num = num / 10;
}

👉 Loop tab tak chalega jab tak number 1 digit ka na ho jaye.

first = num;

👉 Ab num me sirf first digit bachi hogi.

🔹 Example (Enter 4567)

last = 4567 % 10 = 7

Loop chalega:

4567 → 456

456 → 45

45 → 4

first = 4

sum = 4 + 7 = 11

Output:

sum of digit: 11

