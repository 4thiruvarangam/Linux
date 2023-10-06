pipeline {
	agent any 
	stages {
	
		stage("build") {
			steps {
			sh '''#!/bin/bash
   			/home/master/test.sh
			echo "$var1"'''
			
			}
			
		
		}

		stage("build1") {
			steps {
			sh '''#!/bin/bash
   			for i in `echo 1 2`
      		        echo $i
			done '''
			
			}
			
		
		}
	
	
	}




}
