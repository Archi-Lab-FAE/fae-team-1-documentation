node {
    stage('Checkout Main Project') {
        git(
                url: 'https://github.com/Archi-Lab-FAE/fae-documentation-server.git',
                credentialsId: 'archilab-github-jenkins',
                branch: 'master'
        )
    }
    load 'pipeline.groovy'
}
