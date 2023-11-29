FROM python:3.12
RUN apt update && apt upgrade -y
RUN apt install -y python3-rdkit

# Install Cheminformatics
RUN pip install --upgrade pip && pip install rdkit ase
# Install ml libraries
RUN pip install pytorch torchvision scikit-learn
# Install utilities
RUN pip install matplotlib seaborn pandas numpy scipy
