To install..

# In vim
:source %
:PluginInstall

# In bash
cd ~.vim/plugged/YouCompleteMe
git submodule update --init --recursive
sudo apt-get install cmake
./install.sh
