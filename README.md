# 📏 IMC Calculator JS

This is a simple **BMI (IMC)** calculator built with **HTML, CSS, and Vanilla JavaScript**.  
It helps the user calculate their **Body Mass Index (IMC)** based on their height and weight and displays the result along with the classification table.

---

## 🚀 Features

✅ Input fields for **height** and **weight**  
✅ **Input validation**: only numbers and commas allowed  
✅ BMI calculation with **dynamic classification**  
✅ **Automatically generated** BMI classification table  
✅ Clear input fields button  
✅ Reset and recalculate option  
✅ Clean and organized **project structure**

---

## ⚙️ How it works

**Main flow:**

1. **Data table:**  
   - All BMI ranges and categories are stored in an array of objects (`data`).
   - Each object contains `min`, `max`, `classification`, `info`, and `obesity`.

2. **Dynamic table creation:**  
   - The classification table is built dynamically using `createElement`, `innerText` and `appendChild`.

3. **Input validation:**  
   - An `input` event listener ensures only valid numbers and commas are accepted in the form.

4. **Calculation:**  
   - BMI = weight / (height * height)  
   - The result is matched with the corresponding category.

5. **Display:**  
   - Shows the BMI value and its classification with color highlights.
   - User can clear inputs or go back to recalculate.

---

## 🗂️ Project structure

📁 imc-calculator-js/
├─ 📁 css/ → Contains the CSS styles (e.g., style.css)
├─ 📁 js/ → Contains the JavaScript logic (e.g., script.js)
└─ index.html → Main HTML file

yaml
Copiar
Editar

---

## 📌 Technologies Used

- **HTML5**
- **CSS3**
- **Vanilla JavaScript**

---

## 💡 What I learned

✅ Manipulating the DOM with `createElement`, `innerText`, `appendChild`  
✅ Using `classList.add` to dynamically apply CSS classes  
✅ Looping through data with `forEach`  
✅ Validating inputs using regular expressions  
✅ Building a clear file and folder structure for small web projects

---

## ⚡ How to run locally

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/imc-calculator-js
Open index.html in your browser.

Enter your height (in meters) and weight (in kilograms).

Click Calculate to see your BMI result!

📄 License
This project is open source and free to use.

✨ Author
Made with 💙 by Matheus Pires
