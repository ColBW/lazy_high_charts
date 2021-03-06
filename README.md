# LazyHighCharts - Official gem repository

Easily include HighCharts in your project with this gem
[![Build Status](https://secure.travis-ci.org/michelson/lazy_high_charts.png)](http://travis-ci.org/michelson/lazy_high_charts)

## Notice
Current
[VERSION](https://github.com/michelson/lazy_high_charts/blob/master/GEM_VERSION)
[ChangeLog](https://github.com/michelson/lazy_high_charts/blob/master/CHANGELOG.md)

## Installation

### Installation with rubygems

To install it, you just need to add it to your Gemfile:

```ruby
    gem 'lazy_high_charts'
```

then run

```bash
bundle install
```

to install it.

### legacy notice: if you use rails 2.3.x or 3.0.x or 3.1.x, please use versions less than 1.3.3.

##  Lazy_high_charts User Guide

Add javascript file to the application.js file
//= require highcharts

###In controller
Create an object of 
```ruby
LazyHighCharts::HighChart
```


###In View
Just pass the “div id” created and the “chart object”, where to display the chart
```ruby
  <%= high_chart(“div_id”, @chart) %>
```

## Contributing

We're open to any contribution. It has to be tested properly though.

* [Fork](http://help.github.com/forking/) the project
* Do your changes and commit them to your repository
* Test your changes. We won't accept any untested contributions (except if they're not testable).
* Create an [issue](https://github.com/michelson/lazy_high_charts/issues) with a link to your commits.

Thanks for all [contributers](https://github.com/michelson/lazy_high_charts/contributors)

## Maintainers
* Deshi Xiao [github/xiaods](https://github.com/xiaods)
* Miguel Michelson [github/michelson](https://github.com/michelson)

## License
* Copyright (c) 2013 [Deshi Xiao](http://xiaods.mit-license.org) - Miguel Michelson Martinez, released under the MIT license
