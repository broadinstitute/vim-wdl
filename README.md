# vim-wdl

Syntax highlighting for WDL files

# Installing with Pathogen

If you already have [Pathogen][1] working then skip [Step 1](#step1) and go to
[Step 2](#step2).

<a name="step1"></a>

## Step 1: Install pathogen.vim

[Pathogen][1] is one of the most widely used ways to install plugins

```sh
mkdir -p ~/.vim/autoload ~/.vim/bundle
curl -LSso ~/.vim/autoload/pathogen.vim https://raw.githubusercontent.com/tpope/vim-pathogen/master/autoload/pathogen.vim
```
Next you *need* to add this to your `~/.vimrc`:

```vim
execute pathogen#infect()
```

<a name="step2"></a>

## Step 2: Install as a Pathogen bundle

You now have pathogen installed and can put the WDL syntax definitions into `~/.vim/bundle` like this:

```sh
cd ~/.vim/bundle
git clone https://github.com/broadinstitute/vim-wdl.git
```

Quit Vim and reload it.  Open up a file that ends in `.wdl`

[1]: https://github.com/tpope/vim-pathogen
