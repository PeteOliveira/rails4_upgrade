# rails4\_upgrade [![Build Status](https://secure.travis-ci.org/alindeman/rails4_upgrade.png?branch=master)](http://travis-ci.org/alindeman/rails4_upgrade)

Helps you more easily upgrade to Rails 4. A work in progress, I'm simply
shipping something of a minimum viable product to attract others to
contribute.

Inspired by [rails_upgrade](https://github.com/rails/rails_upgrade) which
helped upgrade applications from Rails 2 to Rails 3.

## Installation

Upgrade to Ruby 1.9.3 if your application does not already use it. Rails 4
requires Ruby 1.9.3, and `rails4_upgrade` uses 1.9-only syntax and semantics.

Add to `Gemfile`:

    gem 'rails4_upgrade', github: 'alindeman/rails4_upgrade'

## Usage

List gems that would currently prevent you from upgrading to Rails 4:

    rake rails4:check_gems

## Contributing

I'm open to accepting pull requests that improve the functionality of the gem.

If there's an upgrade procedure that can be automated or semi-automated, let's
discuss it. Open an
[issue](https://github.com/alindeman/rails4_upgrade/issues).

Ideas:

* Recommending versions of gems that may be compatible with Rails 4
* Removing deprecated configuration options
* Adding newly required or recommended configuration options
