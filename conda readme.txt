
0. modify yaml files
	remove 4 lines related to pytorch
1. conda update
	conda update -n base conda
2. yaml install
	conda env create -f cylinder3d.yaml
3. conda recognition
	source /opt/conda/etc/profile.d/conda.sh
4. torch download
	pip3 install torch torchvision torchaudio --index-url https://download.pytorch.org/whl/cu118
5. torch scatter download
	pip install torch-scatter -f https://data.pyg.org/whl/torch-2.2.0.html
6. uninstall numpy
	pip uninstall numpy
7. install numpy
	conda install numpy=1.23.0


