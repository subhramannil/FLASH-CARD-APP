# Flashy Card - Language Learning App
Flashy Card is a GUI-based flashcard application designed to help users learn French vocabulary. The app displays a French word, waits for 5 seconds, and then flips to reveal the English translation.

## 🚀 Features
Automated Flipping: The card automatically flips from French to English after a 5-second delay.

Progress Tracking: Words you mark as "known" are removed from the deck and saved to a Known_Words.csv file, so you don't have to study the same words twice.

Dynamic Data: Uses pandas to manage and update the vocabulary list in real-time.

User-Friendly UI: Built with tkinter, featuring custom images and a clean layout.

## 🛠️ Built With
Python 3

Tkinter: For the graphical user interface.

Pandas: For data manipulation and CSV handling.

## 📋 Prerequisites
Before running the app, ensure you have pandas installed:

## Bash
pip install pandas
📂 File Structure
To run this code correctly, ensure your directory is organized as follows:

## Plaintext

DAY-31/
├── data/
│   ├── french_words.csv
│   └── Known_Words.csv (generated automatically)
├── images/
│   ├── card_front.png
│   ├── card_back.png
│   ├── right.png
│   └── wrong.png
└── main.py
## 🎮 How to Use
Launch the App: Run main.py.

### The Challenge: A French word will appear. Try to remember the English translation.

### The Reveal: After 5 seconds, the card will flip to show the English word.

### Feedback: * Click the ✔️ (Check) button if you knew the word. It will be removed from your learning list.

Click the ❌ (Cross) button if you didn't know it. The word will remain in the deck for future sessions.

<img width="1119" height="952" alt="image" src="https://github.com/user-attachments/assets/136b8dec-be70-40ba-8616-ba1ca1230022" />

