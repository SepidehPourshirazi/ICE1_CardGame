# ICE1_CardGame – Java Project 🃏

## 📖 Project Overview
This project is a simple **Card Game simulation** developed as part of the *Fundamentals of Software Design and Development (SYST 17796)* course – **In-Class Exercise 1 (ICE1)**.  
It introduces the basics of **Object-Oriented Programming (OOP)** in Java using a card deck and demonstrates concepts such as classes, objects, encapsulation, and collections.

The game simulates creating a deck of cards, shuffling them, dealing cards to players, and comparing hands.

---

## ✨ Features
- Full deck of **52 standard playing cards** (4 suits × 13 ranks).  
- **Deck generation** and **shuffle** functionality.  
- **Player hands** with multiple dealt cards.  
- **Simple hand comparison** (e.g., highest card wins).  
- Console-based interface.  

---

## 🏗️ System Design

### Main Components
- **Card** → Represents a single playing card (Rank + Suit).  
- **Deck** → Builds, stores, and shuffles the 52-card deck.  
- **Player** → Holds a hand of cards.  
- **Game/Driver** → Main program to initialize the game, deal cards, and display results.  

### OOP Principles Applied
- **Encapsulation** → Card properties (rank, suit) stored privately with getters.  
- **Abstraction** → Game logic separated into different classes.  
- **Reusability** → Deck and Card classes can be reused in future projects.  

---

## ⚙️ Technical Details
- **Language:** Java  
- **IDE:** NetBeans (or IntelliJ / Eclipse)  
- **Concepts Used:**  
  - Java classes and objects  
  - Encapsulation and abstraction  
  - Random shuffling using `Collections.shuffle()`  
  - Console-based output  

---

## 🚀 How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/ICE1_CardGame.git
   cd ICE1_CardGame
