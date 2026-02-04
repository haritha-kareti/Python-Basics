<h1>🐍 Python Basics</h1>

<p>
This section explains <b>Python basic concepts</b> in a clear and beginner-friendly way.
</p>

<hr>

<h2>1️⃣ Variables</h2>
<p>
Variables are used to store data values in Python.
</p>

<pre>
x = 10
name = "Python"
price = 99.50
</pre>

<p>
<b>Rules:</b>
<ul>
  <li>Must start with a letter or underscore (_)</li>
  <li>Cannot start with a number</li>
  <li>Case-sensitive</li>
</ul>
</p>

<img src="images/variables.png" alt="Variables in Python" width="500">

<hr>

<h2>2️⃣ Data Types</h2>
<p>
Data types define the type of value a variable holds.
</p>

<table>
  <tr>
    <th>Data Type</th>
    <th>Description</th>
    <th>Example</th>
  </tr>
  <tr>
    <td>int</td>
    <td>Integer numbers</td>
    <td>10</td>
  </tr>
  <tr>
    <td>float</td>
    <td>Decimal numbers</td>
    <td>3.14</td>
  </tr>
  <tr>
    <td>str</td>
    <td>Text data</td>
    <td>"Hello"</td>
  </tr>
  <tr>
    <td>bool</td>
    <td>True / False</td>
    <td>True</td>
  </tr>
</table>

<pre>
x = 10
print(type(x))
</pre>

<img src="images/data_types.png" alt="Python Data Types" width="500">

<hr>

<h2>3️⃣ Operators</h2>

<p><b>Arithmetic Operators:</b> +  -  *  /  %  //  **</p>
<p><b>Relational Operators:</b> ==  !=  >  <  >=  <=</p>
<p><b>Logical Operators:</b> and  or  not</p>

<pre>
a = 10
b = 3
print(a + b)
</pre>

<img src="images/operators.png" alt="Python Operators" width="500">

<hr>

<h2>4️⃣ Library</h2>
<p>
A library is a collection of pre-written code used to perform common tasks.
</p>

<ul>
  <li>math</li>
  <li>random</li>
  <li>datetime</li>
</ul>

<pre>
import math
print(math.sqrt(16))
</pre>

<img src="images/library.png" alt="Python Library" width="500">

<hr>

<h2>5️⃣ Built-in Functions</h2>
<p>
Built-in functions are functions already available in Python.
</p>

<ul>
  <li>print()</li>
  <li>input()</li>
  <li>len()</li>
  <li>type()</li>
  <li>sum()</li>
</ul>

<pre>
numbers = [1, 2, 3, 4]
print(len(numbers))
</pre>

<img src="images/builtin_functions.png" alt="Built-in Functions" width="500">

<hr>

<h2>6️⃣ String</h2>
<p>
A string is a sequence of characters enclosed in quotes.
</p>

<pre>
text = "Python"
print(text.upper())
print(text[0:3])
</pre>

<img src="images/string.png" alt="Python String" width="500">

<hr>

<h2>7️⃣ List</h2>
<p>
A list is an ordered and mutable collection.
</p>

<pre>
fruits = ["apple", "banana", "cherry"]
fruits.append("orange")
print(fruits)
</pre>

<img src="images/list.png" alt="Python List" width="500">

<hr>

<h2>8️⃣ Tuple</h2>
<p>
A tuple is an ordered but immutable collection.
</p>

<pre>
colors = ("red", "green", "blue")
print(colors)
</pre>

<img src="images/tuple.png" alt="Python Tuple" width="500">

<hr>

<h2>9️⃣ Dictionary</h2>
<p>
A dictionary stores data in key-value pairs.
</p>

<pre>
student = {
  "name": "Anish",
  "age": 21,
  "course": "Python"
}
print(student["name"])
</pre>

<img src="images/dictionary.png" alt="Python Dictionary" width="500">

<hr>

<h3>🎯 Purpose</h3>
<ul>
  <li>Learn Python from scratch</li>
  <li>Understand concepts clearly</li>
  <li>Useful for exams and interviews</li>
</ul>

<p><b>⭐ If you found this helpful, give the repository a star!</b></p>
