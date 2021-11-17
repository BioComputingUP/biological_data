
## Install Conda

   https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html

Disable conda environment on startup (optional)

    conda config --set auto_activate_base false

Useful commands

    # create environment
    conda create -n biological_data

    # list environments
    conda env list

    # activate/deactivate your environment
    conda activate biological_data
    conda deactivate

    # info about the current environment
    conda info
    
    # display all packages in your environment
    conda list

    # install jupyter notebook
    conda install -c conda-forge notebook

    # launch notebook
    jupyter notebook

    # remove environment
    conda env remove -n biological_data

    # clone conda environment
    conda create --name biological_data_new --clone biological_data

## Install Blast

This installs a precompiled version of Blast+ for Linux x64. Other 
versions are available, including Windows and MacOS

(~250 Mb)

    wget ftp://ftp.ncbi.nlm.nih.gov/blast/executables/blast+/LATEST/ncbi-blast-2.12.0+-x64-linux.tar.gz
    tar -xzf ncbi-blast-2.12.0+-x64-linux.tar.gz

## Install HMMER

(~18 Mb)

    wget http://eddylab.org/software/hmmer/hmmer.tar.gz
    tar -xzf hmmer.tar.gz
    ./configure
    make
