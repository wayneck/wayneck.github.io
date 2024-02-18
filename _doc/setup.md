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