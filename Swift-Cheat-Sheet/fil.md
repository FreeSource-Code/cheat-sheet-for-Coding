📝 Swift Cheat Sheet (Basics)
```
✅ Variables & Constants
swift
Copy
Edit
var name = "Ishan"       // Mutable variable
let age = 21             // Immutable constant
```
```
🔢 Data Types
swift
Copy
Edit
let myInt: Int = 5
let myDouble: Double = 5.99
let myBool: Bool = true
let myString: String = "Hello"
```
```
🔁 String Interpolation
swift
Copy
Edit
let greeting = "Hello, \(name)"
```
```
🔀 Operators
swift
Copy
Edit
let sum = 5 + 3
let isEqual = (5 == 3) // false
```
```
📦 Arrays & Dictionaries
swift
Copy
Edit
// Array
var colors = ["red", "blue", "green"]
colors.append("yellow")

// Dictionary
var person = ["name": "Ishan", "age": "21"]
print(person["name"] ?? "")
```
```
🔁 Loops
swift
Copy
Edit
// For-in loop
for color in colors {
    print(color)
}

// While loop
var i = 0
while i < 3 {
    print(i)
    i += 1
}
```
```
🎯 Conditional Statements
swift
Copy
Edit
let score = 85
if score >= 90 {
    print("A")
} else if score >= 80 {
    print("B")
} else {
    print("C")
}
```
```
🔧 Functions
swift
Copy
Edit
func greet(name: String) -> String {
    return "Hello, \(name)!"
}
print(greet(name: "Ishan"))
```
```
📦 Optionals
swift
Copy
Edit
var optionalName: String? = "Ishan"
if let name = optionalName {
    print("Name is \(name)")
}
```
```
🧱 Classes & Structs
swift
Copy
Edit
// Struct
struct Car {
    var model: String
    func drive() {
        print("Driving \(model)")
    }
}

// Class
class Animal {
    var name: String
    init(name: String) {
        self.name = name
    }
    func speak() {
        print("\(name) makes a sound")
    }
}
```
```
🧰 Closures
swift
Copy
Edit
let multiply = { (a: Int, b: Int) -> Int in
    return a * b
}
print(multiply(2, 3))
```
