pipeline{
        agent{
		 label{
		 label 'master'
		 customWorkspace '/mnt/jobs/adinath'
		 }
		}
		stages{
		stage('indrx.html deploy'){
		steps{
		                sh 'yum remove httpd -y'
                        sh 'yum install httpd -y'
                          sh 'service httpd start' 
                           sh  'echo "Chandrakant shelke" >> /var/www/html/index.html'
                           sh   'chmod -R 777 /var/www/html'
		}
		}
		
		}
}
