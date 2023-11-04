# Apple Silicon Data Science Stack

This is a repo for getting started using Python Data Science tools.

It exists mostly because I've had tons of problems in the past on any machine
getting the actual packages, python version, and virtual environments working.


So here we go, assuming a new Mac.

`xcode-select –-install` and accept the agreement in the popup window.

Install rye (https://rye-up.com)

`curl -sSf https://rye-up.com/get | bash`

After you install rye add the following to zprofile:

`source "$HOME/.rye/env"`

Clone this repo and cd to it.

`git clone git@github.com:agmartin/m1-ds-stack.git && cd m1-ds-stack`


Now you should be able to simply do `rye sync` to install Python 3.11.6,
 create a virtual environment, and install all dependencies.

This includes the following packages:

numpy
pandas
scipy
matplotlib
scikit-learn
torch
torchvision
torchtext
torchaudio
ortools
xgboost
