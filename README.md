# FACTORIAL-OF-A-NUMBER-USING-8051-KEIL

**AIM:**

To write and execute Assembly language Program to perform factorial of a number using 8051 keil.
APPARATUS REQUIRED: Personal computer with Keil software

**ALGORITHM:**

• Start  

• Input: Read the number n.  

• Initialize:  

•Set factorial to 1.  

•Set i to 1.  

• Loop: While i is less than or equal to n:  

•Multiply factorial by i.  

•Increment i by 1.  

• Output: Store or print the value of factorial.  

• End

**FLOW CHART:**
<img width="261" height="308" alt="image" src="https://github.com/user-attachments/assets/bffe89f6-3ba9-4294-b817-8b545f680e66" />

**Program:**

ORG 0000H   

MOV A,#04H  

MOV R0,A  

ACALL FACTORIAL  

MOV 40H,A  

SJMP THIN  

FACTORIAL:DEC R0  

CJNE R0,#01H,PRODUCT  

SJMP THICK   

PRODUCT:MOV B,R0  

MUL AB  

ACALL FACTORIAL  

THICK: RET  

THIN:  

END
**Input:**
<img width="979" height="534" alt="image" src="https://github.com/user-attachments/assets/62a21e04-e4fd-488a-8e6d-74c52f022925" />

**Output:**  
<img width="966" height="532" alt="image" src="https://github.com/user-attachments/assets/a202309b-8a30-4e30-a698-33cff16c66c0" />

<br>
<br>
<br>



**Manual Calculations:**  
![WhatsApp Image 2025-11-09 at 19 23 18_8a6d3608](https://github.com/user-attachments/assets/01c6325a-105a-4f5d-a4d2-335d543f2072)

<br>
<br>
<br>
<br>
<br>
<br>





**Result:**

Thus the factorial of a number using 8051 keil was calculated and shown the output.
