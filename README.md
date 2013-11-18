# Bootstrap-Slider-Rails

This Gem integrates [Seiyara's fork](https://github.com/seiyria/bootstrap-slider) of [Bootstrap Slider](http://www.eyecon.ro/bootstrap-slider/). The original has no public Github Repo, issues tracking etc.

It integrates this fork with your Rails project and is versioned to track the fork's versioning.

## Installation

Add this line to your application's Gemfile:

    gem 'bootstrap-slider-rails'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install bootstrap-slider-rails

## Usage

This gem uses a Rails Engine to make Bootstrap Slider's assets available to you.

Require the JavaScript files from your `application.js` or wherever needed using:

```
//= require bootstrap-slider
```

Require the CSS files from your `application.scss` or wherever needed using:

```
*= require slider
```

*Note: This naming inconsistancy is part of Bootstrap Slider. I have opened a ticket [here](https://github.com/seiyria/bootstrap-slider/issues/41)

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
