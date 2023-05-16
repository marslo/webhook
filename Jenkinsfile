node( 'built-in' ) {
    cleanWs()
    println 'helloo'
    checkout scmGit(
               branches: [[ name: '*/main' ]],
               extensions: [],
               userRemoteConfigs: [[ credentialsId: 'GITHUB_SSH_CREDENTIAL_MARSLO ',
                                     url: 'git@github.com:marslo/webhook.git'
               ]]
            )
}
