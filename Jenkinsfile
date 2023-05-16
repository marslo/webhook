node( 'built-in' ) {
    cleanWs()
    println 'helloo'
    // git branch: '*/main',
        // credentialsId: 'GITHUB_SSH_CREDENTIAL_MARSLO',
        // url: 'https://github.com/marslo/webhook.git'

    checkout scmGit(
               branches: [[ name: '*/main' ]],
               browser: github( 'https://github.com/marslo/webhook' ),
               extensions: [],
               userRemoteConfigs: [[ credentialsId: 'GITHUB_SSH_CREDENTIAL_MARSLO', url: 'https://github.com/marslo/webhook.git' ]]
             )
}
