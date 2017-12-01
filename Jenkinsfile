#!groovy
node("392641ad9392-3acb3aef") {
    properties([
         parameters([
           string(
             defaultValue: "componentB",
             description: "list of components",
             name: 'componentsToUpdate'
           )
         ])
       ])
    stage("branch_name") {
        checkout scm
        println "Branch name is: " + env.BRANCH_NAME
    }
    stage("check parameters") {
        println "Passed parameters: " + params.name
    }
}