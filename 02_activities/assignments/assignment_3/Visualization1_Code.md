# Visualization 1: Incident Rate by Region (Toronto Police Data)
# https://data.ontario.ca/dataset/police-reported-crime-rates-by-age/resource/84cf68aa-8c6c-487a-96bf-902ff00a0128


import pandas as pd
import matplotlib.pyplot as plt

file_path = "02_activities/assignments/police-reported_crime_statistics_dataset.csv"
df = pd.read_csv(file_path)

df.columns = df.columns.str.strip()
df = df[df["Region"].notna()]

df["IncidentRate"] = df["IncidentRate"].astype(str).str.replace(",", "", regex=False)
df["IncidentRate"] = pd.to_numeric(df["IncidentRate"], errors="coerce")

df = df.sort_values(by="IncidentRate", ascending=False)

# IMPORTANT: use fig, ax
fig, ax = plt.subplots(figsize=(8, 5))
ax.bar(df["Region"], df["IncidentRate"])

ax.set_title("Incident Rate by Region (Police-Reported Crime)")
ax.set_xlabel("Region")
ax.set_ylabel("Incident Rate per 100,000 Population")
plt.xticks(rotation=45)
plt.tight_layout()

# IMPORTANT: save from fig BEFORE show
output_path = "02_activities/assignments/visualization_1_incident_rate_by_region.png"
fig.savefig(output_path, dpi=300, bbox_inches="tight")

plt.show()
print(f"Saved: {output_path}")
