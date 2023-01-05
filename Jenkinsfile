pipeline {
    agent any
    stages {
	stage('scm checkout')
	    {steps {git branch: 'master', url: 'https://github.com/nangareashu29/maven-project.git'}}
	    stage('execute unit test framework')
	    {steps {withMaven(globalMavenSettingsConfig: '--- Use system default settings or file path ---', jdk: 'JDK_HOME', maven: 'MAVEAN_HOME', mavenSettingsConfig: '--- Use system default settings or file path ---') {
    // some block
}}
	}
	}
