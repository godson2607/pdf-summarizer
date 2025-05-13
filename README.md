# 🧠 PDF Summarizer using LangChain & OpenAI

This project is a simple PDF summarizer built using [LangChain](https://www.langchain.com/), [OpenAI](https://platform.openai.com/), and [Python](https://www.python.org/). It takes a PDF file, splits it into chunks, and uses GPT-4o to generate a summary.

---

## 📁 Project Structure



pdf-summarizer/
│
├── pdf summarizer/
│   └── sample.pdf          # PDF file to be summarized
│
├── main.py                 # Main script
├── .env                    # Contains your OpenAI API key
└── README.md               # Project documentation

`

---

## 🚀 How It Works

1. Loads a PDF using `PyPDFLoader`
2. Splits the PDF into text chunks with `CharacterTextSplitter`
3. Uses GPT-4o via LangChain to summarize the content
4. Outputs the summary to the console

---

## 🛠 Requirements

- Python 3.8+
- OpenAI API Key

### 🔧 Install dependencies

bash
pip install langchain langchain-openai python-dotenv
`

> Also install `pypdf` if you haven’t already:

bash
pip install pypdf


---

## 🔑 Setup `.env` File

Create a `.env` file in the project root with your OpenAI key:


OPENAI_API_KEY=your_openai_api_key_here


---

## ▶ Run the Script

bash
python main.py


---

## 📄 Output

The summary will be printed to the terminal:


📄 Summary:

This PDF talks about ...


---

## 📌 Notes

* Make sure the file path in your code is correct:

  python
  loader = PyPDFLoader("pdf summarizer/sample.pdf")
  

  Avoid typos like `samp;le.pdf` or backslashes `\` on non-Windows systems.

* You can use other models like `"gpt-3.5-turbo"` if you don't have GPT-4o access.

---

## 📚 References

* [LangChain Docs](https://docs.langchain.com/)
* [OpenAI API](https://platform.openai.com/docs)
* [Python dotenv](https://pypi.org/project/python-dotenv/)

---

## 🤝 License

MIT License



---

Let me know if you'd like this README.md translated into Tamil or if you want to add a Streamlit UI for summarizing PDF files visually.
```
