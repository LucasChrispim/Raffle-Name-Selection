````markdown
# 🎉 Fair Raffle 

This Python script performs a fair and random raffle using participant names stored in a CSV file.

## 📦 Requirements

- Python 3.6 or higher
- pandas

Install dependencies with:

```bash
pip install pandas
````

## 📁 Input File

The input CSV should follow this structure (the script already handles this format correctly):

> The script skips the first line and reads names from the `Name` column.

## 🚀 How to Use

1. Place your CSV file in the same folder as the script.
2. Rename it to `names.csv` or adjust the filename in the script.
3. Run the script:

```bash
python raffle.py
```

4. Press **Enter** to draw the next name.
5. Names won't repeat. Once all have been drawn, the script ends.

## 📜 Example Output

```bash
Press Enter to draw the next name...
Selected: John Doe

Press Enter to draw the next name...
Selected: Jane Smith

All names have been drawn!
```

## 🔐 Fairness

* 100% random thanks to `random.shuffle()`
* No duplicate winners

## 🛠 Author

Made with by [Lucas](https://github.com/LucasChrispim)
