# Look ma, no (npm) registry!

Did you know you can install packages directly from GitHub repos, without publishing them to the npm registry?

This is a little demo repo/package to show off how that works. 


## Install from GitHub

You can install this package directly from GitHub like this:

```
npm install zeke/look-ma-no-registry
```

## Execute from GitHub

You can also you use npx to run packages directly from GitHub:

```
npx zeke/look-ma-no-registry
```

## Why?

This is really handy if you are developing a package and want to share it with testers before it's ready for primetime, or if you're building an internal tool and want to keep it in a private GitHub organization, so only your teammates can access it.
