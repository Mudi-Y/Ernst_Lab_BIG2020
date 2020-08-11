# DNase_Analysis

download_and_gen_coords.ipynb 
downloads the necessary datasets from ENCODE and generates XXX_coords.bed files for each cell type:
Hepg2, K562, Huvec, H1hesc. One line per region in the XXX_coords.bed file



Midpoints.ipynb
Generates finds midpoints of each region (each line) in the XXX_coords.bed file



Intersection_matrices.ipynb
Generates intersections matrices all regions in a cell type. Each row in matrix corresponds to one
unique region, each element of a row represents one base. 0 means not in DNase, 1 means in. 

Plots heatmap of regions and percentage overlap across all regions. 
