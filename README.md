# jupyterhubinstall

```
alembic==1.5.3
argon2-cffi==20.1.0
async-generator==1.10
attrs==20.3.0
backcall==0.2.0
bleach==3.3.0
certifi==2020.12.5
certipy==0.1.3
cffi==1.14.4
chardet==4.0.0
cryptography==3.3.1
decorator==4.4.2
defusedxml==0.6.0
entrypoints==0.3
idna==2.10
importlib-metadata==3.4.0
ipykernel==5.4.3
ipython==7.16.1
ipython-genutils==0.2.0
ipywidgets==7.6.3
jedi==0.18.0
Jinja2==2.11.3
jsonschema==3.2.0
jupyter-client==6.1.11
jupyter-core==4.7.1
jupyter-telemetry==0.1.0
jupyterhub==1.3.0
jupyterlab-pygments==0.1.2
jupyterlab-widgets==1.0.0
Mako==1.1.4
MarkupSafe==1.1.1
mistune==0.8.4
nbclient==0.5.1
nbconvert==6.0.7
nbformat==5.1.2
nest-asyncio==1.5.1
notebook==6.2.0
oauthlib==3.1.0
packaging==20.9
pamela==1.0.0
pandocfilters==1.4.3
parso==0.8.1
pexpect==4.8.0
pickleshare==0.7.5
prometheus-client==0.9.0
prompt-toolkit==3.0.14
ptyprocess==0.7.0
pycparser==2.20
Pygments==2.7.4
pyOpenSSL==20.0.1
pyparsing==2.4.7
pyrsistent==0.17.3
python-dateutil==2.8.1
python-editor==1.0.4
python-json-logger==2.0.1
pyzmq==22.0.2
requests==2.25.1
ruamel.yaml==0.16.12
ruamel.yaml.clib==0.2.2
Send2Trash==1.5.0
six==1.15.0
SQLAlchemy==1.3.23
terminado==0.9.2
testpath==0.4.4
tornado==6.1
traitlets==4.3.3
typing-extensions==3.7.4.3
urllib3==1.26.3
wcwidth==0.2.5
webencodings==0.5.1
widgetsnbextension==3.5.1
zipp==3.4.0

```

