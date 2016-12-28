alexmcnurlin.github.io
======================

This is my website! Built with love, tears, and Bootstrap 3. Mostly Bootstrap 3

# Setting up and deploying

## First time setup
clone the repo into the current directory (This will create a folder called alexmcnurlin.github.io in the current directory)

```
git clone https://www.github.com/alexmcnurlin/alexmcnurlin.github.io
```

Install the following

* [`bundle`](http://bundler.io/)
	- bundle Requires [RubyGems](https://rubygems.org/pages/download)
		* RubyGems requires [Ruby](https://www.ruby-lang.org/en/documentation/installation/) (I'd reccomend installing with [rvm](https://rvm.io/))
	- One RubyGems is installed, run `gem install bundler`
* ['bower'](http://bower.io/)
	- Bower requires [node.js](https://nodejs.org/en/download/) (I'd recommend installing nodejs with [nvm](https://github.com/creationix/nvm))

## Get Dependencies

``` bash
bundle install
bower install
```

## Build the website/run server

```
jekyll serve -w
```

The site will be viewable at [http://localhost:5277](http://localhost:5277)!
