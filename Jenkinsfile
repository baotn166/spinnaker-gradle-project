@Library('jenkins-library') _
new org.soramitsu.mainLibrary().call(
  agentLabel: 'docker-build-agent',
  registry: 'docker.soramitsu.co.jp',
  agentImage: 'openjdk-11:latest',
  nexusUserId: 'bot-unkai-rw',
  nexusCredentials: 'bot-soramitsu-rw'
)
