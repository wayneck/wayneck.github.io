``` log
bundle install 
Fetching gem metadata from https://rubygems.org/............
Resolving dependencies...
Installing safe_yaml 1.0.5
Installing kramdown 2.4.0
Installing rouge 4.2.0
The installation path is insecure. Bundler cannot continue.
/home/wayne/pack/lib/ruby/gems/3.3.0/gems is world-writable (without sticky bit).
Bundler cannot safely replace gems in world-writeable directories due to potential vulnerabilities.
Please change the permissions of this directory or choose a different install path.
```

sudo chmod +t /tmp


## write something to _post dir

bundle exec jekyll serve

git add .
git comm -am "xxxx"
git push origin main



# error deal
``` log
git push -u main 
Username for 'https://github.com': debugos@163.com
Password for 'https://debugos@163.com@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
```
the error case by git authentication,
(see it)[https://blog.csdn.net/qq_32512573/article/details/113252407]
### just do
``` log 
git remote add main 远程的项目地址
git push origin main
```
