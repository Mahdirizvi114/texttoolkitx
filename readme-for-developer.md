# texttoolkitx

`texttoolkitx` is a powerful Python utility library for working with strings, including features like text normalization, cleaning, extraction, formatting, and more. Designed to save time and promote consistency across your projects.

---

## 🚀 Features

- Remove extra spaces and clean strings
- Convert text to various cases (camelCase, snake_case, etc.)
- Validate email and phone numbers
- Extract keywords or substrings
- And more...

---

## 🛠️ Setup for Development

Follow these steps to set up your local development environment:

### 1. Clone the Repository

```bash
git clone https://github.com/Mahdirizvi114/texttoolkitx.git
cd texttoolkitx

2. Create Virtual Environment
python3 -m venv venv
source venv/bin/activate  # For Linux/macOS
# OR
venv\Scripts\activate  # For Windows

3. Install Dependencies
pip install -r requirements.txt

👨‍💻 Development Workflow
✅ Linting (Optional)

pip install flake8
flake8 texttoolkitx/

🧪 Running Tests (Optional)
Make sure to add your test files inside a tests/ directory.
pytest tests/

📦 Build the Package
python setup.py sdist bdist_wheel
This will generate .tar.gz and .whl files inside the dist/ directory.

🚀 Publish to PyPI  
make sure to change version in pyproject.toml like for now it is 0.1.1
1. Install Twine
pip install twine

2. Upload to PyPI
twine upload dist/*

📁 Project Structure

texttoolkitx/
├── __init__.py
├── core.py
├── utils.py
setup.py
README.md
LICENSE

✍️ Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

🏷️ License
This project is licensed under the MIT License - see the LICENSE file for details.

Let me know if you want badges, examples, or function docstrings included too.
