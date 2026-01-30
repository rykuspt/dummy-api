properties([
    parameters([
        string(name: 'JENKINS_SHARED_PIPELINE_BRANCH', defaultValue: 'develop')
    ])
])

library "project-system-jenkins-shared-pipeline-library-mulesoft@${params.JENKINS_SHARED_PIPELINE_BRANCH}"

service_config = defaultConfigService()

pipelineMulesoftDeploymentMaven(service_config)