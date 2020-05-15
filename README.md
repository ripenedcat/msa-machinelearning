# MSA-machinelearning

### Introduction
We all know that the news of Bitcoin's skyrocketing swept the world in 2017. This news shocked me, because a few people a few years ago because of their interest in investing in a few bitcoins have now increased their value by tens or even hundreds of times, and some people have embarked on the path of being rich.

This bitcoin market that made me jealous made me start to try it, but I did n’t have any experience in cryptocurrency investment, nor did I observe the stock market and market-related minds. So, while I may not have a ticket to the moon, I can at least get on board the hype train by successfully predicting the price of cryptos by harnessing machine learning and deep learning.


### Environment
Miniconda + Jupyter Notebook.
Main packages used:
	import pandas as pd
	import time
	import seaborn as sns
	import matplotlib.pyplot as plt
	import datetime
	import numpy as np
	from sklearn.preprocessing import MinMaxScaler
	from keras.models import Sequential
	from keras.layers import Activation, Dense
	from keras.layers import LSTM
	from keras.layers import Dropout

all packages in environment:

  Name                    Version                   Build  Channel
_tflow_select             2.2.0                     eigen
absl-py                   0.9.0                    py37_0
asn1crypto                1.3.0                    py37_0
astor                     0.8.0                    py37_0
attrs                     19.3.0                     py_0
backcall                  0.1.0                    py37_0
blas                      1.0                         mkl
bleach                    3.1.4                      py_0
blinker                   1.4                      py37_0
ca-certificates           2020.1.1                      0
cachetools                3.1.1                      py_0
certifi                   2020.4.5.1               py37_0
cffi                      1.14.0           py37h7a1dbc1_0
chardet                   3.0.4                 py37_1003
click                     7.1.1                      py_0
colorama                  0.4.3                      py_0
cryptography              2.8              py37h7a1dbc1_0
cycler                    0.10.0                   py37_0
decorator                 4.4.2                      py_0
defusedxml                0.6.0                      py_0
entrypoints               0.3                      py37_0
freetype                  2.9.1                ha9979f8_1
gast                      0.2.2                    py37_0
google-auth               1.13.1                     py_0
google-auth-oauthlib      0.4.1                      py_2
google-pasta              0.2.0                      py_0
grpcio                    1.27.2           py37h351948d_0
h5py                      2.10.0           py37h5e291fa_0
hdf5                      1.10.4               h7ebc959_0
icc_rt                    2019.0.0             h0cc432a_1
icu                       58.2                 ha66f8fd_1
idna                      2.9                        py_1
importlib_metadata        1.5.0                    py37_0
intel-openmp              2020.0                      166
ipykernel                 5.1.4            py37h39e3cac_0
ipython                   7.13.0           py37h5ca1d4c_0
ipython_genutils          0.2.0                    py37_0
ipywidgets                7.5.1                      py_0
jedi                      0.16.0                   py37_1
jinja2                    2.11.1                     py_0
joblib                    0.14.1                     py_0
jpeg                      9b                   hb83a4c4_2
jsonschema                3.2.0                    py37_0
jupyter                   1.0.0                    py37_7
jupyter_client            6.1.2                      py_0
jupyter_console           6.1.0                      py_0
jupyter_core              4.6.3                    py37_0
keras                     2.3.1                         0
keras-applications        1.0.8                      py_0
keras-base                2.3.1                    py37_0
keras-preprocessing       1.1.0                      py_1
kiwisolver                1.1.0            py37ha925a31_0
libiconv                  1.15                 h1df5818_7
libpng                    1.6.37               h2a8f88b_0
libprotobuf               3.11.4               h7bd577a_0
libsodium                 1.0.16               h9d3ae62_0
libxml2                   2.9.9                h464c3ec_0
libxslt                   1.1.33               h579f668_0
lxml                      4.5.0            py37h1350720_0
m2w64-gcc-libgfortran     5.3.0                         6
m2w64-gcc-libs            5.3.0                         7
m2w64-gcc-libs-core       5.3.0                         7
m2w64-gmp                 6.1.0                         2
m2w64-libwinpthread-git   5.0.0.4634.697f757               2
markdown                  3.1.1                    py37_0
markupsafe                1.1.1            py37he774522_0
matplotlib                3.1.3                    py37_0
matplotlib-base           3.1.3            py37h64f37c6_0
mistune                   0.8.4            py37he774522_0
mkl                       2020.0                      166
mkl-service               2.3.0            py37hb782905_0
mkl_fft                   1.0.15           py37h14836fe_0
mkl_random                1.1.0            py37h675688f_0
msys2-conda-epoch         20160418                      1
nbconvert                 5.6.1                    py37_0
nbformat                  5.0.4                      py_0
notebook                  6.0.3                    py37_0
numpy                     1.18.1           py37h93ca92e_0
numpy-base                1.18.1           py37hc3f5095_1
oauthlib                  3.1.0                      py_0
openssl                   1.1.1g               he774522_0
opt_einsum                3.1.0                      py_0
pandas                    1.0.3            py37h47e9c7a_0
pandoc                    2.2.3.2                       0
pandocfilters             1.4.2                    py37_1
parso                     0.6.2                      py_0
pickleshare               0.7.5                    py37_0
pip                       20.0.2                   py37_1
prometheus_client         0.7.1                      py_0
prompt-toolkit            3.0.4                      py_0
prompt_toolkit            3.0.4                         0
protobuf                  3.11.4           py37h33f27b4_0
pyasn1                    0.4.8                      py_0
pyasn1-modules            0.2.7                      py_0
pycparser                 2.20                       py_0
pygments                  2.6.1                      py_0
pyjwt                     1.7.1                    py37_0
pyopenssl                 19.1.0                   py37_0
pyparsing                 2.4.6                      py_0
pyqt                      5.9.2            py37h6538335_2
pyreadline                2.1                      py37_1
pyrsistent                0.16.0           py37he774522_0
pysocks                   1.7.1                    py37_0
python                    3.7.7                h60c2a47_2
python-dateutil           2.8.1                      py_0
pytz                      2019.3                     py_0
pywin32                   227              py37he774522_1
pywinpty                  0.5.7                    py37_0
pyyaml                    5.3.1            py37he774522_0
pyzmq                     18.1.1           py37ha925a31_0
qt                        5.9.7            vc14h73c81de_0
qtconsole                 4.7.3                      py_0
qtpy                      1.9.0                      py_0
requests                  2.23.0                   py37_0
requests-oauthlib         1.3.0                      py_0
rsa                       4.0                        py_0
scikit-learn              0.22.1           py37h6288b17_0
scipy                     1.4.1            py37h9439919_0
seaborn                   0.10.0                     py_0
send2trash                1.5.0                    py37_0
setuptools                46.1.3                   py37_0
sip                       4.19.8           py37h6538335_0
six                       1.14.0                   py37_0
sqlite                    3.31.1               he774522_0
tensorboard               2.1.0                     py3_0
tensorflow                2.1.0           eigen_py37hd727fc0_0
tensorflow-base           2.1.0           eigen_py37h49b2757_0
tensorflow-estimator      2.1.0              pyhd54b08b_0
termcolor                 1.1.0                    py37_1
terminado                 0.8.3                    py37_0
testpath                  0.4.4                      py_0
tornado                   6.0.4            py37he774522_1
traitlets                 4.3.3                    py37_0
urllib3                   1.25.8                   py37_0
vc                        14.1                 h0510ff6_4
vs2015_runtime            14.16.27012          hf0eaf9b_1
wcwidth                   0.1.9                      py_0
webencodings              0.5.1                    py37_1
werkzeug                  0.14.1                   py37_0
wheel                     0.34.2                   py37_0
widgetsnbextension        3.5.1                    py37_0
win_inet_pton             1.1.0                    py37_0
wincertstore              0.2                      py37_0
winpty                    0.4.3                         4
wrapt                     1.12.1           py37he774522_1
yaml                      0.1.7                hc54c509_2
zeromq                    4.3.1                h33f27b4_3
zipp                      2.2.0                      py_0
zlib                      1.2.11               h62dcd97_4

### How to used
Use Jupyter Notebook to load 2020-5-15-msa-bitcoin-prediction.ipynb in this project.

### More details
Please refer to the content inside the 2020-5-15-msa-bitcoin-prediction.ipynb.


