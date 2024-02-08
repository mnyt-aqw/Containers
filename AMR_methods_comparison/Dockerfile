FROM mnytaqw/quarto_jupyter_base:latest

RUN mamba install \
    pandas==2.2.0 \
    scipy==1.12.0 \
    matplotlib==3.8.2 \
    seaborn==0.13.2 \
    numpy==1.26.3 \
    scikit-learn==1.4.0 \
    plotly==5.18.0 \
    statsmodels==0.14.1 \
    theme-darcula \
    ipywidgets==8.0.7 \
    biopython==1.83 \
    tabulate \
    nodejs \
    -y --quiet

RUN python3 -m pip install \ 
    nbzip \
    ipydrawio \
    ipydrawio-export \
    jupyterlab-quarto \
    jupyterlab-spellchecker \
    jupyterlab-code-formatter \
    black \
    isort
