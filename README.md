# Multi::Analytics::Turbolinks

Turbolinks page changes are often not detected with event tracking frameworks such as
Google Analytics, Baidu Tongji and Bing UET.

Facebook's Pixel appears to work with turbolinks without problems.

These analytics and ad/event tracking products are also the
worlds largest search providers. This gem adds support to fire these
events on page changes, to more accurately work with turbolinks.

**Use with Rails and Asset Pipeline**

## Installation

Add this line to your application's Gemfile:

    gem 'multi-analytics-turbolinks'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install multi-analytics-turbolinks

## Usage

Signup to

  * [Google Analytics](http://analytics.google.com/)
  * Baidu Tongji [join](http://tongji.baidu.com/open/api/more?p=howToJoin) and [login](http://tongji.baidu.com/web/welcome/login)
  * [Bing UET](https://secure.bingads.microsoft.com/) (credit-card not required)

Add the JS you need to your Javascript manifest file (typically application.js)

```html
	//= require google-analytics-turbolinks
	//= require baidu-tongji-turbolinks
	//= require bing-uet-turbolinks
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

##License

Check LICENSE, MIT.
