# cf-buildpack-multi

Use multiple buildpacks on your app

## Usage

    $ cat .buildpacks
    https://github.com/cloudfoundry/nodejs-buildpack#v1.5.19
    https://github.com/cloudfoundry/ruby-buildpack#v1.6.24

    $ cf push -b https://bitbucket.org/cf-utilities/cf-buildpack-multi

## License

Originally imported from https://github.com/ddollar/heroku-buildpack-multi with
a MIT license @ commit `331b0277c8b091fb3580a543e18ad5f1fe4532f5`.

Subsequent modifications licensed under the GPL, version 3 or later.
