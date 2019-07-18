# zksnark-notebooks

QAP is a SageMath notebook that constructs the polynomials in a Quadratic Arithmetic Program, which is the first stage of constructing a zkSNARK.

This notebook shows how a small arithmetic circuit is transformed into a polynomial. A assignment to the circuit is correct if and only if the created polynomial is divisible by a target polynomial.

The next steps for this notebook are to include the elliptic curve cryptography necessary to hide the private inputs. 

# Downloading and Installing Sage

## Linux
### From a package manager
- for Debian, Ubuntu
```
sudo apt-get install sagemath sagemath-jupyter sagemath-doc-en
```
- for Arch Linux
```
sudo pacman -S sagemath sagemath-jupyter sagemath-doc
```

### From tar.gz

Download tar.gz file from http://www.sagemath.org/download-linux.html

Unpack tar.gz in the dierctory where you want to run sage.

To use Sage directly from the command-line using the `sage` command, use a symbolic link:

```
ln -s /your/path/to/sage /usr/local/bin/sage
```

## macOS
Download .dmg at http://www.sagemath.org/download-mac.html and install as usual.

To use Sage directly from the command-line using the `sage` command, use a symbolic link:

```
ln -s /your/path/to/sage /usr/local/bin/sage
```

## Windows (Cygwin)
Download and run installer from http://www.sagemath.org/download-windows.html 

Select Sage from the start menu to launch a Sage terminal emulator.

## Running this file in sage
```
git clone https://github.com/statebox/zksnark-notebooks
cd zksnark-notebooks
sage -n jupyter
```

The Jupyter notebook will launch in the browser. From here you can open the .ipynb file.

You will see several cells of code. In order, select each cell and click 'Run'.

