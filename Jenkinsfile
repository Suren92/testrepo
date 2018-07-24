pipeline {
	agent any
	
	stages {
		stage('Test') {
			steps { 
				def propertiesFile= readJSON file "testjson.json"
				bat ' echo "Heelo"' 
			}
		}
	}
}