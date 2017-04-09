# Kaggle Titanic Challenge


## Links

 - [Cursory EDA RMarkdown](./src/R-eda.Rmd)
 - [Jupyter Notebook of Pipeline](./src/titanic.ipynb)


## Requirements

```yaml
name: titanic
channels: !!python/tuple
- conda-forge
- defaults
dependencies:
- conda-forge::blas=1.1=openblas
- conda-forge::bleach=1.5.0=py36_0
- conda-forge::ca-certificates=2017.1.23=0
- conda-forge::certifi=2017.1.23=py36_0
- conda-forge::cycler=0.10.0=py36_0
- conda-forge::dbus=1.10.10=3
- conda-forge::decorator=4.0.11=py36_0
- conda-forge::entrypoints=0.2.2=py36_1
- conda-forge::expat=2.1.0=2
- conda-forge::fontconfig=2.12.1=4
- conda-forge::freetype=2.7=1
- conda-forge::gettext=0.19.7=1
- conda-forge::glib=2.51.4=0
- conda-forge::gmp=6.1.2=0
- conda-forge::gst-plugins-base=1.8.0=0
- conda-forge::gstreamer=1.8.0=1
- conda-forge::html5lib=0.999=py36_0
- conda-forge::icu=58.1=1
- conda-forge::ipykernel=4.6.0=py36_0
- conda-forge::ipython=5.3.0=py36_0
- conda-forge::ipython_genutils=0.2.0=py36_0
- conda-forge::ipywidgets=6.0.0=py36_0
- conda-forge::jinja2=2.9.5=py36_0
- conda-forge::jpeg=9b=0
- conda-forge::jsonschema=2.5.1=py36_0
- conda-forge::jupyter=1.0.0=py36_0
- conda-forge::jupyter_client=5.0.1=py36_0
- conda-forge::jupyter_console=5.1.0=py36_0
- conda-forge::jupyter_core=4.3.0=py36_0
- conda-forge::libffi=3.2.1=3
- conda-forge::libiconv=1.14=4
- conda-forge::libpng=1.6.28=0
- conda-forge::libsodium=1.0.10=0
- conda-forge::libxcb=1.12=1
- conda-forge::libxml2=2.9.4=4
- conda-forge::markupsafe=0.23=py36_1
- conda-forge::matplotlib=2.0.0=np112py36_3
- conda-forge::mistune=0.7.4=py36_0
- conda-forge::nbconvert=5.1.1=py36_1
- conda-forge::nbformat=4.2.0=py36_0
- conda-forge::ncurses=5.9=10
- conda-forge::notebook=5.0.0=py36_0
- conda-forge::numpy=1.12.1=py36_blas_openblas_200
- conda-forge::openblas=0.2.19=1
- conda-forge::openssl=1.0.2h=3
- conda-forge::pandas=0.19.2=np112py36_1
- conda-forge::pandoc=1.19.2=0
- conda-forge::pandocfilters=1.4.1=py36_0
- conda-forge::patsy=0.4.1=py36_0
- conda-forge::pcre=8.39=0
- conda-forge::pexpect=4.2.1=py36_0
- conda-forge::pickleshare=0.7.3=py36_0
- conda-forge::pip=9.0.1=py36_0
- conda-forge::prompt_toolkit=1.0.14=py36_0
- conda-forge::ptyprocess=0.5.1=py36_0
- conda-forge::pygments=2.2.0=py36_0
- conda-forge::pyparsing=2.2.0=py36_0
- conda-forge::pyqt=5.6.0=py36_0
- conda-forge::python=3.6.1=0
- conda-forge::python-dateutil=2.6.0=py36_0
- conda-forge::pytz=2017.2=py36_0
- conda-forge::pyzmq=16.0.2=py36_1
- conda-forge::qt=5.6.2=1
- conda-forge::qtconsole=4.3.0=py36_0
- conda-forge::readline=6.2=0
- conda-forge::scikit-learn=0.18.1=np112py36_blas_openblas_200
- conda-forge::scipy=0.19.0=np112py36_blas_openblas_200
- conda-forge::seaborn=0.7.1=py36_0
- conda-forge::setuptools=33.1.1=py36_0
- conda-forge::simplegeneric=0.8.1=py36_0
- conda-forge::sip=4.18=py36_1
- conda-forge::six=1.10.0=py36_1
- conda-forge::sqlite=3.13.0=1
- conda-forge::statsmodels=0.8.0=np112py36_0
- conda-forge::terminado=0.6=py36_0
- conda-forge::testpath=0.3=py36_0
- conda-forge::tk=8.5.19=1
- conda-forge::tornado=4.4.3=py36_0
- conda-forge::traitlets=4.3.2=py36_0
- conda-forge::wcwidth=0.1.7=py36_0
- conda-forge::webencodings=0.5=py36_0
- conda-forge::wheel=0.29.0=py36_0
- conda-forge::widgetsnbextension=2.0.0=py36_0
- conda-forge::xgboost=0.6a2=py36_0
- conda-forge::xorg-libxau=1.0.8=3
- conda-forge::xorg-libxdmcp=1.1.2=3
- conda-forge::xz=5.2.2=0
- conda-forge::zeromq=4.2.1=1
- conda-forge::zlib=1.2.11=0
- libgfortran=3.0.0=1
- pip:
  - ipython-genutils==0.2.0
  - jupyter-client==5.0.1
  - jupyter-console==5.1.0
  - jupyter-core==4.3.0
  - prompt-toolkit==1.0.14
prefix: /home/deadhand/anaconda3/envs/titanic
```