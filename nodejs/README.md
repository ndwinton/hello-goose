# Hello Goose - NodeJS

The NodeJS version of the application has few external dependencies and requires no configuration. Just run `cf push` to use.

If you are deploying in an environment where the buildpack will not be able to fetch libraries from the cheese shop, then you will have to vendor the dependencies. See [the docs](https://docs.cloudfoundry.org/buildpacks/node/index.html#vendoring).
