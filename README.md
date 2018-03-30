# heroku-buildpack-sourceversion

Makes the commit ID, i.e. `SOURCE_VERSION`, available to your application at runtime by writing out to a file.

## Usage
To use this buildpack, the app should already be successfully running the [multi buildpack](https://github.com/heroku/heroku-buildpack-multi) setup.

Then just add this buildpack to your buildpacks config:

	https://github.com/maxcountryman/heroku-buildpack-sourceversion.git

At runtime, your application can read the `.commit_id` file.

## License
MIT
