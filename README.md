# React Card Components Project

This is a basic React application built as part of an assignment to demonstrate component reuse and props. The project displays three reusable `Card` components with dynamic content passed via props.

## 🧠 Concepts Practiced

- Functional components in React
- Reusing components
- Passing data via `props`
- Basic CSS styling with className
- Layout using Flexbox

  Screenshot:
<img width="1279" height="633" alt="react_cards_beginner" src="https://github.com/user-attachments/assets/0f098c1b-d746-4cb3-8438-1a104484cad3" />

## 📁 Project Structure

my-react-app/
│
├── src/
│ ├── App.js # Main component rendering 3 Cards
│ ├── Card.js # Reusable Card component
│ ├── App.css # Styling for layout and cards
│ └── index.js # React entry point
│
├── public/
│ └── index.html
│
├── package.json
├── README.md
└── ...

markdown
Copy
Edit

## 🚀 How to Run

1. Make sure Node.js and npm are installed.
2. Clone the repository or open the project in your lab environment.
3. Open the terminal and run:

```bash
npm install
npm start
Open http://localhost:3000 in your browser.

📸 Output
You will see three styled card components with different h2 and h3 content stacked vertically in the center of the screen.

🧾 Example Props
jsx
Copy
Edit
<Card h2="First card's h2" h3="First card's h3" />
<Card h2="Second card's h2" h3="Second card's h3" />
<Card h2="Third card's h2" h3="Third card's h3" />
🎨 Styling
Cards are styled with borders, padding, and centered using Flexbox. The .card class handles the layout and appearance of each card.

Feel free to modify or expand this project as you explore more features in React!
