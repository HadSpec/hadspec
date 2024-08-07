# hadspec
Hadron Spectrum Collaboration Public Webpage

_____


Instructions for building a local version for testing:

MacOS: brew install ruby (this provides “gem”)

Linux: apt-get install ruby

gem install jekyll

gem install bundler

git clone git@github.com:JeffersonLab/hadspec

cd hadspec

bundle install

cd docs

jekyll build

jekyll serve

then in your favourite web browser you can type:

http://127.0.0.1:4000
