@Library('daws-90s-jenkins-shared-library') _

def configMap = [
    project: "roboshop",
    component: "catalogue"
]
// testPipeline(configMap)

if (env.BRANCH_NAME.equalsIgnoreCase('main')){
    // nodejsEKSMain(configMap)
    we will deal later
}
else {
    nodejsEKSPipeline(configMap)
}