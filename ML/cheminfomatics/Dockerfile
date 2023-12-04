FROM python:3.11
RUN apt update && apt upgrade -y
RUN apt install -y python3-rdkit

# Install Cheminformatics
RUN pip install --upgrade pip && pip install --no-cache-dir rdkit ase
# Install utilities
RUN pip install --no-cache-dir matplotlib seaborn pandas numpy scipy
# Install ml libraries
RUN pip install --no-cache-dir torch torchvision --index-url https://download.pytorch.org/whl/cpu && pip install --no-cache-dir scikit-learn
