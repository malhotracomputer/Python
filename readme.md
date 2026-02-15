# Introduction & installation

## 🐍 Python – Introduction

**Python – परिचय**

**🔹 What is Python?**

**Python** is a high-level, interpreted, general-purpose programming language.

**Python** ek **high-level, interpreted aur general-purpose programming language** hai.

**🔹 Developed By**

Python was developed by **Guido van Rossum** in **1991**.

**(Hindi – देवनागरी)**  
पाइथन को **गुइडो वैन रोसम** ने **1991** में विकसित किया था।  

### Features of Python

**Python की विशेषताएँ**

*   Easy to learn and easy to read  
    👉 Python sikhna aur padhna bahut aasan hai
*   Interpreted Language  
    👉 Python ek **interpreted language** hai (line by line execute hoti hai)
*   Platform Independent  
    👉 Python Windows, Linux aur macOS sab par kaam karti hai
*   Free and Open Source  
    👉 Python bilkul free aur open source hai
*   Object Oriented Language  
    👉 Python ek **object-oriented language** hai
*   Large Standard Library  
    👉 Python me bahut saari built-in libraries hoti hain.

## 🎯 Uses of Python

**Python का उपयोग**

*   Web Development (Django, Flask)  
    👉 Web websites aur applications banane me
*   Data Science & Machine Learning  
    👉 Data analysis aur AI banane me
*   Automation / Scripting  
    👉 Repetitive kaam automatically karne me
*   Desktop Applications  
    👉 Desktop software banane me
*   Game Development  
    👉 Games banane me
*   Cyber Security  
    👉 Security tools aur testing me

### 💻 Python Installation

**🔍 Check Python Installed or Not**

**Python पहले से installed है या नहीं**

**Command:**

python --version

or

python3 --version

Agar version show ho jaye → Python installed hai ✅

### Python Installation on Windows

**Windows में Python कैसे Install करें**

**Steps:**

1.  Open browser and go to **www.python.org**  
    👉 Browser open karke python.org website par jaaye
2.  Click on **Downloads**  
    👉 Downloads par click kare
3.  Download **Python 3.x (Latest Version)**  
    👉 Latest Python version download kare
4.  Run the installer  
    👉 Installer file open kare
5.  ✔️ Tick **Add Python to PATH** (Very Important)  
    👉 “Add Python to PATH” par ✔️ lagana bahut zaroori hai
6.  Click **Install Now**  
    👉 Install Now par click kare

**Verify Installation:**

python --version

pip --version

### 🍎 Python Installation on macOS

**macOS में Python Install करना**

**Method 1: Official Website**

*   Download from **python.org**
*   Install .pkg file

**Verify Installation:**

python3 --version

### 🐧 Python Installation on Linux (Ubuntu)

**Linux (Ubuntu) में Python Install करना**

sudo apt update

sudo apt install python3

sudo apt install python3-pip

Check :  
python3 --version

pip3 --version

# 🐍 Python Syntax & Variables

## 🔹 Python Syntax

**What is Syntax?**

**(English)**  
Syntax refers to the rules that define how a Python program is written.  
Python syntax is simple, clean, and easy to read.

**(हिंदी – देवनागरी)**  
सिंटैक्स उन नियमों को कहते हैं जिनके अनुसार पाइथन प्रोग्राम लिखा जाता है।  
पाइथन की सिंटैक्स सरल और पढ़ने में आसान होती है।

**Example of Python Syntax**

print("Hello Python")

**(English)**  
Python does not use semicolons or curly braces.  
It uses indentation to define blocks of code.

**(हिंदी – देवनागरी)**  
पाइथन में सेमीकोलन या कर्ली ब्रैकेट का उपयोग नहीं होता।  
कोड ब्लॉक बनाने के लिए इंडेंटेशन का उपयोग किया जाता है।

### 📏 Indentation in Python

**(English)**  
Indentation is mandatory in Python.  
It defines the structure of the program.

**(हिंदी – देवनागरी)**  
पाइथन में इंडेंटेशन अनिवार्य होती है।  
यह प्रोग्राम की संरचना को निर्धारित करती है।

**Example:**

if 10 > 5:

print("10 is greater")

**(English)**  
Incorrect indentation causes an IndentationError.

**(हिंदी – देवनागरी)**  
गलत इंडेंटेशन होने पर IndentationError आता है।

### 🏷️ Variables in Python

**Python में वेरिएबल्स**

**What is a Variable?**

**(English)**  
A variable is a container used to store data values in memory.

**(हिंदी – देवनागरी)**  
वेरिएबल एक कंटेनर होता है जिसमें डेटा वैल्यू स्टोर की जाती है।

**Creating Variables**

x = 10

name = "Rahul"

price = 99.50

**(English)**  
Python is dynamically typed, so you do not need to declare the data type.

**(हिंदी – देवनागरी)**  
पाइथन एक डायनामिकली टाइप्ड भाषा है, इसलिए डेटा टाइप लिखना ज़रूरी नहीं होता।

### 🧠 Rules for Variable Names

**(English)**

*   Must start with a letter or underscore (\_)
*   Cannot start with a number
*   Cannot contain spaces
*   Special characters are not allowed
*   Python keywords cannot be used

**(हिंदी – देवनागरी)**

*   वेरिएबल का नाम अक्षर या \_ से शुरू होना चाहिए
*   नंबर से शुरू नहीं हो सकता
*   स्पेस की अनुमति नहीं है
*   विशेष चिन्ह मान्य नहीं हैं
*   पाइथन कीवर्ड का उपयोग नहीं किया जा सकता

**Valid and Invalid Variable Names**

\# Valid

name = "Amit"

\_age = 25

marks1 = 90

\# Invalid

1name = "Ram"

my name = "Shyam"

class = 10

**🔄 Multiple Assignment**

a, b, c = 10, 20, 30

**(English)**  
Multiple variables can be assigned values in a single line.

**(हिंदी – देवनागरी)**  
एक ही लाइन में कई वेरिएबल्स को वैल्यू दी जा सकती है।

**🔁 Assign Same Value to Multiple Variables**

x = y = z = 100

**🖨️ Printing Variables**

name = "Vicky"

age = 25

print(name)

print(age)

**📌 Summary**

**(English)**

*   Python syntax is simple and readable
*   Indentation is mandatory
*   Variables store data values
*   No need to declare data types

**(हिंदी – देवनागरी)**

*   पाइथन की सिंटैक्स सरल होती है
*   इंडेंटेशन अनिवार्य होती है
*   वेरिएबल डेटा स्टोर करता है
*   डेटा टाइप लिखना आवश्यक नहीं

# 🐍 Python Data Types

**Python डेटा टाइप्स**

**🔹 What are Data Types?**

**(English)**  
Data types specify the type of data a variable can hold.  
They tell Python how much memory to allocate and what operations can be performed on the data.

**(हिंदी – देवनागरी)**  
डेटा टाइप यह बताता है कि कोई वेरिएबल किस प्रकार का डेटा स्टोर करेगा।  
यह पाइथन को बताता है कि कितनी मेमोरी लेनी है और डेटा पर कौन-से ऑपरेशन किए जा सकते हैं।

### 🔸 Types of Data Types in Python

**Python में डेटा टाइप्स के प्रकार**

Python has the following built-in data types:

1.  Numeric Data Types
2.  Text Data Type
3.  Sequence Data Types
4.  Set Data Type
5.  Mapping Data Type
6.  Boolean Data Type
7.  None Data Type

### 1️⃣ Numeric Data Types

**संख्यात्मक डेटा टाइप**

**a) int (Integer)**

**(English)**  
int is used to store whole numbers without decimals.

**(हिंदी – देवनागरी)**  
int का उपयोग बिना दशमलव वाले पूर्णांक संख्याओं को स्टोर करने के लिए किया जाता है।

a = 10

b = -25

**b) float**

**(English)**  
float is used to store numbers with decimal points.

