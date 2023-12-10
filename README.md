# Data1030-Final

## Overview

This project examines factors in flight delay using the 2015 airline dataset collected by the department of transportation and found on kaggle. The project first does exploratoratory data analysis (EDA) to examine and find some general trends about flights departing from Boston. It then creates a ML pipeline to examine multiple different models and there accuracy in predicting arrival delay. These models are stored in the results folder. Overall, the best model was found to be XXX with a performance of XXX, which is marginally better than the baseline performance of XXX. 

## LINKS

Link to Dataset Folder on Google Drive:
  https://drive.google.com/drive/u/0/folders/1cs27v_Bs1LA_tXRjZZGeJ0UA_UAFi1m0

Link to Dataset on Kaggle:
  https://www.kaggle.com/datasets/usdot/flight-delays

Presentation on EDA and Preprocessing:
  https://docs.google.com/presentation/d/1n3lgXxpYyVGzIvKifDIKt0662ecCsmenNdtNsijEdDU/edit#slide=id.g290418ee21e_0_4

Final Presentation on Model Performance & Feature Analysis:
  https://docs.google.com/presentation/d/1giW8pl612sHWX14tgGnmKl5BwNnQkooDdjkTGpcAh9w/edit#slide=id.g2a15b586966_0_0


## Python & Package Versions (also found in the yml file): name: data1030
channels:
  - conda-forge
  - defaults
