# Middleman with Nanobox

This is the companion application for the [Middleman: Getting Started](https://guides.nanobox.io/middleman/) guide on [guides.nanobox.io](https://guides.nanobox.io) and is pre-configured and ready to run with [Nanobox](https://nanobox.io/)!

## Up and Running

``` bash
# clone the code
git clone https://github.com/nanobox-quickstarts/nanobox-middleman.git

# cd into the sinatra app
cd nanobox-middleman

# build the code
nanobox build

# start the dev environment
nanobox dev start

# add a convenient way to access your app from the browser
nanobox dev dns add middleman.nanobox.dev

# console into the dev environment
nanobox dev console

# install gems
bundle install

# run middlmean server
bundle exec middleman server
```

Visit the app from your favorite browser at: `middleman.nanobox.dev:4567`.

## Now What?
For more details about how this works or for more advanced topics related to running Middleman applications with Nanobox visit [guides.nanobox.io/middleman/](https://guides.nanobox.io/middleman/).
