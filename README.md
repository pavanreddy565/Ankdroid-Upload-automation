# 📚 AnkiDroid Vocabulary Deck Automation

This repository contains a Jupyter Notebook (`Anki_Upload.ipynb`) that automates the creation and upload of vocabulary flashcards to AnkiDroid using the [`genanki`](https://github.com/kerrickstaley/genanki) Python module.

## 🚀 Project Purpose

Manually adding hundreds of flashcards to AnkiDroid can be time-consuming and repetitive. This notebook automates the process, especially useful for large, structured datasets like vocabulary lists.

This specific project was created to generate a flashcard deck from a list of **376 commonly asked vocabulary words** by **Infosys**, intended to aid in placement preparation and English language improvement.

---

## ✅ Features

- Converts structured vocabulary data into Anki cards
- Automatically creates a new Anki deck
- Supports batch generation of **hundreds of cards**
- Output is a `.apkg` file, ready to import into **AnkiDroid** or desktop Anki

---

## 🛠️ Requirements

- Python 3.6+
- Jupyter Notebook
- [`genanki`](https://github.com/kerrickstaley/genanki)

Install dependencies using:

```bash
pip install genanki
```
# 📚 AnkiDroid Vocabulary Deck Automation

Automated Anki deck generation using Python and the `genanki` module — perfect for large vocabulary sets like Infosys's commonly asked word list (376 words). Save time and avoid the tedium of manual entry!

---

## 📂 Files

| File Name           | Description                                             |
|---------------------|---------------------------------------------------------|
| `Anki_Upload.ipynb` | Main notebook that generates and exports the Anki deck |
| `output.apkg`       | The resulting Anki package file (generated)            |

---

## 🧠 How It Works

1. Vocabulary data (e.g., word and meaning) is structured as a list or loaded from a CSV.
2. A custom note model is created using `genanki`.
3. Each word is added as a flashcard (Front: Word, Back: Meaning).
4. All cards are compiled into an Anki deck.
5. The deck is exported as a `.apkg` file for import into Anki or AnkiDroid.

---

## 📥 How to Use

1. Clone or download this repository.
2. Open `Anki_Upload.ipynb` in Jupyter Notebook.
3. Modify the vocabulary list as needed (or load your own dataset).
4. Run all cells to generate the `.apkg` file.
5. Open **Anki** or **AnkiDroid** and import the generated deck.

---

## 💡 Use Case Example

You're preparing for Infosys interviews and have a list of 376 vocabulary words you want to memorize. Instead of adding each one manually into Anki:

- Use this notebook to generate the flashcards in minutes.
- Import the generated deck into AnkiDroid.
- Start revising efficiently using spaced repetition!

---

## 📌 Notes

- Customize the front/back formatting of the card in the `genanki.Model` section.
- You can extend the card model to include example sentences, synonyms, pronunciation, etc.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- [`genanki`](https://github.com/kerrickstaley/genanki) — for enabling Anki deck generation with Python.
- The Infosys vocabulary list (source not included) — for dataset inspiration.
