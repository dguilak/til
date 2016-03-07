If you're testing an abstract controller in Rails, you can use the `controller` method in your spec to
instantiate an anonymous version of it that you can use to test.

```
controller(BaseController) do; end
```

This way, you don't need to create any dummy controllers to inherit from your `BaseController`, and you'll
DRY up your existing controller tests if you test all the abstract functionality together.

[Source](https://www.relishapp.com/rspec/rspec-rails/docs/controller-specs/anonymous-controller)
