Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any
    stages {
        stage('Example Build') {
            steps {
                withMaven()maven: "maven_3.6")
		sh 'mvn clean compile'
            }
        }
        stage('Example Deploy') {
             steps {
                withMaven()maven: "maven_3.6")
		sh 'mvn test'
            }
        }
    }
}
