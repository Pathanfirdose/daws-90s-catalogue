@Library('daws-90s-jenkins-shared-library') _

def configMap = [
    project: "roboshop",
    component: "daws-90s-catalogue"
]
if (env.BRANCH_NAME.equalsIgnoreCase('main')){
    nodejsEKSMain(configMap)
}
else {
    nodejsEKSPipeline(configMap)
}

// its a test