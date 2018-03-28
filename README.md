# heroku-buildpacks-sourceversion
Writes the `SOURCE_VERSION` environment variable (usually the Git SHA) to a file for use at runtime.

## Usage
To use this buildpack, the app should already be successfully running the [multi buildpack](https://github.com/heroku/heroku-buildpack-multi) setup.

Then just add this buildpack to your buildpacks config:

	https://github.com/maxcountryman/heroku-buildpack-sourceversion.git

At runtime, your application can read `.commit_hash`.

## License
MIT
