
pipeline
	agent any
	{	
		stages
		{
			stage ( ' Download ' )
			{	
				steps
				{
				git ' https://github.com/keshavr21/maven_test.git '
				}	
			}
			stage ( ' build ' )
			{
				steps
				{
				sh 'mvn clean package'
				}
			}

		}
	}
				
