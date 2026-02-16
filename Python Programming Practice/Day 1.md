**🐍 DAY 1 – Python Programming Practice (Basics)**

**🐍 दिन 1 – Python प्रोग्रामिंग अभ्यास (बेसिक्स)**

**1️⃣ Print Statement Programs**

**1️⃣ प्रिंट स्टेटमेंट प्रोग्राम**

**Program 1: Hello World**

**प्रोग्राम 1: हेलो वर्ल्ड**

print("Hello World")

**▶ Run / कैसे चलेगा:**

python file.py

**🖥 Output:**

Hello World

**👉 Prints text on screen.  
👉 स्क्रीन पर टेक्स्ट दिखाता है।**

**Program 2: Print Your Name**

**प्रोग्राम 2: अपना नाम प्रिंट करें**

print("My name is Vicky")

🖥 Output:

My name is Vicky

👉 Displays your name.  
👉 आपका नाम दिखाता है।

**Program 3: Multi-line Print**

**प्रोग्राम 3: मल्टी-लाइन प्रिंट**

**📌 English:**

**This program prints multiple lines using multiple print() statements.**

**📌 हिन्दी:**

**यह प्रोग्राम कई print() स्टेटमेंट का उपयोग करके कई लाइनों को प्रिंट करता है।**

**✅ Code:**

print("Welcome to Python")

print("Day 1 Practice")

print("Let's Start Coding")

**▶ How to Run:**

1.  **Notepad ya VS Code me file save karein:**

**multi\_print.py**

1.  **Command prompt me likhein:**

python multi\_print.py

**✅ Output:**

Welcome to Python

Day 1 Practice

Let's Start Coding

**🔎 Explanation (English):**

*   **Every print() prints text on a new line.**
*   **Python automatically moves to the next line after each print.**

**🔎 व्याख्या (हिन्दी):**

*   **हर print() नई लाइन में टेक्स्ट दिखाता है।**
*   **Python खुद ही अगली लाइन में चला जाता है।**

**_🎯 Extra Practice (थोड़ा और सीखें)_**

**🔹 Same Output Using Single Print:**

print("Welcome to Python\\nDay 1 Practice\\nLet's Start Coding")

**✅ Output:**

Welcome to Python

Day 1 Practice

Let's Start Coding

**🔹 \\n का मतलब है → New Line**

**2️⃣ Variables Programs**

**2️⃣ वेरिएबल्स प्रोग्राम**

**Program 4: Integer Variable**

**प्रोग्राम 4: इंटीजर वेरिएबल**

**✅ Code:**

age = 25

print(age)

**📌 English Explanation:**

*   age = 25  
    → Stores the number **25** inside a variable named age.
*   print(age)  
    → Prints the value stored in the variable.

👉 Stores number in a variable.  
👉 एक संख्या को वेरिएबल में स्टोर करता है।

**📌 हिन्दी व्याख्या:**

*   age = 25  
    → 25 संख्या को age नाम के वेरिएबल में रखा गया है।
*   print(age)  
    → वेरिएबल में रखी हुई वैल्यू को स्क्रीन पर दिखाता है।

**▶ How to Run:**

1.  File save करें:

variable.py

1.  Command Prompt में लिखें:

python variable.py

**✅ Output:**

25

**🔎 Important Concept**

👉 = को assignment operator कहते हैं।  
👉 यह value को variable में डालता है।

**_🎯 Extra Practice_**

**1️⃣ Change the value:**

age = 30

print(age)

**✅ Output:**

30

**2️⃣ Store float number:**

price = 99.99

print(price)

**✅ Output:**

99.99

**Program 5: String Variable**

**प्रोग्राम 5: स्ट्रिंग वेरिएबल**

**✅ Code:**

name = "Vicky"

print(name)

**📌 English Explanation:**

*   name = "Vicky"  
    → Stores the text **"Vicky"** inside a variable called name.  
    → Text values in Python are called **strings**.
*   print(name)  
    → Prints the value stored in the variable.

👉 Stores text in a variable.  
👉 टेक्स्ट को वेरिएबल में स्टोर करता है।

**📌 हिन्दी व्याख्या:**

*   name = "Vicky"  
    → "Vicky" टेक्स्ट को name नाम के वेरिएबल में रखा गया है।  
    → टेक्स्ट को Python में **string (str)** कहते हैं।
*   print(name)  
    → वेरिएबल में रखी हुई वैल्यू को स्क्रीन पर दिखाता है।

**▶ How to Run:**

1.  File save करें:

text\_variable.py

1.  Command Prompt में लिखें:

python text\_variable.py

**✅ Output:**

Vicky

**🔎 Important Concept**

