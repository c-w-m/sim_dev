# sim_dev
2021-06-03

`tox.ini` installation:
```shell# 
/home/cwm/git/git.c-w-m/ec_dev/.venv/bin/python /opt/pycharm-community-2021.1/plugins/python-ce/helpers/pycharm/_jb_tox_runner.py
Testing started at 1:36 AM ...
sim_dev37 create: /home/cwm/git/git.c-w-m/sim_dev/.tox/sim_dev37
sim_dev37 installdeps: flake8, mypy, jupyterlab, -rrequirements.txt
sim_dev37 installed: anyio==3.1.0,appdirs==1.4.4,argon2-cffi==20.1.0,async-generator==1.10,attrs==21.2.0,Babel==2.9.1,backcall==0.2.0,bleach==3.3.0,certifi==2021.5.30,cffi==1.14.5,chardet==4.0.0,Cython==0.29.23,decorator==5.0.9,defusedxml==0.7.1,distlib==0.3.1,entrypoints==0.3,filelock==3.0.12,flake8==3.9.2,idna==2.10,importlib-metadata==3.4.0,importlib-resources==5.1.0,ipykernel==5.5.5,ipython==7.24.1,ipython-genutils==0.2.0,jedi==0.18.0,Jinja2==3.0.1,json5==0.9.5,jsonschema==3.2.0,jupyter-client==6.1.12,jupyter-core==4.7.1,jupyter-server==1.8.0,jupyterlab==3.0.16,jupyterlab-pygments==0.1.2,jupyterlab-server==2.6.0,MarkupSafe==2.0.1,matplotlib-inline==0.1.2,mccabe==0.6.1,mistune==0.8.4,mypy==0.812,mypy-extensions==0.4.3,nbclassic==0.3.1,nbclient==0.5.3,nbconvert==6.0.7,nbformat==5.1.3,nest-asyncio==1.5.1,notebook==6.4.0,packaging==20.9,pandocfilters==1.4.3,parso==0.8.2,pexpect==4.8.0,pickleshare==0.7.5,pluggy==0.13.1,prometheus-client==0.11.0,prompt-toolkit==3.0.18,ptyprocess==0.7.0,py==1.10.0,pycodestyle==2.7.0,pycparser==2.20,pyflakes==2.3.1,Pygments==2.9.0,pyparsing==2.4.7,pyrsistent==0.17.3,python-dateutil==2.8.1,pytz==2021.1,pyzmq==22.1.0,requests==2.25.1,Send2Trash==1.5.0,six==1.15.0,sniffio==1.2.0,terminado==0.10.0,testpath==0.5.0,toml==0.10.2,tornado==6.1,tox==3.22.0,traitlets==5.0.5,typed-ast==1.4.3,typing-extensions==3.7.4.3,urllib3==1.26.5,virtualenv==20.4.2,wcwidth==0.2.5,webencodings==0.5.1,websocket-client==1.0.1,zipp==3.4.0
sim_dev37 run-test-pre: PYTHONHASHSEED='3051707191'
sim_dev37 run-test: commands[0] | python -c 'print((80*"~")+"\ntestenv: commands\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
testenv: commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
sim_dev37 run-test: commands[1] | python -c 'print((80*"~")+"\n"+"pip list\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip list
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
sim_dev37 run-test: commands[2] | python -m pip list --format=columns
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
Cython              0.29.23
decorator           5.0.9
defusedxml          0.7.1
distlib             0.3.1
entrypoints         0.3
filelock            3.0.12
flake8              3.9.2
idna                2.10
importlib-metadata  3.4.0
importlib-resources 5.1.0
ipykernel           5.5.5
ipython             7.24.1
ipython-genutils    0.2.0
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
MarkupSafe          2.0.1
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
packaging           20.9
pandocfilters       1.4.3
parso               0.8.2
pexpect             4.8.0
pickleshare         0.7.5
pip                 21.0.1
pluggy              0.13.1
prometheus-client   0.11.0
prompt-toolkit      3.0.18
ptyprocess          0.7.0
py                  1.10.0
pycodestyle         2.7.0
pycparser           2.20
pyflakes            2.3.1
Pygments            2.9.0
pyparsing           2.4.7
pyrsistent          0.17.3
python-dateutil     2.8.1
pytz                2021.1
pyzmq               22.1.0
requests            2.25.1
Send2Trash          1.5.0
setuptools          56.1.0
six                 1.15.0
sniffio             1.2.0
terminado           0.10.0
testpath            0.5.0
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
zipp                3.4.0
sim_dev37 run-test: commands[3] | python -c 'print((80*"~")+"\n"+"pip freeze\n"+(80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
pip freeze
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
sim_dev37 run-test: commands[4] | pip freeze
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
Cython==0.29.23
decorator==5.0.9
defusedxml==0.7.1
distlib==0.3.1
entrypoints==0.3
filelock==3.0.12
flake8==3.9.2
idna==2.10
importlib-metadata==3.4.0
importlib-resources==5.1.0
ipykernel==5.5.5
ipython==7.24.1
ipython-genutils==0.2.0
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
MarkupSafe==2.0.1
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
packaging==20.9
pandocfilters==1.4.3
parso==0.8.2
pexpect==4.8.0
pickleshare==0.7.5
pluggy==0.13.1
prometheus-client==0.11.0
prompt-toolkit==3.0.18
ptyprocess==0.7.0
py==1.10.0
pycodestyle==2.7.0
pycparser==2.20
pyflakes==2.3.1
Pygments==2.9.0
pyparsing==2.4.7
pyrsistent==0.17.3
python-dateutil==2.8.1
pytz==2021.1
pyzmq==22.1.0
requests==2.25.1
Send2Trash==1.5.0
six==1.15.0
sniffio==1.2.0
terminado==0.10.0
testpath==0.5.0
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
zipp==3.4.0
sim_dev37 run-test: commands[5] | python -c 'print((80*"~"))'
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

___________________________________ summary ____________________________________
  sim_dev37: commands succeeded
  congratulations :)

Process finished with exit code 0

```