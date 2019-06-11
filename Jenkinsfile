node{
	stage('Code CheckOut From Git'){
		git credentialsId: 'RubanGitCredentials', url: 'https://github.com/rubanmoses/Ruban_JenkineFile_Example.git'
	}
	stage('Java Code Build'){
      sh "javac HelloWorld.java"
   }
   stage('Java Code Run'){
      sh "java HelloWorld"
   }
   stage('Show Success Message'){
      sh "echo Pipeline Working Fine"
   }
}
