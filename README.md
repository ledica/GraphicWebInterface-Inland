# GraphicWebInterface-Inland
Graphical web interface in python (flask) for inland

Environment
Start by creating a folder for the project in the location of your choice
```bash

mkdir dev
cd dev
```

Download Inland
```bash

git clone https://github.com/inland-dgvm/inland.git
git clone https://github.com/inland-dgvm/inland-data.git
cd inland
```

Download Web Interface
```bash

git clone https://github.com/ledica/GraphicWebInterface-Inland.git
mv GraphicWebInterface-Inland/* ./
rm -rf GraphicWebInterface-Inland
```

Create a virtualenv for the project for creating isolated environments
```bash

sudo apt-get install python-virtualenv
virtualenv graphicWebInterface_env
source graphicWebInterce_env/bin/activate
```

Install cdo-api-py, Flask and Ipython
```bash
pip install SomePackage
pip install -r requirements.txt
```

Initializing the graphical interface
```bash
./startWebInterface.py
```