✔ Text हमेशा " " या ' ' के अंदर लिखा जाता है।  
✔ String का datatype होता है: str

**Program 6: Multiple Variables**

**प्रोग्राम 6: कई वेरिएबल्स**

**✅ Code:**

name = "Vicky"

age = 25

city = "Delhi"

print(name)

print(age)

print(city)

**📌 English Explanation:**

*   name = "Vicky" → Stores text in a variable.
*   age = 25 → Stores number in a variable.
*   city = "Delhi" → Stores another text value.
*   print() → Prints each variable on a new line.

👉 Uses multiple variables.  
👉 कई वेरिएबल्स का उपयोग करता है।

**📌 हिन्दी व्याख्या:**

*   name = "Vicky" → टेक्स्ट को वेरिएबल में स्टोर किया।
*   age = 25 → संख्या को वेरिएबल में स्टोर किया।
*   city = "Delhi" → एक और टेक्स्ट वैल्यू स्टोर की।
*   print() → हर वेरिएबल को अलग लाइन में दिखाता है।

**▶ How to Run:**

1.  File save करें:

multiple\_variables.py

1.  Command Prompt में लिखें:

python multiple\_variables.py

**✅ Output:**

Vicky

25

Delhi

**🔎 Important Concept**

✔ Python में अलग-अलग प्रकार के डेटा एक साथ स्टोर कर सकते हैं।  
✔ String = " "  
✔ Integer = Number

**🎯 Extra Practice**

**🔹 Print in One Line**

print(name, age, city)

**✅ Output:**

Vicky 25 Delhi

**🔹 Print in Sentence Form**

print("My name is", name, "I am", age, "years old and I live in", city)

**✅ Output:**

My name is Vicky I am 25 years old and I live in Delhi

**3️⃣ Taking User Input**

**3️⃣ यूज़र से इनपुट लेना**

**Program 7: User Name Input**

**प्रोग्राम 7: यूज़र नाम इनपुट**

**✅ Code:**

name = input("Enter your name: ")

print("Hello", name)

**📌 English Explanation:**

*   input("Enter your name: ")  
    → Takes input from the user.  
    → Whatever user types is stored in variable name.
*   print("Hello", name)  
    → Prints greeting message with the entered name.

👉 Takes input from user.  
👉 यूज़र से इनपुट लेता है।

**📌 हिन्दी व्याख्या:**

*   input("Enter your name: ")  
    → यूज़र से नाम पूछता है।  
    → यूज़र जो भी टाइप करता है, वह name वेरिएबल में स्टोर हो जाता है।
*   print("Hello", name)  
    → यूज़र के नाम के साथ मैसेज दिखाता है।

**▶ How to Run:**

1.  File save करें:

user\_input.py

1.  Command Prompt में लिखें:

python user\_input.py

**▶ Example Run:**

Enter your name: Vicky

**✅ Output:**

Hello Vicky

**🔎 Important Concept**

✔ input() हमेशा data को **string (str)** के रूप में लेता है।  
✔ अगर number लेना हो तो int() या float() लगाना पड़ता है।

**🎯 Extra Practice**

**🔹 Take Age from User**

age = input("Enter your age: ")

print("Your age is", age)

**🔹 Take Number Input Proper Way**

num = int(input("Enter a number: "))

print("You entered:", num)

**Program 8: User Age Input**

**प्रोग्राम 8: यूज़र उम्र इनपुट**

**✅ Code:**

age = input("Enter your age: ")

print("Your age is", age)

**📌 English Explanation:**

*   input() always stores the value as **string (str)**.
*   Even if user enters a number, Python treats it as text.
*   The value is stored in variable age.

👉 Input is stored as string.  
👉 इनपुट स्ट्रिंग के रूप में स्टोर होता है।

**📌 हिन्दी व्याख्या:**

*   input() हमेशा वैल्यू को **string (str)** के रूप में स्टोर करता है।
*   अगर यूज़र नंबर भी डाले, तब भी Python उसे टेक्स्ट मानेगा।
*   वह वैल्यू age वेरिएबल में स्टोर होती है।

**▶ Example Run:**

Enter your age: 25

**✅ Output:**

Your age is 25

**🔎 Important Concept (Very Important ⚠)**

Check datatype:

age = input("Enter your age: ")

print(type(age))

**✅ Output:**

<class 'str'>

✔ Even though we entered 25  
✔ It is still stored as string

**🎯 Why This Is Important?**

अगर हम ऐसे लिखें:

age = input("Enter your age: ")

print(age + 5)

**❌ Error आएगा क्योंकि:**

String + Integer add नहीं हो सकता।

**✅ Correct Way (Convert to Integer)**

