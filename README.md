# sprout-wrap

[![Build Status](https://travis-ci.org/pivotal-sprout/sprout-wrap.png?branch=master)](https://travis-ci.org/pivotal-sprout/sprout-wrap)

## Installation

On a base install of Ubuntu
install ruby, here's how to use chruby
```
wget -O chruby-0.3.9.tar.gz https://github.com/postmodern/chruby/archive/v0.3.9.tar.gz
tar -xzvf chruby-0.3.9.tar.gz
cd chruby-0.3.9/
sudo make install
echo ‘source /usr/local/share/chruby/chruby.sh’ >> ~/.bashrc

```
install a ruby
```
wget -O ruby-install-0.6.1.tar.gz https://github.com/postmodern/ruby-install/archive/v0.6.1.tar.gz
tar -xzvf ruby-install-0.6.1.tar.gz
cd ruby-install-0.6.1/
sudo make install
ruby-install ruby 2.3.3
```
Open a new shell
```sh
sudo apt-get install git
git clone https://github.com/pivotal-sprout/sprout-wrap.git
cd sprout-wrap
./sprout
```
