# Eastasianwidth::Rails

gem for (eastasianwidth.js)[https://github.com/komagata/eastasianwidth]

## Installation

Add this line to your application's Gemfile:

    gem 'eastasianwidth-rails'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install eastasianwidth-rails

## Usage

Add the follow line in app/assets/javascripts/application.js

    //= require eastasianwidth

    eastasianwidth.length("あaいbうcえdおe") // 15

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
