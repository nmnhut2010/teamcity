##teamcity[testStarted name='testName']
here go all the test service messages with the same name
##teamcity[testFinished name='testName' duration='300']
##teamcity[testStarted name='testName2']
##teamcity[testFailed name='testName2' message='failure message' details='message and stack trace']
##teamcity[testFinished name='testName2' duration='30']