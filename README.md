# Visualizing Binder launch data

This uses the [mybinder events archive data](https://archive.analytics.mybinder.org/) to collect information about Binder launches across the federation. It stores this locally in `data/` and then uses the `analyze.ipynb` notebook to create visualizations from this data.

- `notebooks/download_data.ipynb` will download data within a date range from the events archive, group it by month, and save it to the `data/` folder.
- `noteoboks/analyze.ipynb` will use the data in the `data/` folder to generate visualizations and aggregate information about launches.
