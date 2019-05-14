node{
  stage('Slack Notification')
  {
  slackSend baseUrl: 'https://hooks.slack.com/services/', 
  channel: '#jenkins-pipeline', 
  color: 'good', 
  message: 'Prod Deployment started!!!!!!!!!!!, please be in touch with Niraj Marmar!!!!!!!!', 
  tokenCredentialId: 'slack-demo'
  }
}
