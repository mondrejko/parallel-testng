Sample project to demonstrate issue at https://github.com/gradle/gradle/issues/3190

`> gradlew test`

Then examine ./build/reports/tests/test/testng-results.xml to see that it contains only partial results
(should show 20 test method executions). It seems that this result file contains results from one a single
test executor.
