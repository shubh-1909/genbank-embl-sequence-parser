# 🧬 GenBank / EMBL Sequence Parser with GC Analysis

This project reads multiple **GenBank (`.gb`, `.gbk`) and EMBL (`.embl`) files**, extracts gene and CDS features, computes **GC content** for CDS regions, flags interesting genes (long or high GC), and generates a tidy summary table.

It also provides **interactive exploration** using Google Colab DataTables or qgrid.

---

## 🚀 Run on Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/shubh-1909/genbank-embl-sequence-parser/blob/main/notebooks/notebooks/GenBank_EMBL_Parser.ipynb)

---

## 🔬 Features

✅ Upload one or more GenBank (`.gb`, `.gbk`) or EMBL (`.embl`) files  
✅ Extracts:
- Gene / CDS type
- Start & end positions
- Strand direction
- Gene name & product description
- Protein translation (if available)  

✅ Computes:
- **Length** of gene/CDS
- **GC content** for CDS regions  

✅ Flags:
- Long genes (>1000 bp)
- High GC content (>60%)

✅ Interactive exploration:
- Google Colab DataTable
- Optional Excel-style filtering via qgrid

✅ Exports results to a clean CSV file for downstream analysis.

---

## 🛠 Tools Used

- Python
- BioPython for sequence parsing
- Pandas for structured data analysis
- PyPI `qgrid` & Google Colab `data_table` for interactive exploration

---

## 🧬 Example Data Included

Sample files under `examples/`:
- `example.gb` – small GenBank record with multiple genes
- `example.embl` – small EMBL record for quick testing

---

## 👨‍💻 Author

**Shubkarandeep Singh Judge**  
🎓 M.Sc. Biotechnology | 💻 Minor in Computer Science  
🌐 [GitHub: shubh-1909](https://github.com/shubh-1909)

---

## 📜 License

This project is licensed under the **MIT License** — freely available for your research, teaching, or bioinformatics portfolio.


