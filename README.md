# Bill-Calculator-Project2
# 💰 Bill Calculator Challenge #2
A simple JavaScript exercise that calculates tips and total bills using functions and arrays.

## 📌 Rules
- If the bill is between **50 and 300**, the tip is **15%**
- Otherwise, the tip is **20%**

## 🛠️ Technologies
- Javascript (ES6)

📂 Code
javascript
function calcTip(bill) {
  return bill >= 50 && bill <= 300 ? bill * 0.15 : bill * 0.2;
}

const bills = [125, 555, 44];

const tips = [
  calcTip(bills[0]),
  calcTip(bills[1]),
  calcTip(bills[2])
];

const totals = [
  bills[0] + tips[0],
  bills[1] + tips[1],
  bills[2] + tips[2]
];

console.log(bills);
console.log(tips);
console.log(totals);

## ✅ Output

text
Bills:
[125, 555, 44]

Tips:
[18.75, 111, 8.8]

Totals:
[143.75, 666, 52.8]
`

## 🎯 Concepts Practiced

- Functions
- Function Return Values
- Arrays
- Arrays Indxing
- Ternary Operator
- Conditional Logic

## 👨‍💻 Author

Darwin Surya Pangestu

Learning JavaScript fundamentals through coding challenges.
- Arrays Indexing
- Ternary Operator
- Conditional Logic
- Array Indexing
- Ternary Operator
- Conditional Logic
