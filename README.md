# Voila

_Voila_ is a didactic purposed project meant to exploit python in to a docker container. Let's imagine a simple scenario: _build a simple program able to to render a given sting using ASCII art fonts._

In python, such a task can be solve in a few lines of codes, but this will require _python_ and some extra libraries.

_Voila_ uses [pyfiglet](https://pypi.python.org/pypi/pyfiglet) library to render a given sting using ASCII art fonts. The Voila project requires **python 3.0** and beside **pyfiglet** it requires the: [termcolor](https://pypi.python.org/pypi/termcolor) and [colorama](https://pypi.python.org/pypi/colorama). The above mentioned packages are not part of the standard python distribution; you need to use can use the [pip](https://pypi.python.org/pypi/pip) to install them as in the next code snippet.

```
pip install git+https://github.com/pwaller/pyfiglet
pip install termcolor
pip install colorama
```

After the above mentioned libraries are install installed you can run the script as in the next code snippet:

```
python voila.py test
```

and the result can be :

```
  O                 O   
 oOo               oOo  
  o   .oOo. .oOo    o   
  O   OooO' `Ooo.   O   
  o   O         O   o   
  `oO `OoO' `OoO'   `oO
```

the **voila** script choose randomly the ASCII front so the result may vary.
