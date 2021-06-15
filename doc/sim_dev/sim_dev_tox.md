# sim_dev
2021-06-14

`tox.ini` installation:
```shell# 
/home/cwm/git/git.c-w-m/eda_dev/.tox/eda_dev39/bin/python /opt/pycharm-community-2021.1/plugins/python-ce/helpers/pycharm/_jb_tox_runner.py
Testing started at 8:50 AM ...
sim_dev37 create: /home/cwm/git/git.c-w-m/sim_dev/.tox/sim_dev37
sim_dev37 installdeps: -rrequirements.txt
sim_dev37 installed: anyio==3.1.0,appdirs==1.4.4,argon2-cffi==20.1.0,async-generator==1.10,attrs==21.2.0,Babel==2.9.1,backcall==0.2.0,bleach==3.3.0,certifi==2021.5.30,cffi==1.14.5,chardet==4.0.0,cramjam==2.3.2,cycler==0.10.0,Cython==0.29.23,decorator==5.0.9,defusedxml==0.7.1,desmod==0.6.1,distlib==0.3.1,entrypoints==0.3,et-xmlfile==1.1.0,fastparquet==0.6.3,filelock==3.0.12,flake8==3.9.2,fsspec==2021.6.0,greenlet==1.1.0,idna==2.10,importlib-metadata==3.4.0,importlib-resources==5.1.0,ipykernel==5.5.5,ipython==7.24.1,ipython-genutils==0.2.0,ipywidgets==7.6.3,jedi==0.18.0,Jinja2==3.0.1,json5==0.9.5,jsonschema==3.2.0,jupyter-client==6.1.12,jupyter-core==4.7.1,jupyter-server==1.8.0,jupyterlab==3.0.16,jupyterlab-pygments==0.1.2,jupyterlab-server==2.6.0,jupyterlab-widgets==1.0.0,kiwisolver==1.3.1,lml==0.1.0,lxml==4.6.3,MarkupSafe==2.0.1,matplotlib==3.4.2,matplotlib-inline==0.1.2,mccabe==0.6.1,mistune==0.8.4,mypy==0.812,mypy-extensions==0.4.3,nbclassic==0.3.1,nbclient==0.5.3,nbconvert==6.0.7,nbformat==5.1.3,nest-asyncio==1.5.1,notebook==6.4.0,numexpr==2.7.3,numpy==1.20.3,openpyxl==3.0.7,packaging==20.9,pandas==1.2.4,pandocfilters==1.4.3,parso==0.8.2,patsy==0.5.1,pexpect==4.8.0,pickleshare==0.7.5,Pillow==8.2.0,pluggy==0.13.1,prometheus-client==0.11.0,prompt-toolkit==3.0.18,ptyprocess==0.7.0,py==1.10.0,pyarrow==4.0.1,pycodestyle==2.7.0,pycparser==2.20,pyexcel-ezodf==0.3.4,pyexcel-io==0.6.4,pyexcel-ods3==0.6.0,pyflakes==2.3.1,Pygments==2.9.0,pyparsing==2.4.7,pyrsistent==0.17.3,python-dateutil==2.8.1,pytz==2021.1,pyvcd==0.2.4,pyxlsb==1.0.8,PyYAML==5.4.1,pyzmq==22.1.0,qgrid==1.3.1,requests==2.25.1,scipy==1.6.3,Send2Trash==1.5.0,simpy==4.0.1,six==1.15.0,sniffio==1.2.0,SQLAlchemy==1.4.18,statsmodels==0.12.2,tables==3.6.1,terminado==0.10.0,testpath==0.5.0,thrift==0.13.0,toml==0.10.2,tornado==6.1,tox==3.22.0,traitlets==5.0.5,typed-ast==1.4.3,typing-extensions==3.7.4.3,urllib3==1.26.5,virtualenv==20.4.2,wcwidth==0.2.5,webencodings==0.5.1,websocket-client==1.0.1,widgetsnbextension==3.5.1,xlrd==2.0.1,XlsxWriter==1.4.3,xlwt==1.3.0,zipp==3.4.0
sim_dev37 run-test-pre: PYTHONHASHSEED='1400411166'
sim_dev37 run-test: commands[0] | python -m pip install --upgrade pip
Requirement already satisfied: pip in ./.tox/sim_dev37/lib/python3.7/site-packages (21.0.1)
Collecting pip
  Using cached pip-21.1.2-py3-none-any.whl (1.5 MB)
Installing collected packages: pip
  Attempting uninstall: pip
    Found existing installation: pip 21.0.1
    Uninstalling pip-21.0.1:
      Successfully uninstalled pip-21.0.1
Successfully installed pip-21.1.2
sim_dev37 run-test: commands[1] | python -c 'print((80*"~")+"\ntestenv: commands\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
testenv: commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
sim_dev37 run-test: commands[2] | python -c 'print((80*"~")+"\n"+"pip list\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip list
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
sim_dev37 run-test: commands[3] | python -m pip list --format=columns
Package             Version
------------------- ---------
anyio               3.1.0
appdirs             1.4.4
argon2-cffi         20.1.0
async-generator     1.10
attrs               21.2.0
Babel               2.9.1
backcall            0.2.0
bleach              3.3.0
certifi             2021.5.30
cffi                1.14.5
chardet             4.0.0
cramjam             2.3.2
cycler              0.10.0
Cython              0.29.23
decorator           5.0.9
defusedxml          0.7.1
desmod              0.6.1
distlib             0.3.1
entrypoints         0.3
et-xmlfile          1.1.0
fastparquet         0.6.3
filelock            3.0.12
flake8              3.9.2
fsspec              2021.6.0
greenlet            1.1.0
idna                2.10
importlib-metadata  3.4.0
importlib-resources 5.1.0
ipykernel           5.5.5
ipython             7.24.1
ipython-genutils    0.2.0
ipywidgets          7.6.3
jedi                0.18.0
Jinja2              3.0.1
json5               0.9.5
jsonschema          3.2.0
jupyter-client      6.1.12
jupyter-core        4.7.1
jupyter-server      1.8.0
jupyterlab          3.0.16
jupyterlab-pygments 0.1.2
jupyterlab-server   2.6.0
jupyterlab-widgets  1.0.0
kiwisolver          1.3.1
lml                 0.1.0
lxml                4.6.3
MarkupSafe          2.0.1
matplotlib          3.4.2
matplotlib-inline   0.1.2
mccabe              0.6.1
mistune             0.8.4
mypy                0.812
mypy-extensions     0.4.3
nbclassic           0.3.1
nbclient            0.5.3
nbconvert           6.0.7
nbformat            5.1.3
nest-asyncio        1.5.1
notebook            6.4.0
numexpr             2.7.3
numpy               1.20.3
openpyxl            3.0.7
packaging           20.9
pandas              1.2.4
pandocfilters       1.4.3
parso               0.8.2
patsy               0.5.1
pexpect             4.8.0
pickleshare         0.7.5
Pillow              8.2.0
pip                 21.1.2
pluggy              0.13.1
prometheus-client   0.11.0
prompt-toolkit      3.0.18
ptyprocess          0.7.0
py                  1.10.0
pyarrow             4.0.1
pycodestyle         2.7.0
pycparser           2.20
pyexcel-ezodf       0.3.4
pyexcel-io          0.6.4
pyexcel-ods3        0.6.0
pyflakes            2.3.1
Pygments            2.9.0
pyparsing           2.4.7
pyrsistent          0.17.3
python-dateutil     2.8.1
pytz                2021.1
pyvcd               0.2.4
pyxlsb              1.0.8
PyYAML              5.4.1
pyzmq               22.1.0
qgrid               1.3.1
requests            2.25.1
scipy               1.6.3
Send2Trash          1.5.0
setuptools          56.2.0
simpy               4.0.1
six                 1.15.0
sniffio             1.2.0
SQLAlchemy          1.4.18
statsmodels         0.12.2
tables              3.6.1
terminado           0.10.0
testpath            0.5.0
thrift              0.13.0
toml                0.10.2
tornado             6.1
tox                 3.22.0
traitlets           5.0.5
typed-ast           1.4.3
typing-extensions   3.7.4.3
urllib3             1.26.5
virtualenv          20.4.2
wcwidth             0.2.5
webencodings        0.5.1
websocket-client    1.0.1
wheel               0.36.2
widgetsnbextension  3.5.1
xlrd                2.0.1
XlsxWriter          1.4.3
xlwt                1.3.0
zipp                3.4.0
sim_dev37 run-test: commands[4] | python -c 'print((80*"~")+"\n"+"pip freeze\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip freeze
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
sim_dev37 run-test: commands[5] | pip freeze
anyio==3.1.0
appdirs==1.4.4
argon2-cffi==20.1.0
async-generator==1.10
attrs==21.2.0
Babel==2.9.1
backcall==0.2.0
bleach==3.3.0
certifi==2021.5.30
cffi==1.14.5
chardet==4.0.0
cramjam==2.3.2
cycler==0.10.0
Cython==0.29.23
decorator==5.0.9
defusedxml==0.7.1
desmod==0.6.1
distlib==0.3.1
entrypoints==0.3
et-xmlfile==1.1.0
fastparquet==0.6.3
filelock==3.0.12
flake8==3.9.2
fsspec==2021.6.0
greenlet==1.1.0
idna==2.10
importlib-metadata==3.4.0
importlib-resources==5.1.0
ipykernel==5.5.5
ipython==7.24.1
ipython-genutils==0.2.0
ipywidgets==7.6.3
jedi==0.18.0
Jinja2==3.0.1
json5==0.9.5
jsonschema==3.2.0
jupyter-client==6.1.12
jupyter-core==4.7.1
jupyter-server==1.8.0
jupyterlab==3.0.16
jupyterlab-pygments==0.1.2
jupyterlab-server==2.6.0
jupyterlab-widgets==1.0.0
kiwisolver==1.3.1
lml==0.1.0
lxml==4.6.3
MarkupSafe==2.0.1
matplotlib==3.4.2
matplotlib-inline==0.1.2
mccabe==0.6.1
mistune==0.8.4
mypy==0.812
mypy-extensions==0.4.3
nbclassic==0.3.1
nbclient==0.5.3
nbconvert==6.0.7
nbformat==5.1.3
nest-asyncio==1.5.1
notebook==6.4.0
numexpr==2.7.3
numpy==1.20.3
openpyxl==3.0.7
packaging==20.9
pandas==1.2.4
pandocfilters==1.4.3
parso==0.8.2
patsy==0.5.1
pexpect==4.8.0
pickleshare==0.7.5
Pillow==8.2.0
pluggy==0.13.1
prometheus-client==0.11.0
prompt-toolkit==3.0.18
ptyprocess==0.7.0
py==1.10.0
pyarrow==4.0.1
pycodestyle==2.7.0
pycparser==2.20
pyexcel-ezodf==0.3.4
pyexcel-io==0.6.4
pyexcel-ods3==0.6.0
pyflakes==2.3.1
Pygments==2.9.0
pyparsing==2.4.7
pyrsistent==0.17.3
python-dateutil==2.8.1
pytz==2021.1
pyvcd==0.2.4
pyxlsb==1.0.8
PyYAML==5.4.1
pyzmq==22.1.0
qgrid==1.3.1
requests==2.25.1
scipy==1.6.3
Send2Trash==1.5.0
simpy==4.0.1
six==1.15.0
sniffio==1.2.0
SQLAlchemy==1.4.18
statsmodels==0.12.2
tables==3.6.1
terminado==0.10.0
testpath==0.5.0
thrift==0.13.0
toml==0.10.2
tornado==6.1
tox==3.22.0
traitlets==5.0.5
typed-ast==1.4.3
typing-extensions==3.7.4.3
urllib3==1.26.5
virtualenv==20.4.2
wcwidth==0.2.5
webencodings==0.5.1
websocket-client==1.0.1
widgetsnbextension==3.5.1
xlrd==2.0.1
XlsxWriter==1.4.3
xlwt==1.3.0
zipp==3.4.0
sim_dev37 run-test: commands[6] | python -c 'print((80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

sim_dev39 create: /home/cwm/git/git.c-w-m/sim_dev/.tox/sim_dev39
sim_dev39 installdeps: -rrequirements.txt
sim_dev39 installed: anyio==3.1.0,appdirs==1.4.4,argon2-cffi==20.1.0,async-generator==1.10,attrs==21.2.0,Babel==2.9.1,backcall==0.2.0,bleach==3.3.0,certifi==2021.5.30,cffi==1.14.5,chardet==4.0.0,cramjam==2.3.2,cycler==0.10.0,Cython==0.29.23,decorator==5.0.9,defusedxml==0.7.1,desmod==0.6.1,distlib==0.3.1,entrypoints==0.3,et-xmlfile==1.1.0,fastparquet==0.6.3,filelock==3.0.12,flake8==3.9.2,fsspec==2021.6.0,greenlet==1.1.0,idna==2.10,importlib-metadata==3.4.0,importlib-resources==5.1.0,ipykernel==5.5.5,ipython==7.24.1,ipython-genutils==0.2.0,ipywidgets==7.6.3,jedi==0.18.0,Jinja2==3.0.1,json5==0.9.5,jsonschema==3.2.0,jupyter-client==6.1.12,jupyter-core==4.7.1,jupyter-server==1.8.0,jupyterlab==3.0.16,jupyterlab-pygments==0.1.2,jupyterlab-server==2.6.0,jupyterlab-widgets==1.0.0,kiwisolver==1.3.1,lml==0.1.0,lxml==4.6.3,MarkupSafe==2.0.1,matplotlib==3.4.2,matplotlib-inline==0.1.2,mccabe==0.6.1,mistune==0.8.4,mypy==0.812,mypy-extensions==0.4.3,nbclassic==0.3.1,nbclient==0.5.3,nbconvert==6.0.7,nbformat==5.1.3,nest-asyncio==1.5.1,notebook==6.4.0,numexpr==2.7.3,numpy==1.20.3,openpyxl==3.0.7,packaging==20.9,pandas==1.2.4,pandocfilters==1.4.3,parso==0.8.2,patsy==0.5.1,pexpect==4.8.0,pickleshare==0.7.5,Pillow==8.2.0,pluggy==0.13.1,prometheus-client==0.11.0,prompt-toolkit==3.0.18,ptyprocess==0.7.0,py==1.10.0,pyarrow==4.0.1,pycodestyle==2.7.0,pycparser==2.20,pyexcel-ezodf==0.3.4,pyexcel-io==0.6.4,pyexcel-ods3==0.6.0,pyflakes==2.3.1,Pygments==2.9.0,pyparsing==2.4.7,pyrsistent==0.17.3,python-dateutil==2.8.1,pytz==2021.1,pyvcd==0.2.4,pyxlsb==1.0.8,PyYAML==5.4.1,pyzmq==22.1.0,qgrid==1.3.1,requests==2.25.1,scipy==1.6.3,Send2Trash==1.5.0,simpy==4.0.1,six==1.15.0,sniffio==1.2.0,SQLAlchemy==1.4.18,statsmodels==0.12.2,tables==3.6.1,terminado==0.10.0,testpath==0.5.0,thrift==0.13.0,toml==0.10.2,tornado==6.1,tox==3.22.0,traitlets==5.0.5,typed-ast==1.4.3,typing-extensions==3.7.4.3,urllib3==1.26.5,virtualenv==20.4.2,wcwidth==0.2.5,webencodings==0.5.1,websocket-client==1.0.1,widgetsnbextension==3.5.1,xlrd==2.0.1,XlsxWriter==1.4.3,xlwt==1.3.0,zipp==3.4.0
sim_dev39 run-test-pre: PYTHONHASHSEED='1400411166'
sim_dev39 run-test: commands[0] | python -m pip install --upgrade pip
Requirement already satisfied: pip in ./.tox/sim_dev39/lib/python3.9/site-packages (21.0.1)
Collecting pip
  Using cached pip-21.1.2-py3-none-any.whl (1.5 MB)
Installing collected packages: pip
  Attempting uninstall: pip
    Found existing installation: pip 21.0.1
    Uninstalling pip-21.0.1:
      Successfully uninstalled pip-21.0.1
Successfully installed pip-21.1.2
sim_dev39 run-test: commands[1] | python -c 'print((80*"~")+"\ntestenv: commands\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
testenv: commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
sim_dev39 run-test: commands[2] | python -c 'print((80*"~")+"\n"+"pip list\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip list
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
sim_dev39 run-test: commands[3] | python -m pip list --format=columns
Package             Version
------------------- ---------
anyio               3.1.0
appdirs             1.4.4
argon2-cffi         20.1.0
async-generator     1.10
attrs               21.2.0
Babel               2.9.1
backcall            0.2.0
bleach              3.3.0
certifi             2021.5.30
cffi                1.14.5
chardet             4.0.0
cramjam             2.3.2
cycler              0.10.0
Cython              0.29.23
decorator           5.0.9
defusedxml          0.7.1
desmod              0.6.1
distlib             0.3.1
entrypoints         0.3
et-xmlfile          1.1.0
fastparquet         0.6.3
filelock            3.0.12
flake8              3.9.2
fsspec              2021.6.0
greenlet            1.1.0
idna                2.10
importlib-metadata  3.4.0
importlib-resources 5.1.0
ipykernel           5.5.5
ipython             7.24.1
ipython-genutils    0.2.0
ipywidgets          7.6.3
jedi                0.18.0
Jinja2              3.0.1
json5               0.9.5
jsonschema          3.2.0
jupyter-client      6.1.12
jupyter-core        4.7.1
jupyter-server      1.8.0
jupyterlab          3.0.16
jupyterlab-pygments 0.1.2
jupyterlab-server   2.6.0
jupyterlab-widgets  1.0.0
kiwisolver          1.3.1
lml                 0.1.0
lxml                4.6.3
MarkupSafe          2.0.1
matplotlib          3.4.2
matplotlib-inline   0.1.2
mccabe              0.6.1
mistune             0.8.4
mypy                0.812
mypy-extensions     0.4.3
nbclassic           0.3.1
nbclient            0.5.3
nbconvert           6.0.7
nbformat            5.1.3
nest-asyncio        1.5.1
notebook            6.4.0
numexpr             2.7.3
numpy               1.20.3
openpyxl            3.0.7
packaging           20.9
pandas              1.2.4
pandocfilters       1.4.3
parso               0.8.2
patsy               0.5.1
pexpect             4.8.0
pickleshare         0.7.5
Pillow              8.2.0
pip                 21.1.2
pluggy              0.13.1
prometheus-client   0.11.0
prompt-toolkit      3.0.18
ptyprocess          0.7.0
py                  1.10.0
pyarrow             4.0.1
pycodestyle         2.7.0
pycparser           2.20
pyexcel-ezodf       0.3.4
pyexcel-io          0.6.4
pyexcel-ods3        0.6.0
pyflakes            2.3.1
Pygments            2.9.0
pyparsing           2.4.7
pyrsistent          0.17.3
python-dateutil     2.8.1
pytz                2021.1
pyvcd               0.2.4
pyxlsb              1.0.8
PyYAML              5.4.1
pyzmq               22.1.0
qgrid               1.3.1
requests            2.25.1
scipy               1.6.3
Send2Trash          1.5.0
setuptools          56.2.0
simpy               4.0.1
six                 1.15.0
sniffio             1.2.0
SQLAlchemy          1.4.18
statsmodels         0.12.2
tables              3.6.1
terminado           0.10.0
testpath            0.5.0
thrift              0.13.0
toml                0.10.2
tornado             6.1
tox                 3.22.0
traitlets           5.0.5
typed-ast           1.4.3
typing-extensions   3.7.4.3
urllib3             1.26.5
virtualenv          20.4.2
wcwidth             0.2.5
webencodings        0.5.1
websocket-client    1.0.1
wheel               0.36.2
widgetsnbextension  3.5.1
xlrd                2.0.1
XlsxWriter          1.4.3
xlwt                1.3.0
zipp                3.4.0
sim_dev39 run-test: commands[4] | python -c 'print((80*"~")+"\n"+"pip freeze\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip freeze
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
sim_dev39 run-test: commands[5] | pip freeze
anyio==3.1.0
appdirs==1.4.4
argon2-cffi==20.1.0
async-generator==1.10
attrs==21.2.0
Babel==2.9.1
backcall==0.2.0
bleach==3.3.0
certifi==2021.5.30
cffi==1.14.5
chardet==4.0.0
cramjam==2.3.2
cycler==0.10.0
Cython==0.29.23
decorator==5.0.9
defusedxml==0.7.1
desmod==0.6.1
distlib==0.3.1
entrypoints==0.3
et-xmlfile==1.1.0
fastparquet==0.6.3
filelock==3.0.12
flake8==3.9.2
fsspec==2021.6.0
greenlet==1.1.0
idna==2.10
importlib-metadata==3.4.0
importlib-resources==5.1.0
ipykernel==5.5.5
ipython==7.24.1
ipython-genutils==0.2.0
ipywidgets==7.6.3
jedi==0.18.0
Jinja2==3.0.1
json5==0.9.5
jsonschema==3.2.0
jupyter-client==6.1.12
jupyter-core==4.7.1
jupyter-server==1.8.0
jupyterlab==3.0.16
jupyterlab-pygments==0.1.2
jupyterlab-server==2.6.0
jupyterlab-widgets==1.0.0
kiwisolver==1.3.1
lml==0.1.0
lxml==4.6.3
MarkupSafe==2.0.1
matplotlib==3.4.2
matplotlib-inline==0.1.2
mccabe==0.6.1
mistune==0.8.4
mypy==0.812
mypy-extensions==0.4.3
nbclassic==0.3.1
nbclient==0.5.3
nbconvert==6.0.7
nbformat==5.1.3
nest-asyncio==1.5.1
notebook==6.4.0
numexpr==2.7.3
numpy==1.20.3
openpyxl==3.0.7
packaging==20.9
pandas==1.2.4
pandocfilters==1.4.3
parso==0.8.2
patsy==0.5.1
pexpect==4.8.0
pickleshare==0.7.5
Pillow==8.2.0
pluggy==0.13.1
prometheus-client==0.11.0
prompt-toolkit==3.0.18
ptyprocess==0.7.0
py==1.10.0
pyarrow==4.0.1
pycodestyle==2.7.0
pycparser==2.20
pyexcel-ezodf==0.3.4
pyexcel-io==0.6.4
pyexcel-ods3==0.6.0
pyflakes==2.3.1
Pygments==2.9.0
pyparsing==2.4.7
pyrsistent==0.17.3
python-dateutil==2.8.1
pytz==2021.1
pyvcd==0.2.4
pyxlsb==1.0.8
PyYAML==5.4.1
pyzmq==22.1.0
qgrid==1.3.1
requests==2.25.1
scipy==1.6.3
Send2Trash==1.5.0
simpy==4.0.1
six==1.15.0
sniffio==1.2.0
SQLAlchemy==1.4.18
statsmodels==0.12.2
tables==3.6.1
terminado==0.10.0
testpath==0.5.0
thrift==0.13.0
toml==0.10.2
tornado==6.1
tox==3.22.0
traitlets==5.0.5
typed-ast==1.4.3
typing-extensions==3.7.4.3
urllib3==1.26.5
virtualenv==20.4.2
wcwidth==0.2.5
webencodings==0.5.1
websocket-client==1.0.1
widgetsnbextension==3.5.1
xlrd==2.0.1
XlsxWriter==1.4.3
xlwt==1.3.0
zipp==3.4.0
sim_dev39 run-test: commands[6] | python -c 'print((80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

___________________________________ summary ____________________________________
  sim_dev37: commands succeeded
  sim_dev39: commands succeeded
  congratulations :)

Process finished with exit code 0
```