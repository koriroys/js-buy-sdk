# How to contribute
We ❤️ pull requests. If you'd like to fix a bug, contribute a feature or
just correct a typo, please feel free to do so, as long as you follow
our [Code of Conduct](https://github.com/Shopify/js-buy-sdk/blob/master/CODE_OF_CONDUCT.md).

If you're thinking of adding a big new feature, consider opening an
issue first to discuss it to ensure it aligns to the direction of the
project (and potentially save yourself some time!).

## Getting Started
To start working on the codebase, first fork the repo, then clone it:
```
git clone git@github.com:your-username/js-buy-sdk.git
```
*Note: replace "your-username" with your Github handle*

Install the project's dependencies:
```
npm install
```

Run the server:
```
npm start
```
Add some tests and make your change. Re-run the tests with:
```
npm run test
```

## Examples
See [here](https://github.com/Shopify/js-buy-sdk/blob/master/examples) for our examples.

## Documentation
If your change affects how people use the project (i.e. adding or
changing arguments to a function, adding a new function, changing the
return value, etc), please ensure the documentation is also updated to
reflect this. To serve docs run the following command:

```
npm run doc:serve
```

If this command succeeds you can read the docs at:
http://127.0.0.1:4000/js-buy-sdk/

If you have issues running the above command do the following:

Install `rbenv` which manages your local `ruby` environment. For installation instructions checkout this url: 
https://github.com/rbenv/rbenv#installation

On OSX to install `rbenv` do:
```
$ brew install rbenv
```

After installing `rbenv` you will need to follow the init/setup instructions returned by this command:
```
$ rbenv init
```

Restart terminal. Then run the following commands:
```
$ rbenv install 2.3.0 # install ruby version 2.3.0
$ rbenv global 2.3.0 # set your global ruby version to be 2.3.0
$ gem install bundler # installs bundler globally
$ npm run doc:serve # finally you can serve docs
```

The documentation will then be visible at
`http://localhost:4000/js-buy-sdk/index.html`
