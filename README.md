# Readme mujeresentecnologiaEC.github.io

###Before you begin
1. You need to make sure that you have:
    * Installed Git.
    * Installed Ruby 1.9.3 or greater using either rbenv or RVM. (If ruby --version doesn't say you're using Ruby at least 1.9.3, revisit your rbenv or RVM installation.)
    * Installed one of the ExecJS supported JavaScript runtimes.

###Steps to clone the Repository
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

###Blogging with Octopress:
1. To create a new post:
    * rake new_post["title"]

Example: rake new_post["Zombie Ninjas Attack: A survivor's retrospective"]

This will create a post in source/_posts/2011-07-03-zombie-ninjas-attack-a-survivors-retrospective.markdown

2. Go to source/_posts/YYYY-MM-DD-post-title.markdown
3. Write your post after the --- line right below Categories.
4. Save it, make a commit and send a pull request!

####That's all you need to do to start blogging in our page. We'll be updating our blog page soon in order to make it nicer :)
