conda create -n wineq python=3.7 -y
conda activate wineq
pip install requirements.txt
pip install ./requirements.txt
pip install dvc 'dvc[gdrive]' scikit-learn 