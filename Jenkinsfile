// Specify configurations explicitly to test against newer LTS.
// See also https://github.com/jenkins-infra/pipeline-library/pull/145

// This should be updated manually.
def recentLts = '2.263.1'

buildPlugin(configurations: [
  [ platform: 'linux', jdk: '8' ],
  [ platform: 'windows', jdk: '8', jenkins: recentLts ],
  [ platform: 'linux', jdk: '11', jenkins: recentLts ],
])
