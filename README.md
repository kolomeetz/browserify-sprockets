== README

This repository reproduces [the problem](https://github.com/browserify-rails/browserify-rails/issues/135) with browserify-rails (1.0.2) and sprockets 3.7.0.

Clone the repository, run `bundle`, launch `rails s`:

```
→ rails s
=> Booting WEBrick
=> Rails 4.2.7.1 application starting in development on http://localhost:3000
=> Run `rails server -h` for more startup options
=> Ctrl-C to shutdown server
Exiting
/Users/kolomeetz/.gem/ruby/2.3.0/gems/browserify-rails-1.0.2/lib/browserify-rails/railtie.rb:33:in `block in <class:Railtie>': undefined method `register_postprocessor' for nil:NilClass (NoMethodError)
```


