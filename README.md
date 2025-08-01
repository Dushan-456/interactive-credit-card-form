# Interactive Credit Card Details Form

This is a React-based interactive credit card form that dynamically updates and visually displays user input for card number, holder name, expiry date, and CVV. The card flips to show the CVV on the back when focused.

## 🧩 Features

- Live card preview with animation and 3D flip effect for CVV.
- Auto-formatting of credit card number and expiry date.
- Dynamic detection of Visa or MasterCard logos.
- Responsive design with Tailwind CSS.
- User-friendly form validation and layout.

## 📸 Demo

![Demo Screenshot](./src/assets/preview/interactive-credit-card-form.gif)

## 🚀 Getting Started

### Prerequisites

- Node.js and npm installed

### Installation

```bash
git clone https://github.com/Dushan-456/interactive-credit-card-form.git
cd interactive-credit-card-form
npm install
npm run dev
```

> Make sure to add the Visa, Mastercard, and a default black card image in the `./assets` folder as:
> - `visa.png`
> - `master.png`
> - `black-card.png`

### File Structure

```
.
├── public/
├── src/
│   ├── assets/
│   │   ├── visa.png
│   │   ├── master.png
│   │   └── black-card.png
│   ├── index.css
│   └── App.jsx
├── package.json
└── README.md
```

## 🛠 Technologies Used

- React
- Tailwind CSS
- JavaScript (ES6+)
- CSS 3D transforms

## 💡 Future Improvements

- Add real-time validation for card fields.
- Add support for more card types (AmEx, Discover).
- Mobile-friendly keyboard enhancements.

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).