#!groovy
library 'pipeline-library'

def isMaster = env.BRANCH_NAME.equals('master')

buildModule {
	sdkVersion = '9.0.0.v20200205134519' // TODO: Change to 9.0.0.GA once released
	npmPublish = isMaster
}
