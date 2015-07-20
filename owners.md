###Steps to contribute
1. First, clone the repo and switch to the correct branch
    * git clone https://github.com/mujeresentecnologiaEC/mujeresentecnologiaEC.github.io.git
    * cd mujeresentecnologiaEC.github.io
    * git checkout source
2. Then, setup the _deploy directory:
    * mkdir _deploy
    * cd _deploy
    * git init
    * git remote add -t master -f origin https://github.com/mujeresentecnologiaEC/mujeresentecnologiaEC.github.io.git
3. Install dependencies needed:
    * cd mujeresentecnologiaEC.github.io
    * gem install bundler
    * rbenv rehash (If you use rbenv, rehash to be able to run the bundle command)
    * bundle install 