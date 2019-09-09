node {

    stage('Checkout Main Project') {
        git(
                url: 'https://github.com/Archi-Lab-FAE/fae-documentation-server.git',
                credentialsId: 'archilab-github-jenkins',
                branch: 'master'
        )
    }

    stage('Checkout Global') {
        dir("_posts/global") {
            git(
                    url: 'https://github.com/Archi-Lab-FAE/fae-global-documentation',
                    credentialsId: 'archilab-github-jenkins',
                    branch: 'master'
            )
        }
    }

    stage('Checkout Team-1') {
        dir("_posts/team1") {
            git(
                    url: 'https://github.com/Archi-Lab-FAE/fae-team-1-documentation.git',
                    credentialsId: 'archilab-github-jenkins',
                    branch: 'master'
            )
        }
    }

    stage('Checkout Team-2') {
        dir("_posts/team2") {
            git(
                    url: 'https://github.com/Archi-Lab-FAE/fae-team-2-documentation.git',
                    credentialsId: 'archilab-github-jenkins',
                    branch: 'master'
            )
        }
    }

    stage('Checkout Team-3') {
        dir("_posts/team3") {
            git(
                    url: 'https://github.com/Archi-Lab-FAE/fae-team-3-documentation.git',
                    credentialsId: 'archilab-github-jenkins',
                    branch: 'master'
            )
        }
    }

    stage('Checkout Team-4') {
        dir("_posts/team4") {
            git(
                    url: 'https://github.com/Archi-Lab-FAE/fae-team-4-documentation.git',
                    credentialsId: 'archilab-github-jenkins',
                    branch: 'master'
            )
        }
    }

    stage('Build Production Image') {
        docker.withRegistry('https://docker.nexus.archi-lab.io', 'archilab-nexus-jenkins') {
            def customImage = docker.build("docker.nexus.archi-lab.io/archilab/fae-documentation-server:${env.BUILD_ID}")
            customImage.push()
            customImage.push('latest')
        }
    }
}
