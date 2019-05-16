node{
  stage('Slack Notification')
  {
  slackSend baseUrl: 'https://hooks.slack.com/services/', 
  channel: '#jenkins-pipeline', 
  color: 'good', 
  message: 'Prod Deployment started by Mangi Lal, please be in touch with BigOps Team!!!!!!!!', 
  tokenCredentialId: 'slack-demo'
  }
  stage('email notofication'){
        mail bcc: '', 
        body: 'Hi', 
        cc: '', 
        from: '', replyTo: '', 
        subject: 'Hi', 
        to: 'mangilal23@gmail.com'
        }
}