dependencies:
  - _py-xgboost-mutex=2.0=cpu_0
  - anyio=4.0.0=pyhd8ed1ab_0
  - appnope=0.1.3=pyhd8ed1ab_0
  - argon2-cffi=23.1.0=pyhd8ed1ab_0
  - argon2-cffi-bindings=21.2.0=py311h5547dcb_3
  - arrow=1.2.3=pyhd8ed1ab_0
  - asttokens=2.4.0=pyhd8ed1ab_0
  - async-lru=2.0.4=pyhd8ed1ab_0
  - attrs=23.1.0=pyh71513ae_1
  - babel=2.12.1=pyhd8ed1ab_1
  - backcall=0.2.0=pyh9f0ad1d_0
  - backports=1.0=pyhd8ed1ab_3
  - backports.functools_lru_cache=1.6.5=pyhd8ed1ab_0
  - beautifulsoup4=4.12.2=pyha770c72_0
  - bleach=6.0.0=pyhd8ed1ab_0
  - brotli=1.1.0=h0dc2134_0
  - brotli-bin=1.1.0=h0dc2134_0
  - brotli-python=1.1.0=py311hdf8f085_0
  - bzip2=1.0.8=h0d85af4_4
  - ca-certificates=2023.7.22=h8857fd0_0
  - cached-property=1.5.2=hd8ed1ab_1
  - cached_property=1.5.2=pyha770c72_1
  - certifi=2023.7.22=pyhd8ed1ab_0
  - cffi=1.15.1=py311ha86e640_3
  - charset-normalizer=3.2.0=pyhd8ed1ab_0
  - cloudpickle=2.2.1=pyhd8ed1ab_0
  - colorama=0.4.6=pyhd8ed1ab_0
  - comm=0.1.4=pyhd8ed1ab_0
  - contourpy=1.1.1=py311h5fe6e05_0
  - cycler=0.11.0=pyhd8ed1ab_0
  - debugpy=1.8.0=py311hdf8f085_0
  - decorator=5.1.1=pyhd8ed1ab_0
  - defusedxml=0.7.1=pyhd8ed1ab_0
  - entrypoints=0.4=pyhd8ed1ab_0
  - exceptiongroup=1.1.3=pyhd8ed1ab_0
  - executing=1.2.0=pyhd8ed1ab_0
  - fonttools=4.42.1=py311h2725bcf_0
  - fqdn=1.5.1=pyhd8ed1ab_0
  - freetype=2.12.1=h60636b9_2
  - gettext=0.21.1=h8a4c099_0
  - glib=2.78.0=h7d26f99_0
  - glib-tools=2.78.0=h7d26f99_0
  - gst-plugins-base=1.22.5=hb5d3a86_1
  - gstreamer=1.22.5=h840fbdc_1
  - icu=73.2=hf5e326d_0
  - idna=3.4=pyhd8ed1ab_0
  - importlib-metadata=6.8.0=pyha770c72_0
  - importlib_metadata=6.8.0=hd8ed1ab_0
  - importlib_resources=6.0.1=pyhd8ed1ab_0
  - ipykernel=6.25.2=pyh1050b4e_0
  - ipython=8.15.0=pyh31c8845_0
  - ipython_genutils=0.2.0=py_1
  - ipywidgets=8.1.1=pyhd8ed1ab_0
  - isoduration=20.11.0=pyhd8ed1ab_0
  - jedi=0.19.0=pyhd8ed1ab_0
  - jinja2=3.1.2=pyhd8ed1ab_1
  - joblib=1.3.2=pyhd8ed1ab_0
  - json5=0.9.14=pyhd8ed1ab_0
  - jsonpointer=2.4=py311h6eed73b_2
  - jsonschema=4.19.0=pyhd8ed1ab_1
  - jsonschema-specifications=2023.7.1=pyhd8ed1ab_0
  - jsonschema-with-format-nongpl=4.19.0=pyhd8ed1ab_1
  - jupyter=1.0.0=py311h6eed73b_8
  - jupyter-lsp=2.2.0=pyhd8ed1ab_0
  - jupyter_client=8.3.1=pyhd8ed1ab_0
  - jupyter_console=6.6.3=pyhd8ed1ab_0
  - jupyter_core=5.3.1=py311h6eed73b_0
  - jupyter_events=0.7.0=pyhd8ed1ab_2
  - jupyter_server=2.7.3=pyhd8ed1ab_0
  - jupyter_server_terminals=0.4.4=pyhd8ed1ab_1
  - jupyterlab=4.0.6=pyhd8ed1ab_0
  - jupyterlab_pygments=0.2.2=pyhd8ed1ab_0
  - jupyterlab_server=2.25.0=pyhd8ed1ab_0
  - jupyterlab_widgets=3.0.9=pyhd8ed1ab_0
  - kiwisolver=1.4.5=py311h5fe6e05_0
  - krb5=1.21.2=hb884880_0
  - lcms2=2.15=ha53face_2
  - lerc=4.0.0=hb486fe8_0
  - libblas=3.9.0=18_osx64_openblas
  - libbrotlicommon=1.1.0=h0dc2134_0
  - libbrotlidec=1.1.0=h0dc2134_0
  - libbrotlienc=1.1.0=h0dc2134_0
  - libcblas=3.9.0=18_osx64_openblas
  - libclang=15.0.7=default_hdb78580_3
  - libclang13=15.0.7=default_h953c2e9_3
  - libcxx=16.0.6=hd57cbcb_0
  - libdeflate=1.19=ha4e1b8e_0
  - libedit=3.1.20191231=h0678c8f_2
  - libexpat=2.5.0=hf0c8a7f_1
  - libffi=3.4.2=h0d85af4_5
  - libgfortran=5.0.0=13_2_0_h97931a8_1
  - libgfortran5=13.2.0=h2873a65_1
  - libglib=2.78.0=hc62aa5d_0
  - libiconv=1.17=hac89ed1_0
  - libjpeg-turbo=2.1.5.1=h0dc2134_1
  - liblapack=3.9.0=18_osx64_openblas
  - libllvm14=14.0.6=hc8e404f_4
  - libllvm15=15.0.7=he4b1e75_3
  - libogg=1.3.4=h35c211d_1
  - libopenblas=0.3.24=openmp_h48a4ad5_0
  - libopus=1.3.1=hc929b4f_1
  - libpng=1.6.39=ha978bb4_0
  - libpq=15.4=h3df487d_0
  - libsodium=1.0.18=hbcb3906_1
  - libsqlite=3.43.0=h58db7d2_0
  - libtiff=4.6.0=haeeb97c_1
  - libvorbis=1.3.7=h046ec9c_0
  - libwebp-base=1.3.2=h0dc2134_0
  - libxcb=1.15=hb7f2c08_0
  - libxgboost=1.7.6=cpu_h72f100a_2
  - libxml2=2.11.5=h3346baf_1
  - libzlib=1.2.13=h8a1eda9_5
  - llvm-openmp=16.0.6=hff08bdf_0
  - llvmlite=0.40.1=py311hcbb5c6d_0
  - markupsafe=2.1.3=py311h2725bcf_0
  - matplotlib=3.7.2=py311h6eed73b_0
  - matplotlib-base=3.7.2=py311haff9b01_0
  - matplotlib-inline=0.1.6=pyhd8ed1ab_0
  - mistune=3.0.1=pyhd8ed1ab_0
  - munkres=1.1.4=pyh9f0ad1d_0
  - mysql-common=8.0.33=h794ff91_4
  - mysql-libs=8.0.33=he48d296_4
  - nbclient=0.8.0=pyhd8ed1ab_0
  - nbconvert=7.8.0=pyhd8ed1ab_0
  - nbconvert-core=7.8.0=pyhd8ed1ab_0
  - nbconvert-pandoc=7.8.0=pyhd8ed1ab_0
  - nbformat=5.9.2=pyhd8ed1ab_0
  - ncurses=6.4=hf0c8a7f_0
  - nest-asyncio=1.5.6=pyhd8ed1ab_0
  - notebook=7.0.3=pyhd8ed1ab_0
  - notebook-shim=0.2.3=pyhd8ed1ab_0
  - nspr=4.35=hea0b92c_0
  - nss=3.92=hd6ac835_0
  - numba=0.57.1=py311h5a8220d_0
  - numpy=1.24.4=py311hc44ba51_0
  - openjpeg=2.5.0=ha4da562_3
  - openssl=3.1.2=h8a1eda9_0
  - overrides=7.4.0=pyhd8ed1ab_0
  - packaging=23.1=pyhd8ed1ab_0
  - pandas=2.0.3=py311hab14417_1
  - pandoc=3.1.3=h9d075a6_0
  - pandocfilters=1.5.0=pyhd8ed1ab_0
  - parso=0.8.3=pyhd8ed1ab_0
  - patsy=0.5.3=pyhd8ed1ab_0
  - pcre2=10.40=h1c4e4bc_0
  - pexpect=4.8.0=pyh1a96a4e_2
  - pickleshare=0.7.5=py_1003
  - pillow=10.0.1=py311hd5308a1_0
  - pip=23.2.1=pyhd8ed1ab_0
  - pkgutil-resolve-name=1.3.10=pyhd8ed1ab_1
  - platformdirs=3.10.0=pyhd8ed1ab_0
  - ply=3.11=py_1
  - prometheus_client=0.17.1=pyhd8ed1ab_0
  - prompt-toolkit=3.0.39=pyha770c72_0
  - prompt_toolkit=3.0.39=hd8ed1ab_0
  - psutil=5.9.5=py311h5547dcb_0
  - pthread-stubs=0.4=hc929b4f_1001
  - ptyprocess=0.7.0=pyhd3deb0d_0
  - pure_eval=0.2.2=pyhd8ed1ab_0
  - py-xgboost=1.7.6=cpu_py311hedae6b8_2
  - pycparser=2.21=pyhd8ed1ab_0
  - pygments=2.16.1=pyhd8ed1ab_0
  - pyobjc-core=9.2=py311hf110eff_0
  - pyobjc-framework-cocoa=9.2=py311hf110eff_0
  - pyparsing=3.0.9=pyhd8ed1ab_0
  - pyqt=5.15.9=py311h5b1a2bc_4
  - pyqt5-sip=12.12.2=py311h46b81f0_4
  - pysocks=1.7.1=pyha2e5f31_6
  - python=3.11.4=h30d4d87_0_cpython
  - python-dateutil=2.8.2=pyhd8ed1ab_0
  - python-fastjsonschema=2.18.0=pyhd8ed1ab_0
  - python-json-logger=2.0.7=pyhd8ed1ab_0
  - python-tzdata=2023.3=pyhd8ed1ab_0
  - python_abi=3.11=3_cp311
  - pytz=2023.3.post1=pyhd8ed1ab_0
  - pyyaml=6.0.1=py311h2725bcf_0
  - pyzmq=25.1.1=py311h5dacc12_0
  - qt-main=5.15.8=hc03889f_16
  - qtconsole=5.4.4=pyhd8ed1ab_0
  - qtconsole-base=5.4.4=pyha770c72_0
  - qtpy=2.4.0=pyhd8ed1ab_0
  - readline=8.2=h9e318b2_1
  - referencing=0.30.2=pyhd8ed1ab_0
  - requests=2.31.0=pyhd8ed1ab_0
  - rfc3339-validator=0.1.4=pyhd8ed1ab_0
  - rfc3986-validator=0.1.1=pyh9f0ad1d_0
  - rpds-py=0.10.3=py311h299eb51_0
  - scikit-learn=1.3.0=py311h83feae1_0
  - scipy=1.11.2=py311h16c3c4d_1
  - seaborn=0.12.2=hd8ed1ab_0
  - seaborn-base=0.12.2=pyhd8ed1ab_0
  - send2trash=1.8.2=pyhd1c38e8_0
  - setuptools=68.2.2=pyhd8ed1ab_0
  - shap=0.42.1=py311hab14417_0
  - sip=6.7.11=py311hdf8f085_0
  - six=1.16.0=pyh6c4a22f_0
  - slicer=0.0.7=pyhd8ed1ab_0
  - sniffio=1.3.0=pyhd8ed1ab_0
  - soupsieve=2.5=pyhd8ed1ab_1
  - stack_data=0.6.2=pyhd8ed1ab_0
  - statsmodels=0.14.0=py311h4a70a88_1
  - terminado=0.17.1=pyhd1c38e8_0
  - threadpoolctl=3.2.0=pyha21a80b_0
  - tinycss2=1.2.1=pyhd8ed1ab_0
  - tk=8.6.12=h5dbffcc_0
  - toml=0.10.2=pyhd8ed1ab_0
  - tomli=2.0.1=pyhd8ed1ab_0
  - tornado=6.3.3=py311h2725bcf_0
  - tqdm=4.66.1=pyhd8ed1ab_0
  - traitlets=5.10.0=pyhd8ed1ab_0
  - typing-extensions=4.8.0=hd8ed1ab_0
  - typing_extensions=4.8.0=pyha770c72_0
  - typing_utils=0.1.0=pyhd8ed1ab_0
  - tzdata=2023c=h71feb2d_0
  - uri-template=1.3.0=pyhd8ed1ab_0
  - urllib3=2.0.4=pyhd8ed1ab_0
  - wcwidth=0.2.6=pyhd8ed1ab_0
  - webcolors=1.13=pyhd8ed1ab_0
  - webencodings=0.5.1=pyhd8ed1ab_2
  - websocket-client=1.6.3=pyhd8ed1ab_0
  - wheel=0.41.2=pyhd8ed1ab_0
  - widgetsnbextension=4.0.9=pyhd8ed1ab_0
  - xorg-libxau=1.0.11=h0dc2134_0
  - xorg-libxdmcp=1.1.3=h35c211d_0
  - xz=5.2.6=h775f41a_0
  - yaml=0.2.5=h0d85af4_2
  - zeromq=4.3.4=he49afe7_1
  - zipp=3.16.2=pyhd8ed1ab_0
  - zstd=1.5.5=h829000d_0
  - pip:
      - et-xmlfile==1.1.0
      - openpyxl==3.1.2
prefix: /Users/anoopmanjal/anaconda3/envs/data1030
