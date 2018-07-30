node('dind') {
    
    sh 'docker-compose up'
    // do not launch in detached mode, the job will have to be killed
    // idea of this job is to check the memory used by the containers launched in dind mode
}