node{
  stage('Slack Notification')
  {
  slackSend baseUrl: 'https://hooks.slack.com/services/', 
  channel: '#jenkins-pipeline', 
  color: 'good', 
  message: 'Hello From Mangi Lal', 
  tokenCredentialId: 'slack-demo'
  }
}
