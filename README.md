# uvcdat-docs
SPHINX Documentation for UV-CDAT


To build:

Requires `sphinx`

```
pip install -U sphinx
```

You'll need to source a UV-CDAT installation:

```
source $UVCDAT_INSTALL_LOC/bin/setup_runtime.sh
```

Then, all you should need to do is:

```
make html
```

Other output targets are available (`make` will list them if you don't provide a target)
