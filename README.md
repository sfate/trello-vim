A barebone vim plugin to fetch user assigned cards from Trello

## Requirements##
* Vim compiled with Python
* Trello API keys

## Installation##


####Using Vundle####
Append this to .vimrc
```vim
Bundle 'malithsen/trello-vim'
```

Then install in the usual way
```vim
:BundleInstall
````

Run INSTALL.py and follow the instructions
```shell
pip install -r ~/.vim/bundle/trello-vim/requirements.txt
python ~/.vim/bundle/trello-vim/INSTALL.py
```

Above step is an one time procedure to set up trello oauth tokens

## Usage##
Open assigned cards in a new buffer
```vim
:Cards
```

