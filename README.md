# cf-buildpack-multi

Use multiple buildpacks on your app

## Usage

    $ cat .buildpacks
    https://github.com/cloudfoundry/nodejs-buildpack#v1.5.19
    https://github.com/cloudfoundry/ruby-buildpack#v1.6.24

    $ cf push -b https://bitbucket.org/cf-utilities/cf-buildpack-multi

## License

Originally imported to https://bitbucket.org/cf-utilities/cf-buildpack-multi from https://github.com/ddollar/heroku-buildpack-multi with a MIT license @ commit 331b0277c8b091fb3580a543e18ad5f1fe4532f5.

Subsequent modifications licensed under the GPL, version 3 or later.

Imported to https://github.com/Comcast/cf-buildpack-multi from https://bitbucket.org/cf-utilities/cf-buildpack-multi @ commit 2b58527b8a9026b7a71d4d2f803cd2cf5a14fbf7
