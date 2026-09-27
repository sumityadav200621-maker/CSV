# CSV
import pandas as pd

# CSV file open/read
file_path = "Complete_CSV_data.csv"

df = pd.read_csv(file_path)

# Data display
print(df)

# Pehli 5 rows
print("\nFirst 5 rows:")
print(df.head())
