# Sweetalertjs::Rails

Sweet Alert : A BEAUTIFUL REPLACEMENT FOR JAVASCRIPT'S "ALERT"

This gem is wrapping sweetAlert.js for Rails integration

## Installation

Add this line to your application's Gemfile:

```ruby
gem 'sweetalertjs-rails'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install sweetalertjs-rails

## Usage

In `app/assets/javascripts/application.js`, insert the following codeline:

```
//=require sweetalert.min
```

In `app/assets/stylesheets/application.scss`, insert the following codeline:

```
@import 'sweetalert';
```

And then, in javascript files, write 'swal()' function in proper position.

```js
swal("Here's a message!");
```

If you want more examples, refer to the sweetAlert website : http://t4t5.github.io/sweetalert/

## Development

After checking out the repo, run `bin/setup` to install dependencies. Then, run `bin/console` for an interactive prompt that will allow you to experiment.

To install this gem onto your local machine, run `bundle exec rake install`. To release a new version, update the version number in `version.rb`, and then run `bundle exec rake release` to create a git tag for the version, push git commits and tags, and push the `.gem` file to [rubygems.org](https://rubygems.org).

## Contributing

1. Fork it ( https://github.com/[my-github-username]/sweetalertjs-rails/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
