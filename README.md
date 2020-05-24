# AGH_5
Seminarium z wizualizacji i redukcji liczby zmiennych wejściowych

Inicjalizacja śeodowiska i instalacja niezbędnych pakietów

conda create -n fs_viz
conda activate fs_viz
conda install jupyterlab statsmodels scikit-learn numpy scipy plotly ipywidgets ipykernel nb_conda_kernels scikit-image
conda install -c plotly plotly-orca==1.2.1 psutil requests
jupyter labextension install jupyterlab-plotly@4.7.1
jupyter labextension install @jupyter-widgets/jupyterlab-manager plotlywidget@4.7.1

# Dane 
Dane epidemiologiczne 
https://raw.githubusercontent.com/jbrownlee/Datasets/master/pima-indians-diabetes.csv

