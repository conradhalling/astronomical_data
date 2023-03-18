# astronomical_data

I am using this repository for working on Allen Downey's
[_Astronomical Data in Python_](https://allendowney.github.io/AstronomicalData/README.html).

## Setting Up

```shell
cd ~/src/conradhalling/astronomical_data
python3 -m venv venv
source venv/bin/activate
pip install -U -r requirements.txt
```

## Starting Jupyter Lab

```shell
cd ~/src/conradhalling/astronomical_data
source venv/bin/activate
python3 -Xfrozen_modules=off -m jupyterlab
```
