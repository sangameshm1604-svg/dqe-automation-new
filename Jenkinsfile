pipeline {
    agent any

  stages {
      stage('Clone Repo') {
          steps {
              git 'https://github.com/sangameshm1604-svg/dqe-automation-new.git'
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
