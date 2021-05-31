##### Prerequisites

The setup steps expect following tools installed on the system.

- Github
- Ruby [2.7.0](https://github.com/furqanharoon/bitcoin_task/blob/master/.ruby-version#L1)
- Rails [6.1.3]

##### 1. Check out the repository

```bash
git clone git@github.com:furqanharoon/bitcoin_task.git
```


##### 2. Install gems from Gemfile

Run the following commands. First one is to install bundler gem and second to install gems from Gemfile

```ruby
gem install bundler -v 2.2.4
```
```ruby
bundle install
```

##### 4. Start the Rails server

You can start the rails server using the command given below.

```ruby
rails s
```

And now you can visit the site with the URL http://localhost:3000
