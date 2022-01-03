pipeline{
     agent any
     stages {
         stage('Cloning Git'){
            steps{
               git 'https://github.com/kirtipaliwal23/simple-node-js-react-npm-app.git'
               }
            }
         stage('env start'){
            steps{
            bat "npm run start"
            }
          }
         stage('test'){
            steps{
            bat "npm run test"
            }
          }
        stage('Build'){
            steps{
            bat "npm run build"
            }
          }

             

}
}
