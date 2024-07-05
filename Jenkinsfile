node {
	stage('clone'){
		git branch: 'main', url: 'https://github.com/Enzo121212/jenkinsTest.git'
	}
	stage('build'){
		bat "javac Main.java"
	}
	stage('run'){
		bat "java Main"
	}	
}