age = int(input("Enter your age: "))

print(age + 5)

**▶ Example Run:**

Enter your age: 25

**✅ Output:**

30

**4️⃣ Type Conversion**

**4️⃣ टाइप कन्वर्ज़न**

**Program 9: String to Integer**

**प्रोग्राम 9: स्ट्रिंग से इंटीजर**

**✅ Code:**

num1 = int(input("Enter first number: "))

num2 = int(input("Enter second number: "))

sum = num1 + num2

print("Sum is:", sum)

**📌 English Explanation:**

*   **input() normally stores value as string.**
*   **int() converts string into integer.**
*   **num1 + num2 performs mathematical addition.**
*   **Result is stored in variable sum.**

**👉 Converts input into integer.  
👉 इनपुट को इंटीजर में बदलता है।**

**📌 हिन्दी व्याख्या:**

*   **input() वैल्यू को string के रूप में लेता है।**
*   **int() उसे integer (पूर्णांक) में बदल देता है।**
*   **num1 + num2 गणितीय जोड़ करता है।**
*   **परिणाम sum वेरिएबल में स्टोर होता है।**

**▶ Example Run:**

Enter first number: 10

**Enter second number: 5**

**✅ Output:**

Sum is: 15

**🔎 Important Concept ⚠**

**अगर int() नहीं लगाएँ तो क्या होगा?**

num1 = input("Enter first number: ")

num2 = input("Enter second number: ")

print(num1 + num2)

**▶ Example Run:**

Enter first number: 10

Enter second number: 5

**❌ Output:**

105

**👉 Because Python joins strings (concatenation)  
👉 क्योंकि Python टेक्स्ट को जोड़ देता है**

**🎯 Extra Practice**

**🔹 Subtraction Program**

num1 = int(input("Enter first number: "))

num2 = int(input("Enter second number: "))

print("Difference is:", num1 - num2)

**🔹 Multiplication Program**

print("Multiplication is:", num1 \* num2)

**🔹 Division Program**

print("Division is:", num1 / num2)

**5️⃣ Arithmetic Programs**

**5️⃣ गणितीय प्रोग्राम**

**🖥 Program 10: Addition**

**🖥 प्रोग्राम 10: जोड़**

**✅ Code:**

a = 10

b = 5

print("Addition:", a + b)

**📌 English:**

**Adds two numbers stored in variables.**

**📌 हिन्दी:**

**दो वेरिएबल में रखे नंबरों का जोड़ करता है।**

**▶ Run:**

python file.py

**✅ Output:**

Addition: 15

**🖥 Program 11: Subtraction**

**🖥 प्रोग्राम 11: घटाव**

**✅ Code:**

print("Subtraction:", 10 - 5)

**📌 English:**

**Subtracts second number from first number.**

**📌 हिन्दी:**

**पहले नंबर में से दूसरे नंबर को घटाता है।**

**✅ Output:**

Subtraction: 5

**🖥 Program 12: Multiplication**

**🖥 प्रोग्राम 12: गुणा**

**✅ Code:**

print("Multiplication:", 10 \* 5)

**📌 English:**

**Multiplies two numbers.**

**📌 हिन्दी:**

**दो नंबरों का गुणा करता है।**

**✅ Output:**

Multiplication: 50

**🖥 Program 13: Division**

**🖥 प्रोग्राम 13: भाग**

**✅ Code:**

print("Division:", 10 / 5)

**📌 English:**

**Divides first number by second number.**

**📌 हिन्दी:**

**पहले नंबर को दूसरे नंबर से भाग देता है।**

**✅ Output:**

Division: 2.0

**⚠ Note: Division gives float result (decimal).**

**🔎 Extra Important Operators**

**🔹 Modulus (Remainder)**

**🔹 शेषफल**

print("Remainder:", 10 % 3)

**✅ Output:**

Remainder: 1

**🔹 Power (Exponent)**

**🔹 घात**

print("Power:", 2 \*\* 3)

**✅ Output:**

Power: 8

**🧠 Practice Questions**

**🧠 अभ्यास प्रश्न**

**1️⃣ Take two numbers and multiply them.  
➡ दो नंबर लेकर उनका गुणा करें।**

**2️⃣ Calculate area of rectangle.  
➡ आयत का क्षेत्रफल निकालें।**

**3️⃣ Convert Celsius to Fahrenheit.  
➡ सेल्सियस को फारेनहाइट में बदलें।**

**4️⃣ Print your full bio (name, age, city).  
➡ अपना पूरा बायो प्रिंट करें।**

**5️⃣ Find average of 3 numbers.  
➡ 3 नंबर का औसत निकालें।**