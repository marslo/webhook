node( 'built-in' ) {
    println 'helloo'
    checkout scmGit(
               branches: [[ name: '*/main' ]],
               extensions: [],
               userRemoteConfigs: [[ credentialsId: 'GITHUB_SSH_CREDENTAIL',
                                     url: 'git@ssh.github.com:marslojiao-mvl/jenkins-testing.git'
               ]]
            )
}
