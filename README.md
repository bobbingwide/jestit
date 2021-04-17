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


## References
- [Block Editor Handbook: Testing Overview](https://developer.wordpress.org/block-editor/contributors/code/testing-overview/)
- [Jest](https://jestjs.io/)
- tbc

## My block plugins

Plugin | # blocks | Notes
------ | -------- | ------
bigram | 1 | Seen-before, apiVersion: 2
oik    |  6        | Hand cranked webconfig
oik-blocks | 20 | Hand cranked webconfig
oik-bob-bing-wide | 5 | Hand cranked webconfig
oik-css | 2 | Hand cranked webconfig
oik-magnetic-poetry | 1 |  
oik-squeeze | 1 | 
sb-breadcrumbs-block | 1 | 
sb-chart-block | 1 |
sb-children-block | 1 |
sb-coming-up | 1 | 
sb-field-block | 1 |
sb-parent-block | 1 |
sb-toolicons-block | 4 | 
uk-tides | 1 |
wp-top-12 | 1 | 





