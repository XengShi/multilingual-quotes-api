# 📚 Multilingual Quotes API
A simple, open-source collection of multilingual quotes focused on technology, science, logic, innovation, and inspiration.

## 🌐 Supported Languages

- English
- Hindi
- Urdu
- ...more coming soon!

## 🚀 How to Use

These `.json` files are publicly hosted. You can directly fetch them using any HTTP client (like `fetch`, `axios`, `curl`, etc).

**Example URLs:**

```
https://xengshi.github.io/multilingual-quotes-api/data/english.json
https://xengshi.github.io/multilingual-quotes-api/data/hindi.json
https://xengshi.github.io/multilingual-quotes-api/data/urdu.json
```

**Example (JavaScript):**

```js
fetch("https://xengshi.github.io/multilingual-quotes-api/data/english.json")
  .then(res => res.json())
  .then(data => console.log(data));
```

## 🤝 Contributing

Everyone is welcome to contribute quotes in their native languages. Just keep a few things in mind:

- ✅ Make sure you write the **correct author's name**.
- 🧠 Prefer quotes related to **technology, science, logic, or motivation**.
- 🚫 Avoid inappropriate, offensive, or unrelated content.
- 💬 Quotes should be **short and meaningful**.
- 🌍 Add quotes to the correct language file inside `/data/` directory.
- 🧪 Validate JSON format before pushing.

## 📁 Folder Structure

```
multilingual-quotes-api/
├── data/
│   ├── english.json
│   ├── hindi.json
│   ├── urdu.json
│   └── ...other language files
├── README.md
```

