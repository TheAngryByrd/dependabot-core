## `dependabot-paket`

Paket support for [`dependabot-core`][core-repo].

### Running locally

1. Install native helpers
  ```
    cd helpers && build "$(pwd)/helpers/install-dir/paket"  && cd -
  ```

2. Install Ruby dependencies
   ```
   $ bundle install
   ```

3. Run tests
   ```
   $ bundle exec rspec spec
   ```

[core-repo]: https://github.com/dependabot/dependabot-core