# Changelog

## 2.0.0 (unreleased)

  * Removes support for Ruby 1.8.7.
  * Moves renderer into an after_initialize block so the Rails app is
    loaded before it tries to register itself. Should fix intermittent
    issues with it not working in production environments.
  * Use Ruby's CSV library instead of manually building strings.

## 1.0.0

  * Initial Release
