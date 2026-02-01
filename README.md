# 🃏 Game of War – Card Game (JavaScript)

A browser-based implementation of the classic **Game of War**, built using **vanilla HTML, CSS, and JavaScript**, powered by the **Deck of Cards API**.

This project focuses on:

* Working with **async/await**
* Fetching and handling **external APIs**
* DOM manipulation
* Game-state management in JavaScript

---

## 🔧 Tech Stack

* **HTML5** – Structure
* **CSS3** – Styling & layout
* **JavaScript (ES6+)** – Game logic & API interaction
* **Deck of Cards API** – Card generation and shuffling

---

## 🎮 How the Game Works

1. Click **New Deck** to create and shuffle a fresh deck.
2. Click **Draw** to draw two cards:

   * One for the **computer**
   * One for **you**
3. The higher-value card wins the round:

   * Scores update automatically
   * Face cards are ranked:
     `JACK < QUEEN < KING < ACE`
4. When all cards are exhausted:

   * The final winner is declared
   * The **Draw** button is disabled

---

## 🧠 Card Ranking Logic

Cards are compared using an explicit ranking system:

```js
["2", "3", "4", "5", "6", "7", "8", "9", 
 "10", "JACK", "QUEEN", "KING", "ACE"]
```

Each card’s value is compared by its index in this array, ensuring consistent and predictable results.

---

## 🚀 Features

* Async API calls using `async/await`
* Real-time score tracking
* Dynamic card rendering
* Game-ending logic when deck is empty
* Clean UI with responsive layout

---

## 📦 API Used

**Deck of Cards API (via Scrimba proxy)**

```
https://apis.scrimba.com/deckofcards/api/
```

Endpoints used:

* Create & shuffle a new deck
* Draw cards from an existing deck

---

## 🖥️ How to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/game-of-war.git
   ```
2. Open `index.html` in your browser
   *(No build tools or dependencies required)*

---

## 📁 Project Structure

```
├── index.html
├── index.css
├── index.js
└── img/
    └── table.png
```

---

## 🔍 Learning Outcomes

This project helped reinforce:

* How `async/await` works under the hood
* Proper handling of asynchronous API responses
* DOM updates based on application state
* Avoiding common beginner mistakes with Promises

---

## 🛠️ Possible Improvements

* Disable **Draw** button until a deck is created
* Add animations for card flips
* Refactor card comparison logic using a rank map
* Add sound effects or mobile optimizations

---

## 📜 License

This project is open-source and free to use for learning purposes.

---
🧑‍💻 Developer

Arkopratim Chakraborty 
📍 Software Engineer | Siemens Technology & Services Pvt. Ltd. 
🔗 LinkedIN - https://www.linkedin.com/in/arkopratim-chakraborty/ |
💻 GitHub - https://github.com/Arko101

