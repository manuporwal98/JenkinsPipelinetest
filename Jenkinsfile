// test
pipeline {
    agent any 
    stages {
        stage('Stage 1') {
            steps {
                git branch: 'main', url: 'https://github.com/manuporwal98/JenkinsPipelinetest.git'
                sh "C:\\ProgramData\\Jenkins\\.jenkins\\workspace\\SCMPipeline\\JenkinsPipelinetest\\test.sh"
            }
        }
    }
}
