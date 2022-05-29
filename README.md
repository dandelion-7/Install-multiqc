# Install-multiqc with conda
# create an environment
conda create --name multiqc

# try with pip install and delete all the previously remaining packages.
pip install multiqc

returning "Requirement already satisfied: multiqc in /home/zhanggaopu/.local/lib/python3.7/site-packages"
"......."
#remove these remaining multiqc packages in site-packages

#Within the env, install with conda
conda install -c conda-forge multiqc
