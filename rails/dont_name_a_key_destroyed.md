Don't name a key `:destroyed` in Rails, unfortunately it's an instance variable that's set when a record is
deleted.

From [here](https://github.com/rails/rails/blob/2e465e138b09b948ea266a7a5e739436cb01f3a9/activerecord/lib/active_record/persistence.rb#L185).
