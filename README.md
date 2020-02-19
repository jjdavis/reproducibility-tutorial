# reproducibility-tutorial
FOSS 2020 workshop
    1  pwd
    2  which emacs
    3  sudo -i
    4  cd
    5  cd .ssh
    6  emacs authorized_keys
    7  ifconfig
    8  netstat -i | more
    9  netstat -a
   10  sudo -i
   11  emacs ~/.ssh/authorized_keys
   12  ls -l ~/.ssh/authorized_keys
   13  ls -ld /scratch
   14  cd /scratch
   15  git clone https://github.com/jjdavis/reproducibility-tutorial.git
   16  ls
   17  cd reproducibility-tutorial/
   18  ls
   19  wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
   20  sudo /bin/bash -x ./Miniconda3-latest-Linux-x86_64.sh -b -p /opt/conda
   21  sudo ln -s /opt/conda/pkgs/*/bin/* /bin
   22  sudo ln -s /opt/conda/pkgs/*/lib/* /usr/lib
   23  which conda
   24  ls -lt /bin | head
   25  clear
   26  ls -lt /bin | head
   27  which clear
   28  ls -lt /bin | more
   29  which conda
   30  sudo /opt/conda/bin/conda install -c conda-forge -y juypterlab=1.2.3
   31  sudo /opt/conda/bin/conda install -c conda-forge -y jupyterlab=1.2.3
   32  sudo /opt/conda/bin/conda install -c conda-forge -y nodejs=10.13.0
   33  sudo /opt/conda/bin/pip install bash_kernel
   34  sudo /opt/conda/bin/pip install ipykernel
   35  sudo /opt/conda/bin/python3 -m bash_kernel.install
   36  conda search htseq
   37  /opt/conda/bin/conda search bioconda
   38  sudo /opt/conda/bin/conda search bioconda
   39  sudo /opt/conda/bin/conda search -c bioconda htseq
   40  sudo /opt/conda/bin/jupyter lab --no-browser --allow-root --ip=0.0.0.0 --NotebookApp.token='' --NotebookApp.password='' --notebook-dir='/scratch/reproducibility-tutorial/'
   41  sudo /opt/conda/bin/conda searh -c bioconda snakemake
   42  sudo /opt/conda/bin/conda install -c bioconda -c conda-forge -y snakemake=5.8.1
   43  sudo ln -s /opt/conda/bin/* /bin
   44  ln -s /opt/conda/lib/* /usr/lib
   45  which snakemake
   46  snakemake --version
   47  sudo apt-get update
   48  sudo apt-get install -y apt-transport-https ca-certificates curl gnupg-agent software-properties-common
   49  sudo curl -fsLS https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   50  sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
   51  sudo apt-get update
   52  sudo apt-get install -y docer-ce docker-ce-cli containerid.io
   53  sudo apt-get install -y docer-ce docker-ce-cli containerd.io
   54  sudo apt-get install -y docker-ce docker-ce-cli containerd.io
   55  docker run hello-world
   56  sudo docker run hello-world
   57  cd /scratch/reproducibility-tutorial/
   58  history >>README.md
