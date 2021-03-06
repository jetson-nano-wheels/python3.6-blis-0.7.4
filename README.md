# python3.6-blis-0.7.4

Blis 0.7.4 for Python 3.6 running on the Nvidia Jetson Tegra.

Blis [[Github](https://github.com/explosion/cython-blis), [pypi](https://pypi.org/project/blis/)] provides high-performance linear algebra and matrix multiplication, implementing the [Blis linear algebra routines](https://github.com/flame/blis) as a self-contained Python C-extension.

## How to use

If you have `pip` (which should be run in a suitable virtual environment) the following should work. You should probably install numpy as shown.

```sh
pip install 'https://github.com/jetson-nano-wheels/python3.6-numpy-1.19.4/releases/download/v0.0.2/numpy-1.19.4-cp36-cp36m-linux_aarch64.whl'
pip install 'https://github.com/jetson-nano-wheels/python3.6-blis-0.7.4/releases/download/v0.0.1/blis-0.7.4-cp36-cp36m-linux_aarch64.whl'
```

## How to contribute

  1. [Fork this repo](https://github.com/jetson-nano-wheels/python3.6-blis-0.7.4/fork)
  2. Update submodules.
  3. Add a branch for your new feature.
  4. Run the `init.sh` script.

Like this:

```sh
git clone git@github.com:you/python3.6-blis-0.7.4
cd python3.6-blis-0.7.4
git submodule update --recursive --init
git checkout -b feature-my-fancy-addition
./init.sh
```

After that, do your edits, commit and push to your repo, and send a pull-request if you like 😃
