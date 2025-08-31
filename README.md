# Differential Gene Expression (DGE) Analysis Assignment

This project analyzes differential gene expression results from RNA-seq data and classifies genes as:

- 🔺 Upregulated
- 🔻 Downregulated
- ◻️ Not Significant

Based on:
- `log2FoldChange` (logFC)
- Adjusted p-value (`padj`)

---

## 📁 Project Structure

## 🧪 Classification Criteria

| Category        | Condition |
|----------------|---------|
| Upregulated     | `logFC > 1` and `padj < 0.05` |
| Downregulated   | `logFC < -1` and `padj < 0.05` |
| Not_Significant | Otherwise |

## 📊 Summary Results

| Dataset       | Upregulated | Downregulated | Total Significant |
|---------------|-------------|---------------|-------------------|
| DEGs_Data_1   | 0           | 0             | 0                |
| DEGs_Data_2   | 670         | 1383          | 2053             |


## 📝 Tools Used
- R (v4.3+)
- Base R (no external packages required)

## 📂 License
MIT License – feel free to reuse.
