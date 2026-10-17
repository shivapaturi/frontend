@Library('jenkins-shared-library@main') _

def configMap = [
    project : "roboshop",
    component: "frontend"
]

if( ! env.BRANCH_NAME.equalsIgnoreCase('main') ){ // if not equals to main
    nodejsEKSpipeline(configMap) // by default it will call, call function inside this pipeline
}
else{
    echo "Please proceed with PROD process"
}