```
[root@jupyter ~]# pip3 install jupyterhub ipython[notebook]
bash: pip3: command not found
[root@jupyter ~]# find / -name \*pip3\*
/usr/share/bash-completion/completions/pip3
/usr/share/bash-completion/completions/pip3.6
/usr/local/bin/pip3
/usr/local/bin/pip3.6
[root@jupyter ~]# /usr/local/bin/pip3 install jupyterhub ipython[notebook]
Collecting jupyterhub
  Downloading jupyterhub-1.3.0-py3-none-any.whl (3.6 MB)
     |████████████████████████████████| 3.6 MB 19.7 MB/s 
Collecting ipython[notebook]
  Downloading ipython-7.16.1-py3-none-any.whl (785 kB)
     |████████████████████████████████| 785 kB 61.2 MB/s 
Collecting decorator
  Downloading decorator-4.4.2-py2.py3-none-any.whl (9.2 kB)
Requirement already satisfied: setuptools>=18.5 in /usr/lib/python3.6/site-packages (from ipython[notebook]) (39.2.0)
Collecting prompt-toolkit!=3.0.0,!=3.0.1,<3.1.0,>=2.0.0
  Downloading prompt_toolkit-3.0.14-py3-none-any.whl (359 kB)
     |████████████████████████████████| 359 kB 65.6 MB/s 
Collecting backcall
  Downloading backcall-0.2.0-py2.py3-none-any.whl (11 kB)
Collecting pickleshare
  Downloading pickleshare-0.7.5-py2.py3-none-any.whl (6.9 kB)
Collecting jedi>=0.10
  Downloading jedi-0.18.0-py2.py3-none-any.whl (1.4 MB)
     |████████████████████████████████| 1.4 MB 67.2 MB/s 
Collecting pygments
  Downloading Pygments-2.7.4-py3-none-any.whl (950 kB)
     |████████████████████████████████| 950 kB 64.6 MB/s 
Collecting pexpect
  Downloading pexpect-4.8.0-py2.py3-none-any.whl (59 kB)
     |████████████████████████████████| 59 kB 10.1 MB/s 
Collecting traitlets>=4.2
  Downloading traitlets-4.3.3-py2.py3-none-any.whl (75 kB)
     |████████████████████████████████| 75 kB 6.1 MB/s 
Collecting ipywidgets
  Downloading ipywidgets-7.6.3-py2.py3-none-any.whl (121 kB)
     |████████████████████████████████| 121 kB 67.2 MB/s 
Collecting notebook
  Downloading notebook-6.2.0-py3-none-any.whl (9.5 MB)
     |████████████████████████████████| 9.5 MB 63.2 MB/s 
Collecting parso<0.9.0,>=0.8.0
  Downloading parso-0.8.1-py2.py3-none-any.whl (93 kB)
     |████████████████████████████████| 93 kB 2.6 MB/s 
Collecting wcwidth
  Downloading wcwidth-0.2.5-py2.py3-none-any.whl (30 kB)
Collecting six
  Downloading six-1.15.0-py2.py3-none-any.whl (10 kB)
Collecting ipython-genutils
  Downloading ipython_genutils-0.2.0-py2.py3-none-any.whl (26 kB)
Collecting SQLAlchemy>=1.1
  Downloading SQLAlchemy-1.3.23-cp36-cp36m-manylinux2010_x86_64.whl (1.3 MB)
     |████████████████████████████████| 1.3 MB 63.5 MB/s 
Collecting entrypoints
  Downloading entrypoints-0.3-py2.py3-none-any.whl (11 kB)
Collecting async-generator>=1.9
  Downloading async_generator-1.10-py3-none-any.whl (18 kB)
Collecting tornado>=5.1
  Downloading tornado-6.1-cp36-cp36m-manylinux2010_x86_64.whl (427 kB)
     |████████████████████████████████| 427 kB 62.5 MB/s 
Collecting requests
  Downloading requests-2.25.1-py2.py3-none-any.whl (61 kB)
     |████████████████████████████████| 61 kB 11.8 MB/s 
Collecting jupyter-telemetry>=0.1.0
  Downloading jupyter_telemetry-0.1.0-py3-none-any.whl (7.1 kB)
Collecting pamela
  Downloading pamela-1.0.0-py2.py3-none-any.whl (5.8 kB)
Collecting alembic
  Downloading alembic-1.5.3.tar.gz (1.1 MB)
     |████████████████████████████████| 1.1 MB 63.4 MB/s 
Collecting prometheus-client>=0.4.0
  Downloading prometheus_client-0.9.0-py2.py3-none-any.whl (53 kB)
     |████████████████████████████████| 53 kB 3.5 MB/s 
Collecting python-dateutil
  Downloading python_dateutil-2.8.1-py2.py3-none-any.whl (227 kB)
     |████████████████████████████████| 227 kB 69.1 MB/s 
Collecting certipy>=0.1.2
  Downloading certipy-0.1.3-py3-none-any.whl (22 kB)
Collecting oauthlib>=3.0
  Downloading oauthlib-3.1.0-py2.py3-none-any.whl (147 kB)
     |████████████████████████████████| 147 kB 64.0 MB/s 
Collecting jinja2>=2.11.0
  Downloading Jinja2-2.11.3-py2.py3-none-any.whl (125 kB)
     |████████████████████████████████| 125 kB 62.1 MB/s 
Collecting pyopenssl
  Downloading pyOpenSSL-20.0.1-py2.py3-none-any.whl (54 kB)
     |████████████████████████████████| 54 kB 4.1 MB/s 
Collecting MarkupSafe>=0.23
  Downloading MarkupSafe-1.1.1-cp36-cp36m-manylinux2010_x86_64.whl (32 kB)
Collecting jsonschema
  Downloading jsonschema-3.2.0-py2.py3-none-any.whl (56 kB)
     |████████████████████████████████| 56 kB 6.2 MB/s 
Collecting python-json-logger
  Downloading python-json-logger-2.0.1.tar.gz (9.1 kB)
Collecting ruamel.yaml
  Downloading ruamel.yaml-0.16.12-py2.py3-none-any.whl (111 kB)
     |████████████████████████████████| 111 kB 63.0 MB/s 
Collecting Mako
  Downloading Mako-1.1.4.tar.gz (479 kB)
     |████████████████████████████████| 479 kB 64.5 MB/s 
Collecting python-editor>=0.3
  Downloading python_editor-1.0.4-py3-none-any.whl (4.9 kB)
Collecting jupyterlab-widgets>=1.0.0
  Downloading jupyterlab_widgets-1.0.0-py3-none-any.whl (243 kB)
     |████████████████████████████████| 243 kB 62.6 MB/s 
Collecting nbformat>=4.2.0
  Downloading nbformat-5.1.2-py3-none-any.whl (113 kB)
     |████████████████████████████████| 113 kB 58.0 MB/s 
Collecting widgetsnbextension~=3.5.0
  Downloading widgetsnbextension-3.5.1-py2.py3-none-any.whl (2.2 MB)
     |████████████████████████████████| 2.2 MB 62.2 MB/s 
Collecting ipykernel>=4.5.1
  Downloading ipykernel-5.4.3-py3-none-any.whl (120 kB)
     |████████████████████████████████| 120 kB 65.5 MB/s 
Collecting jupyter-client
  Downloading jupyter_client-6.1.11-py3-none-any.whl (108 kB)
     |████████████████████████████████| 108 kB 51.2 MB/s 
Collecting jupyter-core
  Downloading jupyter_core-4.7.1-py3-none-any.whl (82 kB)
     |████████████████████████████████| 82 kB 1.6 MB/s 
Collecting importlib-metadata
  Downloading importlib_metadata-3.4.0-py3-none-any.whl (10 kB)
Collecting attrs>=17.4.0
  Downloading attrs-20.3.0-py2.py3-none-any.whl (49 kB)
     |████████████████████████████████| 49 kB 8.5 MB/s 
Collecting pyrsistent>=0.14.0
  Downloading pyrsistent-0.17.3.tar.gz (106 kB)
     |████████████████████████████████| 106 kB 73.0 MB/s 
Collecting nbconvert
  Downloading nbconvert-6.0.7-py3-none-any.whl (552 kB)
     |████████████████████████████████| 552 kB 69.4 MB/s 
Collecting Send2Trash>=1.5.0
  Downloading Send2Trash-1.5.0-py3-none-any.whl (12 kB)
Collecting terminado>=0.8.3
  Downloading terminado-0.9.2-py3-none-any.whl (14 kB)
Collecting argon2-cffi
  Downloading argon2_cffi-20.1.0-cp35-abi3-manylinux1_x86_64.whl (97 kB)
     |████████████████████████████████| 97 kB 10.6 MB/s 
Collecting pyzmq>=17
  Downloading pyzmq-22.0.2-cp36-cp36m-manylinux1_x86_64.whl (1.1 MB)
     |████████████████████████████████| 1.1 MB 65.7 MB/s 
Collecting ptyprocess
  Downloading ptyprocess-0.7.0-py2.py3-none-any.whl (13 kB)
Collecting cffi>=1.0.0
  Downloading cffi-1.14.4-cp36-cp36m-manylinux1_x86_64.whl (401 kB)
     |████████████████████████████████| 401 kB 77.1 MB/s 
Collecting pycparser
  Downloading pycparser-2.20-py2.py3-none-any.whl (112 kB)
     |████████████████████████████████| 112 kB 79.9 MB/s 
Collecting zipp>=0.5
  Downloading zipp-3.4.0-py3-none-any.whl (5.2 kB)
Collecting typing-extensions>=3.6.4
  Downloading typing_extensions-3.7.4.3-py3-none-any.whl (22 kB)
Collecting testpath
  Downloading testpath-0.4.4-py2.py3-none-any.whl (163 kB)
     |████████████████████████████████| 163 kB 73.2 MB/s 
Collecting bleach
  Downloading bleach-3.3.0-py2.py3-none-any.whl (283 kB)
     |████████████████████████████████| 283 kB 79.9 MB/s 
Collecting pandocfilters>=1.4.1
  Downloading pandocfilters-1.4.3.tar.gz (16 kB)
Collecting mistune<2,>=0.8.1
  Downloading mistune-0.8.4-py2.py3-none-any.whl (16 kB)
Collecting defusedxml
  Downloading defusedxml-0.6.0-py2.py3-none-any.whl (23 kB)
Collecting nbclient<0.6.0,>=0.5.0
  Downloading nbclient-0.5.1-py3-none-any.whl (65 kB)
     |████████████████████████████████| 65 kB 6.0 MB/s 
Collecting jupyterlab-pygments
  Downloading jupyterlab_pygments-0.1.2-py2.py3-none-any.whl (4.6 kB)
Collecting nest-asyncio
  Downloading nest_asyncio-1.5.1-py3-none-any.whl (5.0 kB)
Collecting webencodings
  Downloading webencodings-0.5.1-py2.py3-none-any.whl (11 kB)
Collecting packaging
  Downloading packaging-20.9-py2.py3-none-any.whl (40 kB)
     |████████████████████████████████| 40 kB 9.1 MB/s 
Collecting pyparsing>=2.0.2
  Downloading pyparsing-2.4.7-py2.py3-none-any.whl (67 kB)
     |████████████████████████████████| 67 kB 9.6 MB/s 
Collecting cryptography>=3.2
  Downloading cryptography-3.3.1-cp36-abi3-manylinux2010_x86_64.whl (2.6 MB)
     |████████████████████████████████| 2.6 MB 67.3 MB/s 
Collecting chardet<5,>=3.0.2
  Downloading chardet-4.0.0-py2.py3-none-any.whl (178 kB)
     |████████████████████████████████| 178 kB 78.8 MB/s 
Collecting urllib3<1.27,>=1.21.1
  Downloading urllib3-1.26.3-py2.py3-none-any.whl (137 kB)
     |████████████████████████████████| 137 kB 66.5 MB/s 
Collecting certifi>=2017.4.17
  Downloading certifi-2020.12.5-py2.py3-none-any.whl (147 kB)
     |████████████████████████████████| 147 kB 78.8 MB/s 
Collecting idna<3,>=2.5
  Downloading idna-2.10-py2.py3-none-any.whl (58 kB)
     |████████████████████████████████| 58 kB 9.9 MB/s 
Collecting ruamel.yaml.clib>=0.1.2
  Downloading ruamel.yaml.clib-0.2.2-cp36-cp36m-manylinux1_x86_64.whl (549 kB)
     |████████████████████████████████| 549 kB 77.0 MB/s 
Building wheels for collected packages: alembic, pyrsistent, Mako, pandocfilters, python-json-logger
  Building wheel for alembic (setup.py) ... done
  Created wheel for alembic: filename=alembic-1.5.3-py2.py3-none-any.whl size=155549 sha256=48b16161f597eeecce65b91af81b964e7f11039e995153ba54c486240520799a
  Stored in directory: /root/.cache/pip/wheels/62/9d/29/82c5780ee59c4c94c6e9b7210f83cbbd9310d4779d6c4643c6
  Building wheel for pyrsistent (setup.py) ... done
  Created wheel for pyrsistent: filename=pyrsistent-0.17.3-cp36-cp36m-linux_x86_64.whl size=55876 sha256=c1a3de4c1d1e56d6c9072cc3c069fb020d6352ad15dda263571848ae0b60a7e2
  Stored in directory: /root/.cache/pip/wheels/34/13/19/294da8e11bce7e563afee51251b9fa878185e14f4b5caf00cb
  Building wheel for Mako (setup.py) ... done
  Created wheel for Mako: filename=Mako-1.1.4-py2.py3-none-any.whl size=75675 sha256=6df8213499b5a5abde8a25ac32a9ec96cc842512a3c987915c4e1919cb282cdb
  Stored in directory: /root/.cache/pip/wheels/3c/ee/c2/9651c6b977f9d2a1bb766970d190f71213e2ca47b36d8dc488
  Building wheel for pandocfilters (setup.py) ... done
  Created wheel for pandocfilters: filename=pandocfilters-1.4.3-py3-none-any.whl size=7992 sha256=5e021c1c452ca40871fed23bf55506a126820aa28eb6f3c733a8040bbed60097
  Stored in directory: /root/.cache/pip/wheels/12/12/89/fe63ac4d6ee6440daab4db77b78c63f7f192b700f844b6639f
  Building wheel for python-json-logger (setup.py) ... done
  Created wheel for python-json-logger: filename=python_json_logger-2.0.1-py34-none-any.whl size=7374 sha256=628fa75b686711c017d9c4eb2a487beff0b2cfb47e823773ea8f8eafc2a4cd50
  Stored in directory: /root/.cache/pip/wheels/64/e9/44/041ec2a46cf108765abf9bd14c569f17ee7f950647ddc5b353
Successfully built alembic pyrsistent Mako pandocfilters python-json-logger
Installing collected packages: zipp, typing-extensions, six, ipython-genutils, decorator, traitlets, pyrsistent, importlib-metadata, attrs, wcwidth, tornado, pyzmq, python-dateutil, pyparsing, ptyprocess, parso, jupyter-core, jsonschema, webencodings, pygments, pycparser, prompt-toolkit, pickleshare, pexpect, packaging, nest-asyncio, nbformat, MarkupSafe, jupyter-client, jedi, backcall, async-generator, testpath, pandocfilters, nbclient, mistune, jupyterlab-pygments, jinja2, ipython, entrypoints, defusedxml, cffi, bleach, terminado, Send2Trash, prometheus-client, nbconvert, ipykernel, argon2-cffi, ruamel.yaml.clib, notebook, cryptography, widgetsnbextension, urllib3, SQLAlchemy, ruamel.yaml, python-json-logger, python-editor, pyopenssl, Mako, jupyterlab-widgets, idna, chardet, certifi, requests, pamela, oauthlib, jupyter-telemetry, ipywidgets, certipy, alembic, jupyterhub

```

