<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Python Basics</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            background-color: #f5f7fa;
            color: #333;
            line-height: 1.6;
        }
        h1 {
            text-align: center;
            color: #2c3e50;
        }
        h2 {
            color: #1a73e8;
            margin-top: 30px;
        }
        p {
            margin: 8px 0;
        }
        ul {
            margin-left: 20px;
        }
        code {
            background: #eef;
            padding: 4px 6px;
            border-radius: 4px;
        }
        pre {
            background: #272822;
            color: #f8f8f2;
            padding: 12px;
            border-radius: 6px;
            overflow-x: auto;
        }
        .container {
            max-width: 900px;
            margin: auto;
            background: #fff;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
    </style>
</head>
<body>

<div class="container">
    <h1>🐍 Python Basics</h1>
    <p>This page covers the fundamental concepts of Python programming for beginners.</p>

    <h2>1. Variables</h2>
    <p>Variables are used to store values.</p>
    <pre>
x = 10
name = "Python"
price = 99.99
    </pre>

    <h2>2. Data Types</h2>
    <p>Common built-in data types in Python:</p>
    <ul>
        <li><b>int</b> – 10</li>
        <li><b>float</b> – 3.14</li>
        <li><b>string</b> – "Hello"</li>
        <li><b>boolean</b> – True / False</li>
    </ul>
    <pre>
x = 10
print(type(x))
    </pre>

    <h2>3. Operators</h2>
    <p><b>Arithmetic Operators:</b> +  -  *  /  %</p>
    <p><b>Relational Operators:</b> ==  !=  >  <</p>
    <p><b>Logical Operators:</b> and  or  not</p>
    <pre>
a = 10
b = 3
print(a + b)
    </pre>

    <h2>4. Libraries</h2>
    <p>Libraries are collections of reusable code.</p>
    <ul>
        <li>math</li>
        <li>random</li>
        <li>datetime</li>
    </ul>
    <pre>
import math
print(math.sqrt(16))
    </pre>

    <h2>5. Built-in Functions</h2>
    <ul>
        <li>print()</li>
        <li>input()</li>
        <li>len()</li>
        <li>type()</li>
    </ul>
    <pre>
numbers = [1, 2, 3]
print(len(numbers))
    </pre>

    <h2>6. String</h2>
    <p>Strings store text data.</p>
    <pre>
text = "Python"
print(text.upper())
    </pre>

    <h2>7. List</h2>
    <p>Lists are ordered and mutable.</p>
    <pre>
fruits = ["apple", "banana", "cherry"]
fruits.append("orange")
    </pre>

    <h2>8. Tuple</h2>
    <p>Tuples are ordered and immutable.</p>
    <pre>
colors = ("red", "green", "blue")
    </pre>

    <h2>9. Dictionary</h2>
    <p>Dictionaries store data in key-value pairs.</p>
    <pre>
student = {
    "name": "Anish",
    "age": 21
}
print(student["name"])
    </pre>

    <p><b>🎯 Purpose:</b> Learn Python basics and practice core concepts.</p>
</div>

</body>
</html>

