# jestit
Learning how to test JavaScript with jest and Puppeteer.

## Background
To date I have written 16 block plugins delivering 48 blocks.
I haven't learnt how to write automated unit tests or e2e tests.
It's about time I did.

So I'm going to start with some simple JavaScript and work my way up 
to testing Gutenberg blocks. 

## Requirements

- [ ] To be able to unit test the JavaScript in my WordPress blocks.
- [ ] To be able to End-to-End test my WordPress blocks.
- [ ] To be able to run the tests during regression testing.
- [ ] To be able to test l10n and i18n.
- [ ] Method should be simple enough to retrofit into existing plugins/blocks.

## Proposed solution

- [ ] Use Jest for unit testing JavaScript.
- [ ] Use Snapshot testing, if necessary.
- [ ] Use Puppeteer for End-to-End testing.

## Assumptions & Constraints
- I can start by using my existing development setup.
- I don't need a `wp-env` installation, whatever that is. 
- I can use PhpStorm to invoke the tests.
- I can use the command line to invoke the tests.
- I can write JavaScript that I actually understand.
- I don't need to test every single line of code.
- That I'll learn something.
- That my code will improve.
- That I'll be able to use the test suite to migrate from hand cranked to more modern tooling and APIs.

## Installation?
Prerequisite: install node.js and npm.

Follow the instructions from https://jestjs.io/docs/getting-started

```
cd \path\to\jestit
npm install jest --save-dev
```

This creates the `node_modules` folder and `package-lock.json`.

1. Install jest
2. Create `sum.js` and `sum.test.js``   
3. Update `package.json` to add the run command for jest
4. npm run test
```
C:\apache\htdocs\wordpress\wp-content\plugins\jestit>npm run test

> @ test C:\apache\htdocs\wordpress\wp-content\plugins\jestit
> jest

PASS  src/sum.test.js
√ adds 1 + 2 to equal 3 (2 ms)

Test Suites: 1 passed, 1 total
Tests:       1 passed, 1 total
Snapshots:   0 total
Time:        7.804 s
Ran all test suites.
```

## References
- [Block Editor Handbook: Testing Overview](https://developer.wordpress.org/block-editor/contributors/code/testing-overview/)
- [Jest](https://jestjs.io/)
- [@wordpress/create-block](https://github.com/WordPress/gutenberg/tree/trunk/packages/create-block)  
- tbc

## My block plugins

Plugin | # blocks/variations | Notes
------ | -------- | ------
bigram | 1 | @wordpress/create-block, seen-before, apiVersion: 2
oik  |  6  | Hand cranked webconfig
oik-blocks | 20 | Hand cranked webconfig
oik-bob-bing-wide | 5 | Hand cranked webconfig
oik-css | 2 | Hand cranked webconfig
oik-magnetic-poetry | 1 |  Hand cranked
oik-squeeze | 1 |  @wordpress/create-block
sb-breadcrumbs-block | 1 | @wordpress/create-block
sb-chart-block | 1 | @wordpress/create-block
sb-children-block | 1 | @wordpress/create-block
sb-coming-up | 1 | @wordpress/create-block
sb-field-block | 1 | @wordpress/create-block
sb-parent-block | 1 | @wordpress/create-block
sb-prevnext-block | 1 | @wordpress/create-block
sb-toolicons-block | 4 | @wordpress/create-block
uk-tides | 1 | Hand cranked webconfig
wp-top-12 | 1 | @wordpress/create-block





