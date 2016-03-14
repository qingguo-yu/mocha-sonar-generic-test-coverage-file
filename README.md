# mocha-sonar-generic-test-coverage-file
Basically the same reporter as mocha-sonar-generic-test-coverage reporter(https://github.com/mageddo/mocha-sonar-generic-test-coverage), but writes the output to a file. And some issues fixed.
Why we need to do that? The logging output in the test cases can pollute the final report file when we use capture keyword in grunt.
By default, the output file would be "gunit.xml" located in root folder of the same project.
