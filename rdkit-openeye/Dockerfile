FROM keiserlabnick/cuda9.0-ubuntu14.4-conda

RUN conda create -c rdkit -n chem_env rdkit && \
    source activate chem_env && \
    pip install -i https://pypi.anaconda.org/OpenEye/simple OpenEye-toolkits && \
    mkdir .OpenEye 

COPY oe_license.txt .OpenEye/


