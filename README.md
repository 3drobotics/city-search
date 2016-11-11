# city-search

Check out the **[Demo](https://3drobotics.github.io/city-search/)**

This is an application meant to be used as an interviewing challenge for interviewing front-end candidates. Feel free to fork it and mess with it or whatever you like! 

This is a demo application made in React.js. This build configuration is derived from [https://github.com/genarorg/webpack-react-redux](https://github.com/genarorg/webpack-react-redux).

Download the built application here: [city-search.v1.0.0](https://github.com/genarorg/city-search/releases/tag/v1.0.0)

To run this application locally, install dependencies first with:

``` bash
npm install
```

Then you can run it, and it will be available at [http://localhost:8080/](http://localhost:8080/).

``` bash
npm run start

> dkc-web@1.0.0 start /Users/genarorg/Work/3dr/cloud-web
> webpack-dev-server --inline --content-base . --history-api-fallback

http://localhost:8080/
webpack result is served from /
content is served from /Users/genarorg/Work/3dr/cloud-web
404s will fallback to /index.html
webpack: wait until bundle finished: /
Child html-webpack-plugin for "index.html":

webpack: bundle is now VALID.
```
note: due to a config issue, webpack-dev-server wont load the background image, but its fine in the build.

Or if you want to build it, just run `npm run build` and your files will be in the `/build` folder:

``` bash
npm run build
```

