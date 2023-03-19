# Building image from course base image
FROM risserlin/bcb420-base-image:latest

# Packages required for the analysis

RUN R -e "BiocManager::install(c('DESeq2', 'pheatmap'))"

