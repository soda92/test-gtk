# test-gtk

repo demostrating usage of [msys2_env](https://pypi.org/project/msys2-env/).

## install

install msys2-env. then create the virtual env: `msys2-env`.

install packages: `.venv2/fish -c install.fish`.

modify `.venv2\pyvenv.cfg`, change `include-system-site-packages = true`.

## Run

```
.venv2/Scripts/activate.ps1
python hello.py
```
