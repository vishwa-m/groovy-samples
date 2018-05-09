#!groovy
node{

stage('Checkout-Code'){
    checkout([$class: 'GitSCM', branches: [[name: 'master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'GITHUB_VISHWA', url: 'https://github.com/vishwa-m/groovy-samples.git']]])
    sh 'pwd'
	}
	
stage('Stage2'){
	sh 'pwd'

	}
}