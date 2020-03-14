# Pythonのインストール

### 完全版インストーラからのインストール

https://www.python.org/downloads/  
[Windows](https://www.python.org/downloads/windows/) / [MacOS](https://www.python.org/downloads/mac-osx/)

### homebrewを使用したインストール (MacOS)

    brew install python3

※[Homebrew](https://brew.sh/)をインストールする

    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

--------
## pyenvのインストール (MacOS)

git clone git://github.com/yyuu/pyenv.git ~/.pyenv

$ brew install pyenv

#### ~./bash_profileの編集
    export PYENV_ROOT=/usr/local/var/pyenv
    PATH="$PYENV_ROOT/bin:$PATH"

#### 自動補完機能
    if which pyenv > /dev/null; then eval "$(pyenv init -)"; fi

--------
## venv (Python Virtual Environments)

    python3 -m venv *ENV*

(MacOS/LINUX)
    *ENV*/bin/activate
or
    . *ENV*/bin/activate

(Windows)
    *ENV*\Scripts\activate
