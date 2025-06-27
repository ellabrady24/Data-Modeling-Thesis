
## Data Modeling Thesis Notebooks
Data_Collection_Text.ipynb: Collect text-based diagrams (mermaid and plantUML) from GitHub repositories,extract diagram code. 
Data_Collection_Images.ipynb: Collect images from GitHub repositories. Render text-based diagrams into .png images
Basic_EDA_Text.ipynb: Calculate descriptive statistics to characterize the structure and content of the collected textual diagrams.
PCA_tSNE_Images.ipynb: Image embedding and KMeans Clustering 

## Data Modeling Data
plantuml_results-2.json: .JSON containing key metadata including the repository name, file path, and file URL for plantUML diagrams.
mermaid_results-2.json: JSON containing key metadata including the repository name, file path, and file URL for mermaid diagrams.
diagram_metadata.csv: CSV file containing structured record of all processed textual diagrams, including file names, file paths, code content, and diagram types.

