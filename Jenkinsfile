pipeline {
    agent any
    stages {
	stage('scm checkout')
	    {steps {git branch: 'master', url: 'https://github.com/nangareashu29/maven-project.git'}}
	    stage('execute unit test framework')
	    {steps {withMaven(globalMavenSettingsConfig: '6459bc23-432b-4d77-871f-920eb8e310c7', jdk: 'JDK_HOME', maven: 'MAVEAN_HOME', mavenSettingsConfig: 'cf88886e-bb8c-4929-8b97-a6eb102e4bdc') {
    // some block
}}}
	}
	}
