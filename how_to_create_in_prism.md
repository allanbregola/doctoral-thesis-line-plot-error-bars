# How to Create a Line Plot with Error Bars in Prism GraphPad

This document outlines the basic steps used to create a **line plot with error bars** in **Prism GraphPad**, as applied in a doctoral thesis project.

---

## 1. Prepare Your Data

- Structure your data appropriately for Prism:
  - **Columns** for different time points or conditions.
  - **Rows** for repeated measurements or individual participants.
- Example formats:
  - Mean and SD (Standard Deviation)
  - Mean and SEM (Standard Error of the Mean) or 95%CI

Example data structure used: [`data_example/example_data.csv`](../data_example/example_data.csv)

---

## 2. Import Data into Prism

- Open Prism and create a **New Project**.
- Select the appropriate **graph type**:
  - "Line graph with error bars" → recommended for longitudinal data.
- Import your data from a CSV or enter manually.

---

## 3. Configure the Graph

- Under the **Graph** tab:
  - Select **Line graph** with markers.
  - Choose the correct **error bar type** (SD, SEM, or custom).
  - Adjust:
    - **Line style** (solid, dashed, etc.)
    - **Marker type** and size
    - **Colour** palette appropriate for thesis/publication

---

## 4. Customise the Appearance

- Use **Graph Settings** to fine-tune:
  - Font size (consistent with thesis guidelines)
  - Axis labels (clear and fully descriptive)
  - Axis scales (linear, log, etc.)
  - Gridlines (optional — for clarity)

---

## 5. Export the Graph

- Export as **high-resolution PNG** or **TIFF** for inclusion in thesis.
- Use **vector format (PDF, SVG)** if further editing is needed in Adobe Illustrator or similar software.

Example output: [`example_graph/line_plot_example.png`](../example_graph/line_plot_example.png)

---

## Tips Provided During the Project

- Recommended **mean ± SEM** for clarity in small sample size.
- Suggested consistent use of **font family and size** across all thesis figures.
- Provided guidance on **colour-blind-friendly palettes**.
- Suggested saving project file to enable easy updates later.

---

## Reflections

- This was a valuable exercise in helping a colleague:
  - Present data in a clear and professional way.
  - Increase confidence in using Prism for data visualisation.
  - Ensure that graphs aligned with academic publishing standards.

---

*"Good data visualisation helps bring the science to life."*

---

