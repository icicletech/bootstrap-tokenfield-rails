# Bootstrap Tokenfield Gem for Rails

This gem tokenizes your input field, allowing the user to input and manage multiple values into the input field effortlessly, by [Icicle](http://www.icicletech.com).

For more information on this gem visit [Bootstrap Tokenfield Rails gem](http://www.icicletech.com/open-source-software/bootstrap-tokenfield-rails).

## Installation


Add this line to your application's Gemfile:

    gem 'bootstrap_tokenfield_rails'


And then execute:

    $ bundle install

Or install it yourself as:

    $ gem install bootstrap_tokenfield_rails

Add this line to your application.js file

    //= require bootstrap-tokenfield

Add this line to your application.css file

    *= require bootstrap-tokenfield

## Features

* Copy & paste tokens with Ctrl+C and Ctrl+V
* Keyboard navigation, delete tokens with keyboard (arrow keys, Shift + arrow keys)
* Select specific tokens with Ctrl + click and Shift + click
* Twitter Typeahead and jQuery UI Autocomplete support

## Usage

Given an input field, add a class of your choice to it.

    <input type="text" class="tokenize">

Then tokenize the input field as follows.

    $('input.tokenize').tokenfield();

Check out the [demo and docs](http://sliptree.github.io/bootstrap-tokenfield/).

## Screenshot

![](http://i.imgur.com/eRvIWIy.png)

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Contributors

[Akash Devaraju](https://github.com/akashdevaraju)

[Ragulka](https://github.com/ragulka)
### License

Available under the MIT License.

## About Icicle Technologies

![Icicle Technologies](https://cdn2.icicletech.com/assets/icicle-698e4eaeca5518499068468bc3ba5680.png)
