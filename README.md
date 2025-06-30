# Extractor

---
A lightweight and easy-to-use Python tool to convert `.mat` (MATLAB) files into `.jpg` image files. Useful for data preprocessing, machine learning pipelines, or visualization purposes.

## 📌 Features

- Converts 2D `.mat` arrays into `.jpg` images
- Batch processing support
- Custom output directory
- Normalizes pixel values (0–255)
- CLI-based usage for ease of automation

## 📂 Example

**Input `.mat` file:**

**Output `.jpg` image:**

Grayscale image where pixel values are scaled based on the matrix.

## 🔧 Requirements

* Python 3.7+
* `scipy`
* `numpy`
* `Pillow` 

## 📥 Installation

```bash
git clone https://github.com/fazeelibtesam/Extractor.git
cd Extractor
pip install -r requirements.txt
```

## 🚀 Usage

```bash
python mat_to_jpg.py --input_dir ./mat_files --output_dir ./jpg_output
```

## 🗂️ Project Structure

```
mat-to-jpg-converter/
│
├── examples/               # Sample .mat files and output images
├── README.md               # Documentation
├── mat_to_jpg.py           # Main script
└── requirements.txt        # Dependencies
```

## 🛠️ Notes

* Make sure the `.mat` files contain 2D arrays for image conversion.
* Use `--key` if the variable name inside the `.mat` file is not obvious.

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## 📄 License

This project is licensed under the Apache 2.0 License - see the [LICENSE](LICENSE) file for details.

Feel free to fork, star ⭐, and follow for updates!

---
