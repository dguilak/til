If you're using a gem and they haven't updated the version yet, you can have bundler install a specific commit
or ref from the actual repository instead of installing from rubygems.

```
gem 'mongo_mapper', git: 'https://github.com/mongomapper/mongomapper', ref: 'HEAD'
```

[Source](http://bundler.io/git.html)
