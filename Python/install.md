# Pythonのインストール

### 完全版インストーラからのインストール

https://www.python.org/downloads/  
[Windows](https://www.python.org/downloads/windows/) / [MacOS](https://www.python.org/downloads/mac-osx/)

### homebrewを使用したインストール (MacOS)

    brew install python3

※更新

    brew upgrade python3

※[Homebrew](https://brew.sh/)をインストールする

    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"

--------
## venv (Python Virtual Environments)

    python3 -m venv _ENV_

(MacOS/LINUX)

    source _ENV_/bin/activate

or

    . _ENV_/bin/activate

(Windows)

    _ENV_\Scripts\activate
