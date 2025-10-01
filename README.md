# Blastpoint, Inc. Tap

## How do I install these formulae?

`brew install blastpoint-inc/tap/<formula>`

Or `brew tap blastpoint-inc/tap` and then `brew install <formula>`.

Or, in a `brew bundle` `Brewfile`:

```ruby
tap "blastpoint-inc/tap"
brew "<formula>"
```


### Install Postgis @ 3.6.0 with Postgresql@14 support


```sh
# Uninstall previous postgis (from homebrew/core)
brew uninstall postgis

# Install this tap's postgis formula which has postgresql@14 support
brew install blastpoint-inc/tap/postgis@3.6.0

# Restart postgresql brew service
brew service restart postgresql
```

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
