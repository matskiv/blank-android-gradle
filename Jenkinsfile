node('android') {
    stage 'Checkout' {
        checkout scm
    }

    stage 'Build' {
        sh "ls && echo 'Dummy Jenkinsfile'"
    }

    stage 'Archive' {
        archiveArtifacts artifacts: '/app/src/main/AndroidManifest.xml'
    }
}
