# JAX-NeuroGeneticsSClDataAnalysis
Slides for the JAX Neurogenetics Short Course

Single Cell Transcriptomics Analysis Workshop

May 3, 2018

### To view the slides

-   Double click or point a web browser to the slides.html or index.html file.

### To run the analysis notebook

-   Have a python3.6 installation with jupyter.  If you have `conda`, you can do
    this simply with a new virtual env:

        conda create --name new_env python=3.6 jupyter

-   From there, install the `scalpel` package from the `sample_code` directory:

        unzip sample_code.zip
        cd sample_code
        source activate new_env
        pip install -e .
        pip install -r requirements.txt

-   Then run the notebook:

        cd ..
        jupyter notebook AnalysisNotebook.ipynb

You can also look at the `AnalysisNotebook.html` file with a web browser in the
same way you view the slides.
