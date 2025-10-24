# 🧬 K-mer Frequency & Origin of Replication Detection in *E. coli*

This Jupyter Notebook analyzes DNA sequences to:
1. Compute **k-mer frequencies** and their **reverse complements**
2. Build a simple **de Bruijn graph**
3. Detect the **origin of replication (oriC)** region in *E. coli* using:
   - DnaA-box motif density
   - GC-skew analysis
   - Combined heuristic scoring

---

## 📁 Files and Structure

| File | Description |
|------|--------------|
| `kmer_notebook_ecoli.ipynb` | Main notebook — includes k-mer analysis, de Bruijn graph construction, motif detection, GC-skew, and oriC scoring pipeline |
| `sequence.fasta` | Input FASTA file containing the *E. coli* genomic sequence (or any other bacterial genome) |
| `README.md` | This documentation file |

---

## ⚙️ Requirements

You can run the notebook in **JupyterLab**, **VS Code**, or **Google Colab**.  
Install the required Python libraries first:

```bash
pip install biopython matplotlib
