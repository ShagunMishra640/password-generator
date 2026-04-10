# Password Generator (React)

A customizable Password Generator built using React that allows users to create strong and secure passwords with different options like length, numbers, and special characters.

---

##  Features

- Adjustable password length (6 to 100)
- Option to include Alphabets
- Option to include Numbers
- Option to include Special Characters
- One-click Copy to Clipboard
- Real-time password generation
- Responsive and user-friendly UI

---

##  Built With

- React (Functional Components)
- JavaScript (ES6+)
- CSS

### React Hooks Used:
- useState
- useCallback
- useEffect
- useRef

---



##  How It Works

- User selects password length using a range slider
- User can toggle options:
  - Include Numbers
  - Include Special Characters
- Password is generated dynamically using useCallback
- useEffect updates the password automatically when dependencies change
- useRef is used to copy the generated password to clipboard

---

##  Project Structure

src/
│
├── App.jsx
├── index.jsx
└── styles.css

---

##  Installation & Setup

1. Clone the repository:
git clone https://github.com/your-username/password-generator.git

2. Navigate to project folder:
cd password-generator

3. Install dependencies:
npm install

4. Start the app:
npm start

---

##  Future Improvements

- Dark / Light mode toggle
- Multi-language support
- Password strength indicator
- Improved mobile UI

---

##  Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

##  License

This project is licensed under the MIT License.

---

##  Author

Made by Shagun Kumar Mishra
