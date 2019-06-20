pipeline{
	agent {
    node {
        label 'Android_Agent'
        customWorkspace '/home/root/'
    }
}


	stages{
	   stage('build'){
	      steps {
	        echo 'building'
	      }
	   }

	   stage('test'){
	      steps{
	         echo 'testing'
	      }
	   }

	   stage('deploy'){
	      steps{
	         echo 'deploying'
	      }
	   }
	}
}
