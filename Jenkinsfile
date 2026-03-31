pipeline {
    agent any

  stages {
      stage('Clone Repo') {
          steps {
              git 'https://github.com/sangamesh1604-svg/dqe-automation.git'
          }
      }

      stage('Run Pipeline') {
          steps {
              sh 'echo "Running data pipeline..."'
              sh 'ls'
          }
      }
    }
}