**(हिंदी – देवनागरी)**  
float का उपयोग दशमलव वाली संख्याओं को स्टोर करने के लिए किया जाता है।

pi = 3.14

price = 99.50

**c) complex**

**(English)**  
complex is used to store complex numbers.

**(हिंदी – देवनागरी)**  
complex का उपयोग कॉम्प्लेक्स संख्याओं को स्टोर करने के लिए किया जाता है।

x = 2 + 3j

### 2️⃣ Text Data Type

**टेक्स्ट डेटा टाइप**

**string (str)**

**(English)**  
str is used to store text data.  
Strings are written inside single or double quotes.

**(हिंदी – देवनागरी)**  
str का उपयोग टेक्स्ट डेटा को स्टोर करने के लिए किया जाता है।  
स्ट्रिंग सिंगल या डबल कोट्स में लिखी जाती है।

name = "Python"

message = 'Hello World'

### 3️⃣ Sequence Data Types

**सीक्वेंस डेटा टाइप**

**a) List**

**(English)**  
A list is an ordered, mutable collection of items.  
It allows duplicate values.

**(हिंदी – देवनागरी)**  
लिस्ट एक क्रमबद्ध और परिवर्तनीय (mutable) डेटा टाइप है।  
इसमें डुप्लिकेट वैल्यू की अनुमति होती है।

numbers = \[1, 2, 3, 4\]

**b) Tuple**

**(English)**  
A tuple is an ordered, immutable collection of items.

**(हिंदी – देवनागरी)**  
ट्यूपल एक क्रमबद्ध लेकिन अपरिवर्तनीय (immutable) डेटा टाइप है।

colors = ("red", "green", "blue")

**c) Range**

**(English)**  
range is used to generate a sequence of numbers.

**(हिंदी – देवनागरी)**  
range का उपयोग संख्याओं की श्रेणी बनाने के लिए किया जाता है।

r = range(1, 5)

### 4️⃣ Set Data Type

**सेट डेटा टाइप**

**set**

**(English)**  
A set is an unordered collection of unique elements.

**(हिंदी – देवनागरी)**  
सेट एक बिना क्रम वाला डेटा टाइप है जिसमें केवल यूनिक वैल्यू होती हैं।

fruits = {"apple", "banana", "mango"}

### 5️⃣ Mapping Data Type

**मैपिंग डेटा टाइप**

**Dictionary (dict)**

**(English)**  
A dictionary stores data in key-value pairs.

**(हिंदी – देवनागरी)**  
डिक्शनरी डेटा को key-value के रूप में स्टोर करती है।

student = {

"name": "Rahul",

"age": 20

}

### 6️⃣ Boolean Data Type

**बूलियन डेटा टाइप**

**bool**

**(English)**  
Boolean data type has two values: True and False.

**(हिंदी – देवनागरी)**  
बूलियन डेटा टाइप में केवल दो वैल्यू होती हैं: True और False।

is\_active = True

### 7️⃣ None Data Type

**None डेटा टाइप**

**NoneType**

**(English)**  
None represents the absence of a value.

**(हिंदी – देवनागरी)**  
None किसी वैल्यू की अनुपस्थिति को दर्शाता है।

result = None

**🔍 Checking Data Type**

**डेटा टाइप कैसे जांचें**

x = 10

print(type(x))

**📌 Summary**

**(English)**

*   Data types define the type of data stored
*   Python has multiple built-in data types
*   type() function is used to check data type

**(हिंदी – देवनागरी)**

*   डेटा टाइप डेटा के प्रकार को दर्शाता है
*   पाइथन में कई बिल्ट-इन डेटा टाइप्स होते हैं
*   type() फ़ंक्शन से डेटा टाइप चेक किया जाता है

## 🐍 Python Type Casting

**🔹 What is Type Casting?**

**(English)**  
Type casting is the process of converting one data type into another data type.  
Python allows you to change the type of a variable when needed.

**(हिंदी – देवनागरी)**  
टाइप कास्टिंग का मतलब एक डेटा टाइप को दूसरे डेटा टाइप में बदलना होता है।  
पाइथन में आवश्यकता पड़ने पर वेरिएबल का डेटा टाइप बदला जा सकता है।

**🔸 Why Type Casting is Needed?**

**(English)**

*   To perform operations between different data types
*   To take user input and convert it into required data type
*   To avoid type-related errors

**(हिंदी – देवनागरी)**

*   अलग-अलग डेटा टाइप पर ऑपरेशन करने के लिए
*   यूज़र इनपुट को सही डेटा टाइप में बदलने के लिए
*   टाइप से जुड़ी गलतियों से बचने के लिए

### 🔹 Types of Type Casting in Python

**Python में टाइप कास्टिंग के प्रकार**

1.  Implicit Type Casting
2.  Explicit Type Casting

### 1️⃣ Implicit Type Casting

**इम्प्लिसिट टाइप कास्टिंग**

**(English)**  
In implicit type casting, Python automatically converts one data type into another.  
This usually happens when no data loss occurs.

**(हिंदी – देवनागरी)**  
इम्प्लिसिट टाइप कास्टिंग में पाइथन अपने आप डेटा टाइप को बदल देता है।  
यह तब होता है जब डेटा का नुकसान नहीं होता।

**Example:**

a = 10 # int

b = 2.5 # float

c = a + b

print(c)

print(type(c))

Output:

12.5

<class 'float'>

### 2️⃣ Explicit Type Casting

**एक्स्प्लिसिट टाइप कास्टिंग**

**(English)**  
In explicit type casting, the programmer manually converts the data type using built-in functions.

**(हिंदी – देवनागरी)**  
एक्स्प्लिसिट टाइप कास्टिंग में प्रोग्रामर खुद डेटा टाइप बदलता है।

**🔧 Common Type Casting Functions**

**सामान्य टाइप कास्टिंग फ़ंक्शन**

**int()**

**(English)**  
Converts a value into an integer.

**(हिंदी – देवनागरी)**  
किसी वैल्यू को integer में बदलता है।

x = int(10.7)

print(x)

**float()**

**(English)**  
Converts a value into a float.

**(हिंदी – देवनागरी)**  
किसी वैल्यू को float में बदलता है।

y = float(5)

print(y)

**str()**

**(English)**  
Converts a value into a string.

**(हिंदी – देवनागरी)**  
किसी वैल्यू को string में बदलता है।

age = 25

s = str(age)

print(s)

**list()**

**(English)**  
Converts a sequence into a list.

**(हिंदी – देवनागरी)**  
किसी सीक्वेंस को लिस्ट में बदलता है।

t = (1, 2, 3)

l = list(t)

print(l)

**tuple()**

**(English)**  
Converts a sequence into a tuple.

**(हिंदी – देवनागरी)**  
किसी सीक्वेंस को ट्यूपल में बदलता है।

l = \[4, 5, 6\]

t = tuple(l)

print(t)

**set()**

**(English)**  
Converts a sequence into a set.

**(हिंदी – देवनागरी)**  
किसी सीक्वेंस को सेट में बदलता है।

l = \[1, 2, 2, 3\]

s = set(l)

print(s)

**⚠️ Important Notes**

**महत्वपूर्ण बातें**

**(English)**

*   Invalid conversion causes ValueError
*   String must contain valid numeric data for conversion

**(हिंदी – देवनागरी)**

*   गलत कन्वर्ज़न करने पर ValueError आता है
*   स्ट्रिंग में वैध संख्या होनी चाहिए

x = int("10") # valid

y = int("abc") # error

**📌 Summary**

**सारांश**

**(English)**

*   Type casting converts one data type into another
*   Python supports implicit and explicit type casting
*   Common functions: int(), float(), str(), list(), tuple(), set()

**(हिंदी – देवनागरी)**

*   टाइप कास्टिंग डेटा टाइप बदलने की प्रक्रिया है
*   पाइथन इम्प्लिसिट और एक्स्प्लिसिट दोनों टाइप कास्टिंग सपोर्ट करता है
*   सामान्य फ़ंक्शन: int(), float(), str(), list(), tuple(), set()

