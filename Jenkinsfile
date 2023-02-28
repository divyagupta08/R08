pipeline {
    agent any

    stages 
    {
        stage('Build') 
        {
            steps 
            {
                echo 'THIS IS TO BUILD AN APP'
            }
        }
        stage('Test') 
        {
            steps 
            {
                echo 'THIS IS TO TEST AN APP'
            }
        }
        stage('Deploy') 
        {
            steps 
            {
                echo 'THIS IS TO DEPLOY AN APP'
            }
        }
    }
    post
  {
    always
    {
        emailext body: 'summary', replyTo: 'rajurakesh441@gmail.com', subject: 'notify', to: 'rajurakesh441@gmail.com'
    }
  }
}
