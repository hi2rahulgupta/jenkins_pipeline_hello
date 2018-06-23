
   
   
node {
    stage('build'){
        echo "building"
    }
}
stage('Deploy approval'){
    input "Deploy to prod?"
}
node {
    stage('deploy to prod'){
        echo "deploying"
    }
}

stage('Deploy approval'){input "Deploy to QA?"}
node {stage('deploy to QA'){echo "deploying to QA"}}
