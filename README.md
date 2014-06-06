# Guard::Bundler::Audit

[guard](https://github.com/guard/guard) + [bundler-audit](https://github.com/rubysec/bundler-audit) =  [security](http://www.rubysec.com/)

## Installation

Add this line to your application's Gemfile:

    gem 'guard-bundler-audit'

Then execute:

    $ bundle

Alternatively, install it without bundler:

    $ gem install guard-bundler-audit

## Usage

    guard 'bundler_audit', run_on_start: true do
      watch('Gemfile.lock')
    end

## Contributing

1. Fork it ( http://github.com/<my-github-username>/guard-bundler-audit/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
