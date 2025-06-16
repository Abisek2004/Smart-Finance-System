# 💰 Simple Finance Dashboard

A personal finance web app to categorize and visualize your debit and credit transactions using Streamlit, Plotly, and Pandas.

[Live Demo](https://smart-finance-system-devbylisa.streamlit.app/) 🚀

---

## 📌 Features

- Upload your **CSV** bank transaction file
- Automatically categorize expenses based on keywords
- Add or edit categories and keywords
- View expense summaries by category
- Interactive pie charts and summaries
- Editable transaction table using Streamlit's `data_editor`
- Persistent keyword-category mapping using `categories.json`

---

## 📂 Project Structure

```
├── main.py                 # Main Streamlit application
├── categories.json         # Stores user-defined categories and keywords
├── requirements.txt        # Required Python packages
├── README.md               # Project documentation
└── .streamlit/
    └── config.toml         # Streamlit Cloud config (optional)
```

---

## 📝 Installation

### 🔧 Local Setup

1. Clone the repo:

```bash
git clone https://github.com/your-username/simple-finance-dashboard.git
cd simple-finance-dashboard
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Run the app:

```bash
streamlit run main.py
```

---

## ☁️ Deploy to Streamlit Cloud

1. Push your code to a **GitHub repository**
2. Go to [Streamlit Cloud](https://streamlit.io/cloud)
3. Connect your GitHub repo
4. Select `main.py` as the entry point
5. Add `requirements.txt` to install dependencies
6. Deploy and share the app link!

---

## 📋 CSV Format Example

Your uploaded file must contain these columns:

- **Date** (e.g. `12 Jan 2024`)
- **Details** (transaction description)
- **Amount** (can include `,` separators)
- **Debit/Credit** (`Debit` or `Credit`)

---

## 📦 Requirements

```
streamlit==1.34.0
pandas==2.2.2
plotly==5.19.0
```

---

## 👩‍💻 Author

Built with ❤️ by Abishek

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
