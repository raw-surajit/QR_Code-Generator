# 📱 QR Code Generator

A simple and efficient Python-based QR Code generator. This project allows users to input any URL and instantly generate a high-quality QR code image saved directly to their system.

## 🚀 Features
* **User Input Driven:** Accepts custom URLs via the terminal.
* **Automated Image Generation:** Uses the `qrcode` and `Pillow` libraries to create and save PNG files.
* **Clean Workflow:** Includes a `.gitignore` to keep the repository free of virtual environment junk and temporary files.

## 🛠️ Technologies Used
* **Language:** Python 3.12
* **Libraries:** `qrcode`, `Pillow (PIL)`
* **Environment:** Virtual Environment (`.venv`) for dependency isolation.

## 📥 Installation

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/QR_Code_Generator.git](https://github.com/YOUR_USERNAME/QR_Code_Generator.git)
   cd QR_Code_Generator

```

2. **Create and activate a virtual environment:**
```bash
python -m venv .venv
# On Windows:
.venv\Scripts\activate

```


3. **Install dependencies:**
```bash
pip install "qrcode[pil]"

```



## 🖥️ Usage

Run the script using Python:

```bash
python main.py

```

Follow the prompt to enter a URL, and your QR code will be generated as `qrcode.png`.

