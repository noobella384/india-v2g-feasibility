# Grid-India SCADA data (not included, about 700 MB)

To rerun Cell 1 from raw data, download the files here.

1. Go to [Mendeley Data: Electricity Demand, Solar and Wind Generation Data of India (doi:10.17632/y58jknpgs8.2)](https://data.mendeley.com/datasets/y58jknpgs8/2) and click **Download All**.
2. Unzip it into this folder. Subfolders are fine, and don't rename the files.

You should end up with 28 monthly files (`September 2021.xlsx` … `December 2023.xlsx`) and one hourly file (`January 2024- June 2025.xlsx`).

Cell 1 reads both formats:
- **Raw SCADA exports:** a hidden `_osi_config` sheet plus `Sheet1`, with 10-second (2023) or 5-minute (2021–22) samples.
- **The hourly table:** Timestamp, Demand, Wind, Solar, Total Generation.

The cleaned hourly output (`results/01_grid_hourly.csv`) is already in the repo, so Cells 2–5 run without this download.

License: CC BY 4.0, from the North-Eastern Regional Load Despatch Centre, Grid Controller of India.
