# sc-analysis
Custom analysis scripts for single-cell-related projects

## Script uploading guideline
- Create a directory with the analysis ID as the name. Analysis ID can be the JIRA ticket number or a short, informative string
- Fill in the table below to record the analysis ID, project name, who you are and an expanded description of the analysis
- Upload your analysis scripts (R, Rmd, python or Jupyter notebook) to the folder. It's optional to upload data or result files but it's not recommanded to upload large data files (>10MB). 

| Analysis ID | Project | Uploader | Description |
|-------------|---------|----------|-------------|
|R_notebook_template| generic |    Li   | Template for R markdown notebook     |
|BIOSC-6_CEF_QC_analysis|      PACT-SMART   |     Li     |     General QC analysis for CEF and HEK datasets        |
|BIOSC-44_Seurat4_citeseq+Zheng_liver_TIL            | PACT-SMART        |  Li        | Parsing T cells from Seruat v4 cite-seq and interagation with Zheng et al Liver TIL dataset            |
|BIOSC-47_celltype_classification|PACT-SMART|Li|cell type classifier based on hierarchical clustering of T cell subtypes of seurat v4 cite-seq dataset|
|||||
