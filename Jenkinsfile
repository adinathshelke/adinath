pipeline{
        agent{
		 label{
		 label 'master'
		 customWorkspace '/mnt/jobs/adinath1'
		 }
		}
		stages{
		stage('indrx.html deploy'){
		steps{
		                sh 'yum remove httpd -y'
                        sh 'yum install httpd -y'
                          sh 'service httpd start' 
                           sh  'echo "bhagyashree shelke" >> /var/www/html/index.html'
                           sh   'chmod -R 777 /var/www/html'
		}
		}
		
		}
}
