To view
-------
Visit [http://ardell.github.io/bread/](http://ardell.github.io/bread/)

To run locally
--------------
- clone this repository
- `cd bread`
- `git checkout -b gh-pages origin/gh-pages`
- `echo 2.5.1 > .ruby-version`
- `echo bread > .ruby-gemset`
- `cd .. && cd bread`
- `gem install bundler && bundle install`
- `jekyll serve`
- navigate to [http://localhost:4000/bread](http://localhost:4000/bread)

