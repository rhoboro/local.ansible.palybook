# 下記を実行

```
sudo xcodebuild -license
ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
brew update
brew install ansible
echo 'export HOMEBREW_CASK_OPTS="--appdir=/Applications"' >> ~/.bash_profile
source ~/.bash_profile
```

# Ansibleの適用

```
ansible-playbook -i hosts site.yml
```

# 下記をbash_profileに追加

```
eval "$(pyenv init -)"
JAVA_HOME
ANDROID_SDK
ANDROID_HOME
```
# vim.zipを~/.vim に解凍

