pipeline {
  agent any
	trigger {
	   githubpush()
	} 
 
  stages { 
    stage ('Production branch echo') {
      steps {
        echo "Namaste"
      }
    }
  }
  
}
