pipeline{
    agent any
    stages{
        stage('greetings'){
	    steps{
	        echo "Greetings from jenkins"
	    }
	}
	stage('build'){
	    steps{
	        "python hello.py"
	    }
	}
	stage('test'){
	    steps{
	        echo "testing....!"
	    }
	}
	stage('deploy'){
	    steps{
	        echo "deploying....!"
	    }
	}
    }
}

