# React Accordion Component

A simple, reusable React accordion component that displays a list of items. Only one accordion item can be open at a time, ensuring a clean and intuitive user experience.

## Features

- Expand/collapse functionality for FAQ-style sections.
- Ensures only one item is open at a time.
- Dynamic rendering based on provided data.
- Fully customizable via CSS.
- Accessible with keyboard navigation support (optional improvement).

---

## Screenshot
![Screenshot 2025-01-26 170338](https://github.com/user-attachments/assets/08e35e67-532a-4567-bfa6-e5067bd2cf43)


---

## Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/react-accordion.git
   cd react-accordion
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:

   ```bash
   npm start
   ```

4. Open the app in your browser at [http://localhost:3000](http://localhost:3000).

---

## Usage

### Data Format
The accordion accepts an array of objects as data. Each object should have the following structure:
```javascript
const faqs = [
  {
    title: "Accordion Item Title",
    text: "Accordion item content goes here."
  },
  ...
];
```

### Adding the Component
1. Import and use the `Accordion` component in your React application:
   ```javascript
   import Accordion from "./Accordion";

   const faqs = [
     {
       title: "Where are these chairs assembled?",
       text: "Lorem ipsum dolor sit amet consectetur adipisicing elit."
     },
     {
       title: "How long do I have to return my chair?",
       text: "Pariatur recusandae dignissimos fuga voluptas unde optio nesciunt."
     }
   ];

   function App() {
     return <Accordion data={faqs} />;
   }

   export default App;
   ```

2. Customize the data, styles, and structure as needed.

---

## Folder Structure

```
react-accordion/
├── src/
│   ├── App.js             // Main app component
│   ├── Accordion.js       // Accordion and AccordionItem components
│   ├── index.js           // Entry point
│   ├── styles.css         // Styles for the accordion
├── public/
│   ├── index.html         // HTML template
├── package.json           // Project dependencies and scripts
├── README.md              // Project documentation
```

---




