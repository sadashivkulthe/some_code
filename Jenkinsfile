pipeline {
  agent {
    label "master"
  }
  triggers {
 cron('* * * * *')
 }
  
  stages { 
    stage ('echo') {
      steps {
        echo "Namaste"
	echo "IS polling working"
	echo "Seems it worked"
      }
    }
  }
  
}
