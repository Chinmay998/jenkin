pipeline {

agent {
			label{
						label 'qa'
			}
}

stages{
			stage ('install-tree'){
								steps{
											sh "sudo yum install tree -y"
								}
			}
			
			stage ('install-soft-on-172.31.30.146'){
			agent {
						label {
									label "qa"
						}
			}
								steps {
										sh "sudo yum install httpd -y"
										
								}
			}
			
			
}
}
