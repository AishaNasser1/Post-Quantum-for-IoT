# Post-Quantum-for-IoT
Efficiency Adjusted Security for Post-Quantum Cryptography in IoT
##Repository Structure

- **EAS_PQC_NIST_ONLY_FINAL_FIXED.ipynb** - Main analysis notebook
- **pqc_iot_classification.csv** - PQM4 benchmark data (input)
- **nist_algorithms_full_data.csv** - Processed NIST algorithm data (output)
- **IEEE_IoT___EAS_PQC.pdf** - Research paper

##  Quick Start

1. Upload `pqc_iot_classification.csv` when prompted
2. Run all cells in the notebook
3. Check validation cell at the end - should show all ✅

##  Main Results

- Class 0: 0/25 algorithms feasible
- Class 1: 13/25 algorithms feasible (52%)
- Class 2: 15/25 algorithms feasible (60%)

See paper for detailed analysis.

##  Citation
----

```

---

## ⚠️ COMMON ERRORS & SOLUTIONS

### Error: "File too large (> 100 MB)"
**Solution:** Don't upload large files. Use Git LFS or external hosting.

### Error: "Permission denied"
**Solution:** Make sure you're logged into the correct GitHub account.

### Error: "Failed to push"
**Solution:** 
```bash
git pull origin main --rebase
git push origin main
```

### Error: "Notebook won't render on GitHub"
**Solution:** 
- Make sure file extension is `.ipynb` (not `.txt`)
- File size < 1 MB usually renders fine
- Try reloading the page
