library "project-system-jenkins-shared-pipeline-library-mulesoft@main"

// Get default service configuration
service_config = defaultConfigService()

service_config.project_config_branch_name = "main"

service_config.maven_test_command = "mvn test -B -s settings.xml -Dsecure.key=mulesoft"

service_config.enable_publishing_to_exchange = true

service_config.java_version = "17"
service_config.project_config_repo_name = "project-configurations"
service_config.project_config_project_name = "rykuspt"

pipelineMavenMulesoftCI(service_config)