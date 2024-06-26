# Doremon-turtle
Draw Doremon form python turtle

An educational environment for learning Python, suitable for beginners and children.

Homepage: [http://pythonturtle.org](http://pythonturtle.org)

## An Appealing Environment to Learn Python

PythonTurtle strives to provide the lowest-threshold way to learn Python.
Students command an interactive Python shell (similar to the [IDLE development
environment](https://docs.python.org/3/library/idle.html)) and use Python
functions to move a turtle displayed on the screen.

An illustrated help screen introduces the student to the basics of Python
programming while demonstrating how to move the turtle. Simplicity and a
colorful visual appearance makes the learning environment more appealing
to students.

![Screen shot](./doremon1.png)
![image](./doremon2.png)


## Installation

Installers for Microsoft Windows and macOS are available from
[pythonturtle.org](http://pythonturtle.org) and [GitHub](
https://github.com/PythonTurtle/PythonTurtle/releases).

Ubuntu Linux:

```bash
sudo apt-get install -y python3-wxgtk4.0
```

Fedora:

```bash
python3 -m pip install wxpython
```

On any GNU/Linux distribution: (after installing prerequisites from above)

```bash
python3 -m pip install --user PythonTurtle
PythonTurtle
```

If you're into automation:

[Ansible tasks](https://github.com/painless-software/ansible-role-software/blob/master/tasks/education/programming.yml#L12-L43
) for setting up PythonTurtle including a desktop shortcut for GNOME.

## Troubleshooting

> ImportError: libpng12.so.0: cannot open shared object file: No such file or directory

See https://askubuntu.com/a/978338/14650


## Compatibility

Tested with Python version 3.6 and wxPython version 4.0.1.
Reported to run on Windows, macOS, Ubuntu Linux, and Fedora.


## Development

```bash
git clone https://github.com/PythonTurtle/PythonTurtle.git
cd PythonTurtle
python3 -m pythonturtle
```

Build application bundles like this:

```bash
python3 setup.py clean bundle
```
