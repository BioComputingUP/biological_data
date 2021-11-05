
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
