# Alex Fox Final Portfolio
**Projects:**

**Equation Bot**

_Description:_

- This project is a discord bot that you can type an equation into and it will return the answer to the equation. The bot allows you to do PEMDAS, derivatives, and basic equations
Equation Setup:
- you have to put a space between every number or symbol in the equation
- EXAMPLE ---> ( 5 * 4 ) + 6 = 26 (The parentheses will make  that thing in them come first. If there is no addition, subtraction, or division, the number in the parentheses will be multiplied by the number outside of them)
  
Multiply: *

Divide: /

Add: +

Subtract: -

Exponent: (number)^(number)

_Pieces of Code:_

**def add(a, b, c, d):

   return a + b + c + d

def subtract(a, b, c, d):

   return a - b - c - d

def multiply(a, b, c, d):

   return a * b * c * d

def divide(a, b, c, d):

   return a / b / c / d

def pow(a, b):
   
   return a**b #this is the exponants, so it would be a to the power of b (second number in this expression will always be defined as b)

#basic opporations

@bot.command()
async def calculate(ctx, num1, operation, num2, num3, num4):
   #I can add more numbers if needed but this is what I have so far
   a = int(num1) 
   b = int (num2)
   c = int (num3)
   d = int (num4)**

   - This is the first portion of the code after the imports

_Type of code:_

- For this project, I used Python code. I wanted to try and use JavaScript but in the time that I had to do this project I ended up just using code that I already had an understanding of, and that I knew I could do quickly.

_The code:_
Find this code [here](https://github.com/alexfox06/EquationBot)
