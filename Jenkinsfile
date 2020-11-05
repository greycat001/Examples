properties([pipelineTriggers([githubPush()])])

node {
    stage ('Checkout'){
        git branch: 'exampleBranch', url: 'https://github.com/greycat001/Examples.git'
    }
    stage ('Build'){
        echo "We are in Build stage."
    }
    stage ('Test'){
        echo "We are in Test stage."
    }
    stage ('Deploy'){
        echo "We are in Deploy stage."
    }
} 
