Heroku buildpack: tdlib
=======================

## !!! This buildpack does not work !!!

### Usage

Add Heroku Apt buildpack

```
heroku buildpacks:add --index 1 https://github.com/heroku/heroku-buildpack-apt
```

Add file named 'Aptfile' to your app root folder with this inside:

```
make git zlib1g-dev libssl-dev gperf php-cli cmake clang-6.0 libc++-dev libc++abi-dev
```
