pipeline{
    agent any
    environment{
        name="rakesh"
        version="1.0"
    }
    stages{
        stage('checkout scm'){
            steps{
                echo "checkout code from scm"
                echo " name ${env.name}"
                echo "version ${env.version}"
            }
        }
        stage('buuild'){
            steps{
                echo "building the project"
            }
        }
        stage('env variables'){
            steps{
                echo "build_number ${env.BUILD_NUMBER}"
                echo "job_name  ${env.JOB_NAME}"
            }
        }
    }
}
