# @marijn/testtool

Utility for running collections of Mocha test files that contain both
Node-based and browser-based tests.

## API

 * **`gatherTests`**`(dirs: string[]) → {tests: string[], browserTests: string[]}`\
   Find `test/test-*.js` and `test/webtest-*.js` in the given
   directories.

 * **`runTests`**`(input: {tests: string[], browserTests: string[], browsers: string[], grep?: string}) → Promise<void>`\
   Run the given set of tests, optionally filtering by name with
   `grep`, or configuring which browsers to run the web tests on.

## Community

This is open source software released under an
[MIT license](https://github.com/marijnh/testtool/blob/master/LICENSE).

Development happens on
[GitHub](https://github.com/marijnh/testtool/). Use the [bug
tracker](https://github.com/marijnh/testtool/issues) to report
problems.
