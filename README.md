# heroku-buildpack-sourceversion

Makes the commit ID, i.e. `SOURCE_VERSION`, available to your application at runtime by writing out to a file.

## Usage
Simply add this buildpack to your application's configuration:

	https://github.com/maxcountryman/heroku-buildpack-sourceversion.git

At runtime your application can read the `.commit_id` file--this will contain the contents of `SOURCE_VERSION` as it existed during build.

## License
MIT
