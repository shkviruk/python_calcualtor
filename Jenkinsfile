pipeline {
	agent any
	stages {
		stage("Run the code!") {
			steps {
				sh """
					python calculator.py
				"""
			} //steps
		} //stage
		stage("RUn unit tests") {
			steps {
				sh """
					pytest
				"""
			} //steps
		} //stage
	} //stages
} //pipeline