# 🐍 Python Input & Output

**🔹 What is Input and Output?**

**(English)**  
Input is the data provided to a program.  
Output is the result produced by the program after processing the input.

**(हिंदी – देवनागरी)**  
इनपुट वह डेटा होता है जो प्रोग्राम को दिया जाता है।  
आउटपुट वह परिणाम होता है जो प्रोग्राम इनपुट को प्रोसेस करने के बाद देता है।

## 🖨️ Output in Python

**Python में आउटपुट**

**print() Function**

**(English)**  
The print() function is used to display output on the screen.

**(हिंदी – देवनागरी)**  
print() फ़ंक्शन का उपयोग स्क्रीन पर आउटपुट दिखाने के लिए किया जाता है।

**Example:**

print("Hello Python")

print(10)

**Printing Multiple Values**

name = "Rahul"

age = 20

print(name, age)

**(English)**  
Multiple values can be printed using a single print() function.

**(हिंदी – देवनागरी)**  
एक ही print() फ़ंक्शन से कई वैल्यू प्रिंट की जा सकती हैं।

**Using Separator and End**

print("Python", "Java", "C++", sep=", ")

print("Hello", end=" ")

print("World")

**(English)**  
sep is used to separate values and end is used to control line ending.

**(हिंदी – देवनागरी)**  
sep वैल्यू को अलग करने के लिए और end लाइन खत्म करने के तरीके को कंट्रोल करता है।

## ⌨️ Input in Python

**input() Function**

**(English)**  
The input() function is used to take input from the user.  
By default, input is taken as a string.

**(हिंदी – देवनागरी)**  
input() फ़ंक्शन का उपयोग यूज़र से इनपुट लेने के लिए किया जाता है।  
डिफ़ॉल्ट रूप से इनपुट स्ट्रिंग के रूप में लिया जाता है।

**Example:**

name = input("Enter your name: ")

print(name)

**🔄 Type Conversion with Input**

**इनपुट के साथ टाइप कन्वर्ज़न**

**(English)**  
Since input is always a string, type casting is required for numeric values.

**(हिंदी – देवनागरी)**  
क्योंकि इनपुट हमेशा स्ट्रिंग होता है, इसलिए नंबर के लिए टाइप कास्टिंग ज़रूरी है।

**Integer Input Example**

age = int(input("Enter your age: "))

print(age)

**Float Input Example**

price = float(input("Enter price: "))

print(price)

**🧮 Simple Input–Output Program**

**सरल इनपुट–आउटपुट प्रोग्राम**

a = int(input("Enter first number: "))

b = int(input("Enter second number: "))

sum = a + b

print("Sum =", sum)

**⚠️ Common Errors**

**सामान्य गलतियाँ**

**(English)**

*   Forgetting type casting
*   Entering invalid input for conversion

**(हिंदी – देवनागरी)**

*   टाइप कास्टिंग भूल जाना
*   गलत इनपुट देना

x = int(input("Enter number: ")) # Error if input is text

**📌 Summary**

**सारांश**

**(English)**

*   print() is used for output
*   input() is used for input
*   Input is always a string
*   Type casting is required for numbers

**(हिंदी – देवनागरी)**

*   आउटपुट के लिए print()
*   इनपुट के लिए input()
*   इनपुट हमेशा स्ट्रिंग होता है
*   नंबर के लिए टाइप कास्टिंग ज़रूरी है

# 🐍 Python Operators

**🔹 What are Operators?**

**(English)**  
Operators are special symbols used to perform operations on variables and values.

**(हिंदी – देवनागरी)**  
ऑपरेटर्स विशेष चिन्ह होते हैं जिनका उपयोग वेरिएबल और वैल्यू पर ऑपरेशन करने के लिए किया जाता है।

## 🔸 Types of Operators in Python

**Python में ऑपरेटर्स के प्रकार**

1.  Arithmetic Operators
2.  Assignment Operators
3.  Comparison Operators
4.  Logical Operators
5.  Bitwise Operators
6.  Membership Operators
7.  Identity Operators

### 1️⃣ Arithmetic Operators

**अंकगणितीय ऑपरेटर्स**

| Operator | Description (English) | विवरण (हिंदी) |
| --- | --- | --- |
| + | Addition | जोड़ |
| - | Subtraction | घटाना |
| * | Multiplication | गुणा |
| / | Division | भाग |
| % | Modulus | शेष |
| ** | Exponent | घात |
| // | Floor Division | पूर्ण भाग |

**Example:**

a = 10

b = 3

print(a + b)

print(a - b)

print(a \* b)

print(a / b)

print(a % b)

print(a \*\* b)

