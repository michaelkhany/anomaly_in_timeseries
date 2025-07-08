## 📊 Data Source: Backblaze Drive Stats

This project uses the **Backblaze Hard Drive Data** dataset, an open dataset published quarterly by [Backblaze](https://www.backblaze.com). It includes daily snapshots of operational hard drives from Backblaze data centers, with each record containing:

- SMART attributes (normalized and raw values)
- Drive metadata (model, capacity, serial number, etc.)
- Failure indicator (`failure = 1` for failed drives, `0` otherwise)

For this analysis, we used the **Q1 2025** dataset (`data_Q1_2025.zip`), which contains over **900,000 daily drive records** across the first 3 days of January 2025. Each day's data is stored as a `.csv` file (e.g., `2025-01-01.csv`), and the full dataset spans a wide range of manufacturers and drive models.

🔗 Dataset link:  
[Backblaze Hard Drive Stats - Q1 2025](https://f001.backblazeb2.com/file/Backblaze-Hard-Drive-Data/data_Q1_2025.zip)

Please cite Backblaze if you use this data in any public work.
