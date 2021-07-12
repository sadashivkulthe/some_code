pipeline {
  agent any
	triggers {
	   githubPush()
	} 
 
  stages { 
    stage ('Production branch echo') {
      steps {
        echo "Namaste"
      }
    }
  }
  
}
