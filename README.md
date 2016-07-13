# Ruboty::Capistrano

RubotyでCapistranoを使って、deployするためのgemです.


## Installation

Add this line to your application's Gemfile:

```ruby
gem 'ruboty-capistrano'
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install ruboty-capistrano

## Usage

![usage](https://cloud.githubusercontent.com/assets/1563239/16789796/6aa5a088-48eb-11e6-9422-fc98904255a9.jpg)


## Env

```
RUBOTY_ENV              - deploy先の環境を指定する
DEFAULT_BRANCH          - deploy時において、branch指定されていなかった場合に、deployするdefaultのbranch
DEPLOY_REPOSITORY_PATH  - deploy対象のrepositoryのpath
(ex: "sample:/path/to/sample;admin:/path/to/admin")
```

## License

The gem is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).

