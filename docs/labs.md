`heroku labs`
=============

disables an experimental feature

* [`heroku labs`](#heroku-labs)
* [`heroku labs:disable [FEATURE]`](#heroku-labsdisable-feature)
* [`heroku labs:enable FEATURE`](#heroku-labsenable-feature)
* [`heroku labs:info FEATURE`](#heroku-labsinfo-feature)

## `heroku labs`

list experimental features

```
USAGE
  $ heroku labs

OPTIONS
  -a, --app=app        app to run command against
  -r, --remote=remote  git remote of app to use
  --json               display as json
```

## `heroku labs:disable [FEATURE]`

disables an experimental feature

```
USAGE
  $ heroku labs:disable [FEATURE]

OPTIONS
  -a, --app=app        app to run command against
  -r, --remote=remote  git remote of app to use
  --confirm=confirm
```

_See code: [@heroku-cli/plugin-auth](https://github.com/heroku/heroku-cli-plugin-auth/blob/v0.6.0/src/commands/labs/disable.ts)_

## `heroku labs:enable FEATURE`

enables an experimental feature

```
USAGE
  $ heroku labs:enable FEATURE

OPTIONS
  -a, --app=app        app to run command against
  -r, --remote=remote  git remote of app to use
```

## `heroku labs:info FEATURE`

show feature info

```
USAGE
  $ heroku labs:info FEATURE

OPTIONS
  -a, --app=app        app to run command against
  -r, --remote=remote  git remote of app to use
  --json               display as json
```
