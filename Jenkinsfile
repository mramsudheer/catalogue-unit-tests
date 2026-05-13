//@Library('jenkins-shared-library') // Name declared in In Jenkins URL -> Settings -> System -> Global Trusted Pipeline Libraries -> Add
def configMap = [
    project: "roboshop",
    component: "catalogue"
]

echo "Triggering the library pipeline"

if ( env.BRANCH_NAME.equalsIgnoreCase('main') ){
    ech "Will do later"
    //configMap["jiraProject"] = "ROBO"
    //nodeJSEKSMainPipeline(configMap)
}
else{
    //configMap["jiraProject"] = "ROBO"
    nodeJSEKSPipeline(configMap)
}