print(a // b)

### 2️⃣ Assignment Operators

**असाइनमेंट ऑपरेटर्स**

| Operator | Example | Description |
| --- | --- | --- |
| = | x = 5 | Assign value |
| += | x += 3 | x = x + 3 |
| -= | x -= 2 | x = x - 2 |
| *= | x *= 4 | x = x * 4 |
| /= | x /= 2 | x = x / 2 |

### 3️⃣ Comparison Operators

**तुलना ऑपरेटर्स**

| Operator | Meaning (English) | अर्थ (हिंदी) |
| --- | --- | --- |
| == | Equal to | बराबर |
| != | Not equal to | बराबर नहीं |
| > | Greater than | से बड़ा |
| < | Less than | से छोटा |
| >= | Greater than or equal | बड़ा या बराबर |
| <= | Less than or equal | छोटा या बराबर |

**Example:**

x = 10

y = 20

print(x == y)

print(x != y)

print(x > y)

### 4️⃣ Logical Operators

**लॉजिकल ऑपरेटर्स**

| Operator | Description | विवरण |
| --- | --- | --- |
| and | True if both true | दोनों सही हों |
| or | True if any one true | कोई एक सही हो |
| not | Reverse result | परिणाम उलटा |

**Example:**

a = True

b = False

print(a and b)

print(a or b)

print(not a)

### 5️⃣ Bitwise Operators

**बिटवाइज़ ऑपरेटर्स**

| Operator | Name |
| --- | --- |
| & | AND |
| ` | ` |
| ^ | XOR |
| ~ | NOT |
| << | Left Shift |
| >> | Right Shift |

### 6️⃣ Membership Operators

**मेंबरशिप ऑपरेटर्स**

| Operator | Description | विवरण |
| --- | --- | --- |
| in | Present in | मौजूद |
| not in | Not present | मौजूद नहीं |

list1 = \[1, 2, 3\]

print(2 in list1)

print(5 not in list1)

### 7️⃣ Identity Operators

**आइडेंटिटी ऑपरेटर्स**

| Operator | Description | विवरण |
| --- | --- | --- |
| is | Same object | समान ऑब्जेक्ट |
| is not | Different object | अलग ऑब्जेक्ट |

x = 10

y = 10

print(x is y)

**📌 Summary**

**सारांश**

**(English)**

*   Operators perform operations on values
*   Python supports many operator types
*   Operators are used in expressions and conditions

**(हिंदी – देवनागरी)**

*   ऑपरेटर्स वैल्यू पर ऑपरेशन करते हैं
*   पाइथन में कई प्रकार के ऑपरेटर्स होते हैं
*   ऑपरेटर्स कंडीशन और एक्सप्रेशन में उपयोग होते हैं

# 🐍 Python If–Else Statements

**🔹 What is If–Else?**

**(English)**  
If–else statements are used to make decisions in a program.  
They execute different blocks of code based on conditions.

**(हिंदी – देवनागरी)**  
If–else स्टेटमेंट्स का उपयोग प्रोग्राम में निर्णय लेने के लिए किया जाता है।  
कंडीशन के आधार पर अलग-अलग कोड ब्लॉक चलाए जाते हैं।

## 🔸 if Statement

**if स्टेटमेंट**

**(English)**  
The if statement executes a block of code when the condition is true.

**(हिंदी – देवनागरी)**  
if स्टेटमेंट तब कोड चलाता है जब कंडीशन सही होती है।

**Syntax:**

if condition:

statement

**Example:**

age = 18

if age >= 18:

print("You are eligible to vote")

## 🔸 if–else Statement

**if–else स्टेटमेंट**

**(English)**  
The else block executes when the if condition is false.

**(हिंदी – देवनागरी)**  
else ब्लॉक तब चलता है जब if कंडीशन गलत होती है।

**Example:**

num = 5

if num % 2 == 0:

print("Even number")

else:

print("Odd number")

## 🔸 if–elif–else Statement

**if–elif–else स्टेटमेंट**

**(English)**  
The elif keyword is used to check multiple conditions.

**(हिंदी – देवनागरी)**  
elif का उपयोग कई कंडीशन चेक करने के लिए किया जाता है।

**Example:**

marks = 75

if marks >= 90:

print("Grade A")

elif marks >= 60:

print("Grade B")

else:

print("Grade C")

## 📏 Nested if Statement

**नेस्टेड if स्टेटमेंट**

**(English)**  
An if statement inside another if statement is called nested if.

**(हिंदी – देवनागरी)**  
एक if के अंदर दूसरा if नेस्टेड if कहलाता है।

**Example:**

num = 10

if num > 0:

if num % 2 == 0:

print("Positive Even Number")

**⚠️ Important Rules**

**महत्वपूर्ण नियम**

**(English)**

*   Colon (:) is mandatory
*   Indentation is required
*   Conditions must return True or False

**(हिंदी – देवनागरी)**

*   कॉलन (:) अनिवार्य है
*   इंडेंटेशन ज़रूरी है
*   कंडीशन True या False होनी चाहिए

**📌 Summary**

**सारांश**

**(English)**

*   If–else is used for decision making
*   elif handles multiple conditions
*   Indentation is very important

**(हिंदी – देवनागरी)**

*   If–else निर्णय लेने के लिए उपयोग होता है
*   elif कई कंडीशन संभालता है
*   इंडेंटेशन बहुत ज़रूरी है

# 🐍 Python Loops

**🔹 What is a Loop?**

**(English)**  
A loop is used to execute a block of code repeatedly until a condition is satisfied.

**(हिंदी – देवनागरी)**  
लूप का उपयोग किसी कोड को बार-बार चलाने के लिए किया जाता है जब तक कंडीशन पूरी न हो जाए।

## 🔸 Types of Loops in Python

**Python में लूप्स के प्रकार**

1.  for loop
2.  while loop

### 1️⃣ for Loop

**for लूप**

**(English)**  
The for loop is used to iterate over a sequence such as a list, tuple, string, or range.

**(हिंदी – देवनागरी)**  
for लूप का उपयोग किसी सीक्वेंस (list, tuple, string, range) पर बार-बार चलने के लिए किया जाता है।

**Syntax:**

for variable in sequence:

statement

**Example: for loop with range**

for i in range(1, 6):

print(i)

**Example: for loop with list**

fruits = \["apple", "banana", "mango"\]

for fruit in fruits:

print(fruit)  

**🔹 Syntax**

for variable in sequence:

statement

**🔹 Example**

for i in range(1, 6):

print(i)

**🔹 Output**

1

2

3

4

5

### 2️⃣ while Loop

**while लूप**

**(English)**  
The while loop executes a block of code as long as the condition is true.

**(हिंदी – देवनागरी)**  
while लूप तब तक कोड चलाता है जब तक कंडीशन सही रहती है।

**Syntax:**

while condition:

statement

**Example:**

i = 1

while i <= 5:

print(i)

i += 1  
  
  
  
**🔹 Syntax**

while condition:

statement

**🔹 Example**

i = 1

while i <= 5:

print(i)

i += 1

### 🔁 Loop Control Statements

**लूप कंट्रोल स्टेटमेंट्स**

### 🔹 break Statement

**break स्टेटमेंट**

**(English)**  
break is used to exit the loop immediately.

**(हिंदी – देवनागरी)**  
break का उपयोग लूप को तुरंत रोकने के लिए किया जाता है।

for i in range(1, 10):

if i == 5:

break

print(i)

### 🔹 continue Statement

**continue स्टेटमेंट**

**(English)**  
continue skips the current iteration and moves to the next one.

**(हिंदी – देवनागरी)**  
continue वर्तमान iteration को छोड़कर अगली iteration पर चला जाता है।

for i in range(1, 6):

if i == 3:

continue

print(i)

### 🔹 pass Statement

**pass स्टेटमेंट**

**(English)**  
pass is used as a placeholder when no action is required.

**(हिंदी – देवनागरी)**  
pass का उपयोग तब किया जाता है जब कोई कोड नहीं लिखना हो।

for i in range(5):

pass

### ⚠️ Infinite Loop

**अनंत लूप**

**(English)**  
A loop that never ends is called an infinite loop.

**(हिंदी – देवनागरी)**  
जो लूप कभी समाप्त नहीं होता, उसे अनंत लूप कहते हैं।

\# Example (avoid running)

while True:

print("Hello")

**📌 Summary**

**सारांश**

**(English)**

*   Loops are used for repetition
*   for loop is used with sequences
*   while loop depends on conditions
*   break, continue, and pass control loops

**(हिंदी – देवनागरी)**

*   लूप्स दोहराव के लिए उपयोग होते हैं
*   for लूप सीक्वेंस के साथ प्रयोग होता है
*   while लूप कंडीशन पर निर्भर करता है
*   break, continue, pass लूप को नियंत्रित करते हैं

# 🐍 Python Functions

**🔹 What is a Function?**

**(English)**  
A function is a block of reusable code that performs a specific task.  
Functions help reduce code repetition and make programs easier to understand.

**(हिंदी – देवनागरी)**  
फ़ंक्शन पुनः उपयोग किए जाने वाला कोड का एक ब्लॉक होता है जो एक विशेष कार्य करता है।  
फ़ंक्शन कोड को दोहराने से बचाते हैं और प्रोग्राम को समझना आसान बनाते हैं।

## 🔸 Why Use Functions?

**(English)**

*   Improves code readability
*   Avoids repetition
*   Makes debugging easier

**(हिंदी – देवनागरी)**

*   कोड को पढ़ने योग्य बनाता है
*   कोड दोहराव से बचाता है
*   डिबगिंग आसान करता है

## 🔹 Defining a Function

**फ़ंक्शन बनाना**

**Syntax:**

def function\_name():

statements

**Example:**

def greet():

print("Hello, Welcome to Python")

## ▶️ Calling a Function

**फ़ंक्शन को कॉल करना**

greet()

## 🧾 Function with Parameters

**पैरामीटर के साथ फ़ंक्शन**

**(English)**  
Parameters are values passed to a function.

**(हिंदी – देवनागरी)**  
पैरामीटर वे वैल्यू होती हैं जो फ़ंक्शन को दी जाती हैं।

**Example:**

def add(a, b):

print(a + b)

add(10, 20)

## 🔁 Function with Return Value

**रिटर्न वैल्यू वाला फ़ंक्शन**

**(English)**  
The return statement sends a value back to the caller.

**(हिंदी – देवनागरी)**  
return स्टेटमेंट वैल्यू को वापस भेजता है।

def square(x):

return x \* x

result = square(5)

print(result)

## 🧮 Default Parameters

**डिफ़ॉल्ट पैरामीटर**

**(English)**  
Default parameters are used when no value is passed.

**(हिंदी – देवनागरी)**  
जब वैल्यू नहीं दी जाती तब डिफ़ॉल्ट पैरामीटर काम आते हैं।

def greet(name="User"):

print("Hello", name)

greet()

greet("Amit")

## 🔢 Keyword Arguments

**कीवर्ड आर्ग्युमेंट्स**

def student(name, age):

print(name, age)

student(age=20, name="Rahul")

## 🔁 Recursion

**रिकर्शन**

**(English)**  
A function calling itself is called recursion.

**(हिंदी – देवनागरी)**  
जब फ़ंक्शन खुद को कॉल करता है, उसे रिकर्शन कहते हैं।

def factorial(n):

if n == 1:

return 1

return n \* factorial(n-1)

**⚠️ Important Points**

**महत्वपूर्ण बातें**

**(English)**

*   Function name must be unique
*   Use return to get value
*   Indentation is mandatory

**(हिंदी – देवनागरी)**

*   फ़ंक्शन का नाम यूनिक होना चाहिए
*   वैल्यू पाने के लिए return का उपयोग करें
*   इंडेंटेशन ज़रूरी है

**📌 Summary**

**सारांश**

**(English)**

*   Functions make code reusable
*   Parameters pass data to functions
*   Return gives output from function

**(हिंदी – देवनागरी)**

*   फ़ंक्शन कोड को दोबारा उपयोग योग्य बनाते हैं
*   पैरामीटर डेटा भेजते हैं
*   रिटर्न आउटपुट देता है

# 🧵 Python Strings

**🔹 What is a String?**

**(English)**  
A string is a sequence of characters enclosed in single quotes ' ', double quotes " ", or triple quotes.

**(हिंदी – देवनागरी)**  
स्ट्रिंग अक्षरों (characters) का समूह होती है जिसे ' ', " " या ट्रिपल कोट्स में लिखा जाता है।

**Examples:**

name = "Python"

city = 'Delhi'

text = """This is Python"""

## 🔸 Accessing Characters in a String

**स्ट्रिंग के अक्षर एक्सेस करना**

**(English)**  
Each character in a string has an index starting from 0.

**(हिंदी – देवनागरी)**  
स्ट्रिंग के हर अक्षर का एक इंडेक्स होता है जो 0 से शुरू होता है।

word = "Python"

print(word\[0\]) # P

print(word\[3\]) # h

## 🔁 Negative Indexing

**नेगेटिव इंडेक्सिंग**

print(word\[-1\]) # n

print(word\[-2\]) # o

## ✂️ String Slicing

**स्ट्रिंग स्लाइसिंग**

**(English)**  
Slicing is used to get a part of a string.

**(हिंदी – देवनागरी)**  
स्लाइसिंग से स्ट्रिंग का एक हिस्सा निकाला जाता है।

text = "PythonProgramming"

print(text\[0:6\]) # Python

print(text\[6:\]) # Programming

print(text\[:6\]) # Python

## 🔄 String Concatenation

**स्ट्रिंग जोड़ना**

a = "Hello"

b = "Python"

print(a + " " + b)

## 🔢 String Length

**स्ट्रिंग की लंबाई**

msg = "Welcome"

print(len(msg))

## 🔠 String Methods

**स्ट्रिंग मेथड्स**

### 1️⃣ upper() / lower()

text = "Python"

print(text.upper())

print(text.lower())

### 2️⃣ strip()

**(English)**  
Removes spaces from both ends.

**(हिंदी – देवनागरी)**  
दोनों तरफ के स्पेस हटाता है।

name = " Rahul "

print(name.strip())

### 3️⃣ replace()

text = "I like Java"

print(text.replace("Java", "Python"))

### 4️⃣ split()

data = "Python is easy"

print(data.split())

### 5️⃣ find()

text = "Python"

print(text.find("t"))

### ❌ Strings are Immutable

**स्ट्रिंग बदल नहीं सकते**

**(English)**  
Strings cannot be changed after creation.

**(हिंदी – देवनागरी)**  
स्ट्रिंग बनने के बाद बदली नहीं जा सकती।

text = "Hello"

\# text\[0\] = "h" ❌ Error

## 🔁 Looping Through a String

**स्ट्रिंग पर लूप**

for char in "Python":

print(char)

**📌 Summary**

**सारांश**

**(English)**

*   Strings store text data
*   Indexing starts from 0
*   Strings are immutable
*   Many built-in methods are available

**(हिंदी – देवनागरी)**

*   स्ट्रिंग टेक्स्ट डेटा स्टोर करती है
*   इंडेक्स 0 से शुरू होता है
*   स्ट्रिंग बदली नहीं जा सकती
*   कई बिल्ट-इन मेथड्स होते हैं

# Data structures (lists, tuples, dictionaries, sets)

# 📋 Python Lists

**🔹 What is a List?**

**(English)**  
A list is a collection of ordered and changeable items.  
Lists allow duplicate values and are written using square brackets \[ \].

**(हिंदी – देवनागरी)**  
लिस्ट क्रमबद्ध (ordered) और बदली जा सकने वाली आइटम्स का संग्रह होती है।  
लिस्ट में डुप्लिकेट वैल्यू हो सकती हैं और इन्हें \[ \] में लिखा जाता है।

**Example:**

numbers = \[10, 20, 30, 40\]

names = \["Amit", "Rahul", "Neha"\]

mixed = \[1, "Python", 3.5\]

## 🔸 Accessing List Items

**लिस्ट के आइटम्स एक्सेस करना**

print(numbers\[0\])

print(names\[1\])

## 🔁 Negative Indexing

**नेगेटिव इंडेक्सिंग**

print(numbers\[-1\])

## ✂️ List Slicing

**लिस्ट स्लाइसिंग**

print(numbers\[1:3\])

## ✏️ Changing List Items

**लिस्ट आइटम बदलना**

**(English)**  
Lists are mutable, so items can be changed.

**(हिंदी – देवनागरी)**  
लिस्ट mutable minimizes; इसके आइटम बदले जा सकते हैं।

numbers\[1\] = 25

print(numbers)

## ➕ Adding Items to List

**लिस्ट में आइटम जोड़ना**

### 1️⃣ append()

numbers.append(50)

### 2️⃣ insert()

numbers.insert(1, 15)

## ➖ Removing Items from List

**लिस्ट से आइटम हटाना**

### 1️⃣ remove()

numbers.remove(30)

### 2️⃣ pop()

numbers.pop()

numbers.pop(1)

### 3️⃣ del

del numbers\[0\]

## 🔁 Loop Through a List

**लिस्ट पर लूप**

for item in names:

print(item)

## 🔢 List Length

**लिस्ट की लंबाई**

print(len(numbers))

## 🔠 List Methods

**लिस्ट मेथड्स**

nums = \[4, 1, 3, 2\]

nums.sort()

nums.reverse()

print(nums)

## 🔗 List Concatenation

**लिस्ट जोड़ना**

a = \[1, 2\]

b = \[3, 4\]

print(a + b)

## 🧬 Nested List

**नेस्टेड लिस्ट**

matrix = \[

\[1, 2\],

\[3, 4\]

\]

**⚠️ Important Points**

**महत्वपूर्ण बातें**

**(English)**

*   Lists are ordered
*   Lists are mutable
*   Allow duplicate values

**(हिंदी – देवनागरी)**

*   लिस्ट क्रमबद्ध होती है
*   लिस्ट बदली जा सकती है
*   डुप्लिकेट वैल्यू संभव है

**📌 Summary**

**सारांश**

**(English)**

*   Lists store multiple values
*   Items can be modified
*   Many built-in methods available

**(हिंदी – देवनागरी)**

*   लिस्ट कई वैल्यू स्टोर करती है
*   आइटम बदले जा सकते हैं
*   कई बिल्ट-इन मेथड्स होते हैं

# 📦 Python Tuples

**🔹 What is a Tuple?**

**(English)**  
A tuple is a collection of ordered and unchangeable items.  
Tuples allow duplicate values and are written using parentheses ( ).

**(हिंदी – देवनागरी)**  
ट्यूपल क्रमबद्ध (ordered) लेकिन अपरिवर्तनीय (unchangeable) आइटम्स का संग्रह होता है।  
ट्यूपल में डुप्लिकेट वैल्यू हो सकती हैं और इन्हें ( ) में लिखा जाता है।

**Example:**

data = (10, 20, 30)

names = ("Amit", "Rahul", "Neha")

single = (5,) # single-item tuple

## 🔸 Accessing Tuple Items

**ट्यूपल के आइटम्स एक्सेस करना**

print(data\[0\])

print(names\[1\])

## 🔁 Negative Indexing

**नेगेटिव इंडेक्सिंग**

print(data\[-1\])

## ✂️ Tuple Slicing

**ट्यूपल स्लाइसिंग**

print(data\[1:3\])

## ❌ Tuples are Immutable

**ट्यूपल बदले नहीं जा सकते**

**(English)**  
Tuple items cannot be changed after creation.

**(हिंदी – देवनागरी)**  
ट्यूपल बनने के बाद उसके आइटम बदले नहीं जा सकते।

\# data\[0\] = 100 ❌ Error

## 🔁 Loop Through a Tuple

**ट्यूपल पर लूप**

for item in data:

print(item)

## 🔢 Tuple Length

**ट्यूपल की लंबाई**

print(len(data))

## 🔠 Tuple Methods

**ट्यूपल मेथड्स**

nums = (1, 2, 3, 2, 4)

print(nums.count(2))

print(nums.index(3))

## 🔄 Tuple Packing & Unpacking

**ट्यूपल पैकिंग और अनपैकिंग**

student = ("Rahul", 20, "BCA")

name, age, course = student

print(name)

print(age)

print(course)

## 🔁 Convert Tuple to List

**ट्यूपल को लिस्ट में बदलना**

t = (1, 2, 3)

lst = list(t)

lst.append(4)

t = tuple(lst)

print(t)

### ⚠️ Tuple vs List

| List | Tuple |
| --- | --- |
| Mutable | Immutable |
| Uses [ ] | Uses ( ) |
| Slower | Faster |

**📌 Summary**

**सारांश**

**(English)**

*   Tuples are ordered and immutable
*   Faster than lists
*   Used for fixed data

**(हिंदी – देवनागरी)**

*   ट्यूपल क्रमबद्ध और अपरिवर्तनीय होते हैं
*   लिस्ट से तेज़ होते हैं
*   फिक्स्ड डेटा के लिए उपयोगी

# 🧺 Python Sets

**पाइथन सेट्स**

**🔹 What is a Set?**

**(English)**  
A set is an unordered collection of unique items.  
Sets do not allow duplicate values and are written using curly braces { }.

**(हिंदी – देवनागरी)**  
सेट यूनिक (अद्वितीय) आइटम्स का बिना क्रम (unordered) वाला संग्रह होता है।  
सेट में डुप्लिकेट वैल्यू नहीं होती और इन्हें { } में लिखा जाता है।

**Example:**

numbers = {10, 20, 30, 40}

names = {"Amit", "Rahul", "Neha"}

## 🔸 Set Characteristics

**सेट की विशेषताएँ**

**(English)**

*   Unordered
*   No duplicates
*   Mutable (items can be added or removed)

**(हिंदी – देवनागरी)**

*   बिना क्रम के
*   डुप्लिकेट नहीं
*   बदले जा सकते हैं

## ➕ Adding Items to Set

**सेट में आइटम जोड़ना**

numbers.add(50)

## ➖ Removing Items from Set

**सेट से आइटम हटाना**

numbers.remove(20)

numbers.discard(30)

## 🔁 Loop Through a Set

**सेट पर लूप**

for item in numbers:

print(item)

## 🔄 Set Operations

**सेट ऑपरेशन्स**

### 1️⃣ Union ( | )

a = {1, 2, 3}

b = {3, 4, 5}

print(a | b)

### 2️⃣ Intersection ( & )

print(a & b)

### 3️⃣ Difference ( - )

print(a - b)

### 4️⃣ Symmetric Difference ( ^ )

print(a ^ b)

## ❌ Set Indexing Not Allowed

**सेट में इंडेक्सिंग नहीं**

\# print(numbers\[0\]) ❌ Error

### 🔢 Set Length

**सेट की लंबाई**

print(len(numbers))

### 🧬 Frozen Set

**फ्रोजन सेट**

**(English)**  
A frozenset is immutable.

**(हिंदी – देवनागरी)**  
फ्रोजन सेट बदला नहीं जा सकता।

fs = frozenset(\[1, 2, 3\])

**⚠️ Important Points**

**महत्वपूर्ण बातें**

**(English)**

*   Sets store unique values
*   Order is not guaranteed
*   No indexing

**(हिंदी – देवनागरी)**

*   सेट यूनिक वैल्यू रखते हैं
*   क्रम निश्चित नहीं
*   इंडेक्सिंग नहीं होती

**📌 Summary**

**सारांश**

**(English)**

*   Sets remove duplicates
*   Useful for mathematical operations
*   Fast membership testing

**(हिंदी – देवनागरी)**

*   सेट डुप्लिकेट हटाते हैं
*   गणितीय ऑपरेशन में उपयोगी
*   तेज़ खोज के लिए अच्छे

# 📘 Python Dictionary

**पाइथन डिक्शनरी**

**🔹 What is a Dictionary?**

**(English)**  
A dictionary is a collection of key–value pairs.  
It is unordered, changeable, and does not allow duplicate keys.

**(हिंदी – देवनागरी)**  
डिक्शनरी key–value जोड़ों का संग्रह होती है।  
यह unordered होती है, बदली जा सकती है और duplicate keys की अनुमति नहीं देती।

**Example:**

student = {

"name": "Rahul",

"age": 20,

"course": "BCA"

}

## 🔸 Accessing Dictionary Values

**डिक्शनरी की वैल्यू एक्सेस करना**

print(student\["name"\])

print(student.get("age"))

## ✏️ Changing Dictionary Values

**डिक्शनरी की वैल्यू बदलना**

student\["age"\] = 21

## ➕ Adding New Key-Value

**नई key–value जोड़ना**

student\["city"\] = "Delhi"

## ➖ Removing Items from Dictionary

**डिक्शनरी से आइटम हटाना**

student.pop("course")

del student\["age"\]

## 🔁 Loop Through Dictionary

**डिक्शनरी पर लूप**

**Keys:**

for key in student:

print(key)

**Values:**

for value in student.values():

print(value)

**Key & Value both:**

for k, v in student.items():

print(k, v)

## 🔢 Dictionary Length

**डिक्शनरी की लंबाई**

print(len(student))

## 🔠 Dictionary Methods

**डिक्शनरी मेथड्स**

student.keys()

student.values()

student.items()

## 🧬 Nested Dictionary

**नेस्टेड डिक्शनरी**

students = {

1: {"name": "Amit", "age": 20},

2: {"name": "Neha", "age": 21}

}

## ❌ Duplicate Keys Not Allowed

**डुप्लिकेट key नहीं**

data = {"a": 1, "a": 2}

print(data) # last value will be used

**⚠️ Important Points**

**महत्वपूर्ण बातें**

**(English)**

*   Dictionary uses key–value pairs
*   Keys must be unique
*   Fast data lookup

**(हिंदी – देवनागरी)**

*   डिक्शनरी key–value पर काम करती है
*   key यूनिक होती है
*   डेटा खोज तेज़ होती है

**📌 Summary**

**सारांश**

**(English)**

*   Dictionary stores structured data
*   Values are accessed using keys
*   Very fast and flexible

**(हिंदी – देवनागरी)**

*   डिक्शनरी संरचित डेटा स्टोर करती है
*   key से वैल्यू मिलती है
*   तेज़ और लचीली होती है

# 📦 Python Modules & Import

**📌 What is a Module?**

**(English)**  
A module is a file that contains Python code such as functions, variables, or classes.  
Modules help in organizing code and reusing it.

**(हिंदी – देवनागरी)**  
मॉड्यूल एक Python फ़ाइल होती है जिसमें फ़ंक्शन, वैरिएबल या क्लास होते हैं।  
मॉड्यूल कोड को व्यवस्थित और पुनः उपयोग योग्य बनाते हैं।

## 🔹 Why Use Modules?

**(English)**

*   Code reusability
*   Better organization
*   Easy maintenance

**(हिंदी)**

*   कोड दोबारा उपयोग
*   बेहतर संरचना
*   आसान रखरखाव

## 🔹 Types of Modules

1️⃣ Built-in modules  
2️⃣ User-defined modules  
3️⃣ External (third-party) modules

### 🟢 1️⃣ Built-in Modules

**इनबिल्ट मॉड्यूल**

Python ke saath pehle se available hote hain.

**Example: math module**

import math

print(math.sqrt(16))

print(math.factorial(5))

**Example: random module**

import random

print(random.randint(1, 10))

**Example: datetime module**

import datetime

today = datetime.date.today()

print(today)

### 🟡 2️⃣ import Statement

**import स्टेटमेंट**

**Basic import**

import math

print(math.pi)

**import with alias**

import math as m

print(m.pi)

### 🔵 3️⃣ from ... import

**from ... import**

from math import sqrt, pi

print(sqrt(25))

print(pi)

**Import everything (not recommended)**

from math import \*

⚠️ **Avoid** — namespace confusion hota hai.

### 🟣 4️⃣ User-Defined Module

**खुद का मॉड्यूल बनाना**

**Step 1: Create a file**

**mymodule.py**

def add(a, b):

return a + b

def sub(a, b):

return a - b

**Step 2: Import in another file**

import mymodule

print(mymodule.add(10, 5))

print(mymodule.sub(10, 5))  

**Step 1: Create module file**

**file:** mymath.py

def add(a, b):

return a + b

def sub(a, b):

return a - b

**Step 2: Import module**

import mymath

print(mymath.add(10, 5))

### 🔁 5️⃣ dir() Function

**dir() फ़ंक्शन**

**(English)**  
Shows all members of a module.

**(हिंदी)**  
मॉड्यूल के सभी नाम दिखाता है।

import math

print(dir(math))

### 🔐 6️⃣ name == "main"

**name मैजिक**

**(English)**  
Runs code only when the file is executed directly.

**(हिंदी)**  
कोड सिर्फ तब चलेगा जब फ़ाइल सीधे रन हो।

def show():

print("Hello")

if \_\_name\_\_ == "\_\_main\_\_":

show()

### 🌐 7️⃣ External Modules (pip)

**थर्ड-पार्टी मॉड्यूल**

Install using pip:

pip install numpy

Use in Python:

import numpy

**⚠️ Common Mistakes**

❌ Wrong file name  
❌ Forgetting .py  
❌ Circular imports  
❌ Using from module import \*

**📌 Modules Summary**

**(English)**

*   Modules organize code
*   import is used to load modules
*   Built-in, user-defined, and external modules exist

**(हिंदी)**

*   मॉड्यूल कोड व्यवस्थित करते हैं
*   import से मॉड्यूल लोड होते हैं
*   तीन प्रकार के मॉड्यूल होते हैं

# 📦 Python Packages & pip

## 📌 What is a Package?

**(English)**  
A package is a collection of related modules organized in directories.  
Packages help manage large projects by grouping modules together.

**(हिंदी – देवनागरी)**  
पैकेज संबंधित मॉड्यूल्स का संग्रह होता है जो डायरेक्टरी में व्यवस्थित रहता है।  
पैकेज बड़े प्रोजेक्ट को व्यवस्थित करने में मदद करते हैं।

## 🔹 Difference: Module vs Package

| Module | Package |
| --- | --- |
| Single .py file | Folder of modules |
| Small code | Large codebase |
| Example: math.py | Example: numpy |

## 📂 Package Structure

**Example folder structure:**

mypackage/

│

├── \_\_init\_\_.py

├── mathops.py

├── stringops.py

## 🟢 init.py File

**(English)**  
\_\_init\_\_.py tells Python that the directory is a package.

**(हिंदी)**  
\_\_init\_\_.py Python को बताता है कि यह फ़ोल्डर एक पैकेज है।

Note: New Python versions me optional hai, but **recommended**.

## 🔁 Import from Package

**Import whole module**

import mypackage.mathops

mypackage.mathops.add(10, 5)

**Import specific function**

from mypackage.mathops import add

print(add(10, 5))

**Import multiple modules**

from mypackage import mathops, stringops

# 🌐 What is pip?

**(English)**  
pip is Python’s package manager used to install external libraries.

**(हिंदी)**  
pip Python का पैकेज मैनेजर है जिससे बाहरी लाइब्रेरी इंस्टॉल की जाती हैं।

## 🔧 Common pip Commands

**Install a package**

pip install numpy

**Install specific version**

pip install numpy==1.26.0

**Upgrade a package**

pip install --upgrade pip

**Uninstall a package**

pip uninstall numpy

**List installed packages**

pip list

## 📌 Popular Python Packages

| Package | Use |
| --- | --- |
| numpy | Numerical computing |
| pandas | Data analysis |
| matplotlib | Data visualization |
| requests | HTTP requests |
| flask | Web development |

## 🧪 Virtual Environment (Basic Idea)

**(English)**  
A virtual environment isolates project dependencies.

**(हिंदी)**  
वर्चुअल एनवायरनमेंट प्रोजेक्ट की लाइब्रेरी अलग रखता है।

**Create virtual environment**

python -m venv myenv

**Activate (Windows)**

myenv\\Scripts\\activate

**Activate (Linux/Mac)**

source myenv/bin/activate

**⚠️ Common Mistakes**

❌ Using system Python without venv  
❌ Installing packages globally  
❌ Wrong Python version pip  
❌ Forgetting to activate venv

**📌 Packages & pip Summary**

**(English)**

*   Packages organize multiple modules
*   pip installs external libraries
*   Virtual environments avoid conflicts

**(हिंदी)**

*   पैकेज कई मॉड्यूल व्यवस्थित करते हैं
*   pip बाहरी लाइब्रेरी इंस्टॉल करता है
*   वर्चुअल एनवायरनमेंट टकराव से बचाता है

# 🧱 Python OOP – Object Oriented Programming

**📌 What is OOP?**

**(English)**  
OOP is a programming approach where programs are built using objects and classes.

**(हिंदी – देवनागरी)**  
OOP एक प्रोग्रामिंग तरीका है जिसमें प्रोग्राम क्लास और ऑब्जेक्ट से बनाए जाते हैं।

## 🔑 Core Concepts of OOP

1️⃣ Class  
2️⃣ Object  
3️⃣ Encapsulation  
4️⃣ Inheritance  
5️⃣ Polymorphism  
6️⃣ Abstraction

### 🟢 1️⃣ Class

**क्लास क्या है?**

**(English)**  
A class is a blueprint for creating objects.

**(हिंदी)**  
क्लास ऑब्जेक्ट बनाने का खाका (blueprint) होती है।

**Syntax:**

class Student:

pass

### 🔵 2️⃣ Object

**ऑब्जेक्ट क्या है?**

**(English)**  
An object is an instance of a class.

**(हिंदी)**  
ऑब्जेक्ट क्लास का उदाहरण होता है।

**Example:**

s1 = Student()

### 🟣 3️⃣ init() Constructor

**कंस्ट्रक्टर**

**(English)**  
\_\_init\_\_() runs automatically when an object is created.

**(हिंदी)**  
\_\_init\_\_() ऑब्जेक्ट बनते ही अपने आप चलता है।

class Student:

def \_\_init\_\_(self, name, age):

self.name = name

self.age = age

s1 = Student("Rahul", 20)

print(s1.name)

print(s1.age)

**🔸 self Keyword**

**self क्या है?**

**(English)**  
self refers to the current object.

**(हिंदी)**  
self वर्तमान ऑब्जेक्ट को दर्शाता है।

### 🟠 4️⃣ Class Variables & Instance Variables

class Student:

college = "ABC College" # class variable

def \_\_init\_\_(self, name):

self.name = name # instance variable

### 🟡 5️⃣ Methods

**मेथड्स**

class Student:

def show(self):

print("Hello Student")

### 🟢 6️⃣ Inheritance

**इनहेरिटेंस**

**(English)**  
Inheritance allows a class to acquire properties of another class.

**(हिंदी)**  
इनहेरिटेंस से एक क्लास दूसरी क्लास की विशेषताएँ ले सकती है।

**Example:**

class Parent:

def show(self):

print("Parent class")

class Child(Parent):

def display(self):

print("Child class")

obj = Child()

obj.show()

obj.display()

### 🔵 Types of Inheritance (Basics)

*   Single
*   Multilevel
*   Multiple

### 🟣 7️⃣ Polymorphism

**पॉलीमॉर्फ़िज़्म**

**(English)**  
Same method name, different behavior.

**(हिंदी)**  
एक ही नाम, अलग व्यवहार।

**Example:**

class A:

def show(self):

print("Class A")

class B(A):

def show(self):

print("Class B")

obj = B()

obj.show()

### 🟠 8️⃣ Encapsulation

**एनकैप्सुलेशन**

**(English)**  
Wrapping data and methods together.

**(हिंदी)**  
डेटा और मेथड को एक साथ बाँधना।

class User:

def \_\_init\_\_(self, password):

self.\_\_password = password

**📌 OOP Summary**

**(English)**

*   Class is a blueprint
*   Object is instance
*   Inheritance reuses code
*   Polymorphism provides flexibility

**(हिंदी)**

*   क्लास खाका है
*   ऑब्जेक्ट उदाहरण है
*   इनहेरिटेंस कोड दोहराव कम करता है
*   पॉलीमॉर्फ़िज़्म लचीलापन देता है

# 📂 Python File Handling & Exceptions

## 📌 What is File Handling?

**(English)**  
File handling allows Python to read from and write data to files stored on disk.

**(हिंदी – देवनागरी)**  
फ़ाइल हैंडलिंग Python को डिस्क पर मौजूद फ़ाइलों से डेटा पढ़ने और लिखने की सुविधा देती है।

## 🔹 Types of Files

**(English)**

*   Text files (.txt)
*   Binary files (.jpg, .pdf)

**(हिंदी)**

*   टेक्स्ट फ़ाइल
*   बाइनरी फ़ाइल

## 🟢 open() Function

**फ़ाइल खोलना**

**Syntax:**

file = open("filename", "mode")

## 🔹 File Modes

| Mode | Meaning |
| --- | --- |
| r | Read |
| w | Write (overwrite) |
| a | Append |
| x | Create |
| rb | Read binary |
| wb | Write binary |

## 📖 Reading a File

**फ़ाइल पढ़ना**

**read()**

file = open("data.txt", "r")

content = file.read()

print(content)

file.close()

## readline()

file = open("data.txt", "r")

print(file.readline())

file.close()

## readlines()

file = open("data.txt", "r")

print(file.readlines())

file.close()

## ✍️ Writing to a File

**फ़ाइल में लिखना**

file = open("data.txt", "w")

file.write("Hello Python")

file.close()

## ➕ Append Mode

**डेटा जोड़ना**

file = open("data.txt", "a")

file.write("\\nNew Line Added")

file.close()

## 🔒 with Statement (Best Practice)

**with स्टेटमेंट**

**(English)**  
Automatically closes the file.

**(हिंदी)**  
अपने आप फ़ाइल बंद कर देता है।

with open("data.txt", "r") as file:

print(file.read())

## ⚠️ What is an Exception?

**(English)**  
An exception is an error that occurs during program execution.

**(हिंदी)**  
एक्सेप्शन वह गलती है जो प्रोग्राम चलते समय होती है।

**🔥 Common Exceptions**

*   ZeroDivisionError
*   FileNotFoundError
*   ValueError
*   TypeError

## 🛡️ try – except

**एरर हैंडलिंग**

try:

x = int(input("Enter number: "))

print(10 / x)

except ZeroDivisionError:

print("Cannot divide by zero")

except ValueError:

print("Invalid input")

## 🧹 finally Block

**finally ब्लॉक**

**(English)**  
Always executes, error ho ya na ho.

**(हिंदी)**  
हमेशा चलेगा, चाहे एरर आए या नहीं।

try:

file = open("data.txt", "r")

print(file.read())

except FileNotFoundError:

print("File not found")

finally:

print("Program finished")

## 🚨 raise Keyword

**कस्टम एक्सेप्शन**

age = -5

if age < 0:

raise ValueError("Age cannot be negative")

## 📌 File Handling + Exception Summary

**(English)**

*   Files are opened using open()
*   Always close files or use with
*   try–except prevents program crash

**(हिंदी)**

*   फ़ाइल open() से खुलती है
*   with से फ़ाइल अपने आप बंद होती है
*   try–except से प्रोग्राम क्रैश नहीं होता

# 📚 Python Libraries

## 📌 What is a Library?

**(English)**  
A library is a collection of pre-written code that helps perform complex tasks easily.

**(हिंदी – देवनागरी)**  
लाइब्रेरी पहले से लिखा हुआ कोड होता है जिससे मुश्किल काम आसानी से हो जाता है।

**🔹 Libraries We Will Cover**

1️⃣ NumPy  
2️⃣ Pandas  
3️⃣ Matplotlib

### 🧮 1️⃣ NumPy

**न्यूमेरिकल पाइथन**

**📌 What is NumPy?**

**(English)**  
NumPy is used for numerical computations and working with arrays.

**(हिंदी)**  
NumPy संख्यात्मक गणनाओं और array पर काम करने के लिए उपयोग होती है।

**Install NumPy**

pip install numpy

**Import NumPy**

import numpy as np

**Creating an Array**

import numpy as np

arr = np.array(\[1, 2, 3, 4\])

print(arr)

**NumPy Operations**

print(arr + 2)

print(arr \* 2)

**2D Array**

matrix = np.array(\[\[1, 2\], \[3, 4\]\])

print(matrix)

### 🐼 2️⃣ Pandas

**डेटा एनालिसिस लाइब्रेरी**

**📌 What is Pandas?**

**(English)**  
Pandas is used for data analysis and handling structured data like tables.

**(हिंदी)**  
Pandas टेबल जैसे डेटा को संभालने और विश्लेषण के लिए उपयोग होती है।

**Install Pandas**

pip install pandas

**Import Pandas**

import pandas as pd

**Create DataFrame**

data = {

"Name": \["Amit", "Rahul", "Neha"\],

"Age": \[20, 21, 22\]

}

df = pd.DataFrame(data)

print(df)

**Read CSV File**

df = pd.read\_csv("data.csv")

print(df.head())

**Basic Pandas Functions**

df.info()

df.describe()

### 📊 3️⃣ Matplotlib

**डेटा विज़ुअलाइज़ेशन**

**📌 What is Matplotlib?**

**(English)**  
Matplotlib is used to create graphs and charts.

**(हिंदी)**  
Matplotlib ग्राफ और चार्ट बनाने के लिए उपयोग होती है।

**Install Matplotlib**

pip install matplotlib

**Import Matplotlib**

import matplotlib.pyplot as plt

### Line Plot Example

x = \[1, 2, 3, 4\]

y = \[10, 20, 25, 30\]

plt.plot(x, y)

plt.xlabel("X Axis")

plt.ylabel("Y Axis")

plt.title("Simple Line Graph")

plt.show()

### Bar Chart Example

names = \["A", "B", "C"\]

marks = \[70, 80, 90\]

plt.bar(names, marks)

plt.show()

**⚠️ Common Mistakes**

❌ Forgetting to install library  
❌ Wrong import name  
❌ File path error in Pandas  
❌ Not calling plt.show()

**📌 Libraries Summary**

**(English)**

*   NumPy → numerical data
*   Pandas → table data
*   Matplotlib → visualization

**(हिंदी)**

*   NumPy → संख्यात्मक डेटा
*   Pandas → टेबल डेटा
*   Matplotlib → ग्राफ
