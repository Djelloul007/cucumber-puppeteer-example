# cucumber + "Google Chrome puppeteere" example

Write UI tests using Gherkin, Cucumber, and Puppeteer. This example is an example project on how to use [cucumber](https://github.com/cucumber/cucumber-js) with [puppeteer](https://github.com/GoogleChrome/puppeteer)  and [puppeteer-to-istanbul] (https://github.com/istanbuljs/puppeteer-to-istanbul) to generate test coverage.

The world.js file lives inside the /features/support/ folder, and is loaded automatically when running Cucumber  

to run the test 
- npx cucumber-js -f json:cucumber_report.json 

or 

- npm test     
- and to open the HTML report   node report.js 

or

Run `yarn` to get the dependencies and then run `yarn test` to execute the UI tests.

The `yarn test` command will generate a JSON report file. You can use the `yarn test:report` command to check the HTML report.
"# cucumber-puppeteer-example" 


to generate test coverage using puppeteer-to-istanbul
- install nyc, npm i nyc -g 
and then 
- nyc report --reporter=html 
