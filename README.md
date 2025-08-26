# 🧮 Item Analysis Puller

A lightweight tool for quickly generating **Top 10** and **Bottom 10** student answer profiles from a ZipGrade `.csv` export — ready to paste into your standard item analysis form.

## 💻 How to Use

1. Download the `.exe` file from the [Releases](../../releases) section.
2. Double-click to open the app.
3. Select:
   - A `.csv` file exported from ZipGrade
   - A destination folder to save the output Excel file
4. The app will create an Excel file with:
   - Top 10 Answer Profiles
   - Bottom 10 Answer Profiles

📎 Copy-paste the results directly into your department's item analysis template.

## ✅ Features

- No Python installation required
- Built-in GUI (via tkinter)
- Auto-selects top/bottom performers
- Uses only 1s and 0s for answer correctness (no names shown)

## 🔧 Tech Stack

- Python 3.12
- tkinter (GUI)
- pandas (data manipulation)
- openpyxl (Excel output)
- Packaged via PyInstaller

## 🧪 Future Plans

- Add item difficulty and discrimination index
- Generate printable summary sheets
- Build macOS `.app` version

## 📄 License

This project is licensed under the [MIT License](LICENSE).
