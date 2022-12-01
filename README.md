## Pre-requisites
- Ruby version: `3.1.2`
- Bundler version `2.3.25`

## Install
clone the repo and run 
```
bundle install
```

In case eventmachine fails to install, run
```
gem install eventmachine -- --with-cppflags=-I/usr/local/opt/openssl/include
```

## Run
Run the server localy with
```
bundle exec jekyll serve --livereload --baseurl=""
```
