# AngularJS - Testing Article
This is a helper repository which is designed to be used alongside the blog article on yearofmoo.com.

## Blog Article
Click the link below to view the blog article which explains exactly what and how this application is used.

http://www.yearofmoo.com/2013/01/full-spectrum-testing-with-angularjs-and-karma.html

## Using the application

Install grunt
`npm install -g grunt-cli`

And then be sure to install everything that the repo requires:
`npm install`
`bower install`

### Development Mode

Run the following command to start the server
`grunt server`

You can now access the website at
`http://localhost:8000`

### End to end tests 

To run all e2e tests once `grunt test:e2e'

You should see Chrome browser open, run through UI and close

### End to end tests using global karma

Should be equivalent to `grunt test:e2e`

1. Install karma runner `npm install -g karma`
2. `grunt server`
3. `karma start test/karma-e2e.conf.js --single-run`

