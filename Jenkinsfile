pipeline {
    agent any
    stages {
	stage('scm checkout')
	    {steps {git branch: 'master', url: 'https://github.com/nangareashu29/maven-project.git'}}
	    stage('execute unit test framework')
	    {steps {withMaven(globalMavenSettingsConfig: '6459bc23-432b-4d77-871f-920eb8e310c7', jdk: 'JDK_HOME', maven: 'MAVEAN_HOME', mavenSettingsConfig: '--- Use system default settings or file path ---') {
    // some block
}}}
	}
	}
