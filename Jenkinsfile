pipeline{

	agent any
                 parameters{
                   string(name:'Greeting',  defaultValue: 'Hello', description: 'How should i greet the world?')

                }
	stages {
	      stage("Greeting"){
                          steps {
                           echo "${params.Greeting} World"
                          }
                       }
                  }
		stage("Build"{
			echo "building"
		}
	      stage("test"){
			echo "testing"
	      }
      }
}
