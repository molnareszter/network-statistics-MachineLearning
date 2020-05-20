FROM jupyter/scipy-notebook
RUN pip install graphviz
RUN pip install pydotplus
ENTRYPOINT ["jupyter", "lab", "--ip=0.0.0.0", "--allow-root" , "--NotebookApp.token=UBBxxx2"]