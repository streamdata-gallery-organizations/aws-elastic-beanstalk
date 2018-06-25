---
name: AWS Elastic Beanstalk
x-slug: aws-elastic-beanstalk
description: AWS Elastic Beanstalk is an easy-to-use service for deploying and scaling
  web applications and services developed with Java,.NET, PHP, Node.js, Python, Ruby,
  Go, andDockeron familiar servers such as Apache, Nginx, Passenger, andIIS.You can
  simply upload your code and Elastic Beanstalk automatically handles the deployment,
  from capacity provisioning, load balancing, auto-scaling to application health monitoring.
  At the same time, you retain full control over the AWS resources powering your application
  and can access the underlying resources at any time.There is no additional charge
  for Elastic Beanstalk - you pay only for the AWS resources needed to store and run
  your applications.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
x-kinRank: "10"
x-alexaRank: "0"
tags: AWS Elastic Beanstalk
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/apis.md
specificationVersion: "0.14"
apis:
- name: AWS Elastic Beanstalk API Abort Environment Update
  x-api-slug: aws-elastic-beanstalk-api
  description: |-
    Cancels in-progress environment configuration update or application version
          deployment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=AbortEnvironmentUpdate
  tags: Environments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actionabortenvironmentupdate-get-openapi.md
- name: AWS Elastic Beanstalk API Apply Environment Managed Action
  x-api-slug: aws-elastic-beanstalk-api
  description: Applies a scheduled managed action immediately.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=ApplyEnvironmentManagedAction
  tags: Environments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actionapplyenvironmentmanagedaction-get-openapi.md
- name: AWS Elastic Beanstalk API Check D N S Availability
  x-api-slug: aws-elastic-beanstalk-api
  description: Checks if the specified CNAME is available.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=CheckDNSAvailability
  tags: DNS
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actioncheckdnsavailability-get-openapi.md
- name: AWS Elastic Beanstalk API Compose Environments
  x-api-slug: aws-elastic-beanstalk-api
  description: |-
    Create or update a group of environments that each run a separate component of a single
          application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=ComposeEnvironments
  tags: Environments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actioncomposeenvironments-get-openapi.md
- name: AWS Elastic Beanstalk API Create Application
  x-api-slug: aws-elastic-beanstalk-api
  description: |-
    Creates an application that has one configuration template named default
          and no application versions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=CreateApplication
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actioncreateapplication-get-openapi.md
- name: AWS Elastic Beanstalk API Create Application Version
  x-api-slug: aws-elastic-beanstalk-api
  description: Creates an application version for the specified application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=CreateApplicationVersion
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actioncreateapplicationversion-get-openapi.md
- name: AWS Elastic Beanstalk API Create Configuration Template
  x-api-slug: aws-elastic-beanstalk-api
  description: Creates a configuration template.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=CreateConfigurationTemplate
  tags: Configuration Templates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actioncreateconfigurationtemplate-get-openapi.md
- name: AWS Elastic Beanstalk API Create Environment
  x-api-slug: aws-elastic-beanstalk-api
  description: |-
    Launches an environment for the specified application using the specified
          configuration.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=CreateEnvironment
  tags: Environments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actioncreateenvironment-get-openapi.md
- name: AWS Elastic Beanstalk API Create Storage Location
  x-api-slug: aws-elastic-beanstalk-api
  description: Creates the Amazon S3 storage location for the account.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=CreateStorageLocation
  tags: Storage Location
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actioncreatestoragelocation-get-openapi.md
- name: AWS Elastic Beanstalk API Delete Application
  x-api-slug: aws-elastic-beanstalk-api
  description: |-
    Deletes the specified application along with all associated versions and
          configurations.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=DeleteApplication
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actiondeleteapplication-get-openapi.md
- name: AWS Elastic Beanstalk API Delete Application Version
  x-api-slug: aws-elastic-beanstalk-api
  description: Deletes the specified version from the specified application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=DeleteApplicationVersion
  tags: Application Version
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actiondeleteapplicationversion-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actiondeleteapplicationversion-get-openapi.md
- name: AWS Elastic Beanstalk API Delete Configuration Template
  x-api-slug: aws-elastic-beanstalk-api
  description: Deletes the specified configuration template.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=DeleteConfigurationTemplate
  tags: Configuration Templates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actiondeleteconfigurationtemplate-get-openapi.md
- name: AWS Elastic Beanstalk API Delete Environment Configuration
  x-api-slug: aws-elastic-beanstalk-api
  description: Deletes the draft configuration associated with the running environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=DeleteEnvironmentConfiguration
  tags: Environments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actiondeleteenvironmentconfiguration-get-openapi.md
- name: AWS Elastic Beanstalk API Describe Applications
  x-api-slug: aws-elastic-beanstalk-api
  description: Returns the descriptions of existing applications.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=DescribeApplications
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actiondescribeapplications-get-openapi.md
- name: AWS Elastic Beanstalk API Describe Application Versions
  x-api-slug: aws-elastic-beanstalk-api
  description: Retrieve a list of application versions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=DescribeApplicationVersions
  tags: Application Version
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actiondescribeapplicationversions-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actiondescribeapplicationversions-get-openapi.md
- name: AWS Elastic Beanstalk API Describe Configuration Options
  x-api-slug: aws-elastic-beanstalk-api
  description: |-
    Describes the configuration options that are used in a particular configuration
          template or environment, or that a specified solution stack defines.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=DescribeConfigurationOptions
  tags: 'ConfigurationOptions '
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actiondescribeconfigurationoptions-get-openapi.md
- name: AWS Elastic Beanstalk API Describe Configuration Settings
  x-api-slug: aws-elastic-beanstalk-api
  description: |-
    Returns a description of the settings for the specified configuration set, that is,
          either a configuration template or the configuration set associated with a running
          environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=DescribeConfigurationSettings
  tags: Configuration Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actiondescribeconfigurationsettings-get-openapi.md
- name: AWS Elastic Beanstalk API Describe Environment Health
  x-api-slug: aws-elastic-beanstalk-api
  description: Returns information about the overall health of the specified environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=DescribeEnvironmentHealth
  tags: Environments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actiondescribeenvironmenthealth-get-openapi.md
- name: AWS Elastic Beanstalk API Describe Environment Managed Action History
  x-api-slug: aws-elastic-beanstalk-api
  description: Lists an environment's completed and failed managed actions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=DescribeEnvironmentManagedActionHistory
  tags: Environments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actiondescribeenvironmentmanagedactionhistory-get-openapi.md
- name: AWS Elastic Beanstalk API Describe Environment Managed Actions
  x-api-slug: aws-elastic-beanstalk-api
  description: Lists an environment's upcoming and in-progress managed actions.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=DescribeEnvironmentManagedActions
  tags: Environments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actiondescribeenvironmentmanagedactions-get-openapi.md
- name: AWS Elastic Beanstalk API Describe Environment Resources
  x-api-slug: aws-elastic-beanstalk-api
  description: Returns AWS resources for this environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=DescribeEnvironmentResources
  tags: Environments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actiondescribeenvironmentresources-get-openapi.md
- name: AWS Elastic Beanstalk API Describe Environments
  x-api-slug: aws-elastic-beanstalk-api
  description: Returns descriptions for existing environments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=DescribeEnvironments
  tags: Environments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actiondescribeenvironments-get-openapi.md
- name: AWS Elastic Beanstalk API Describe Events
  x-api-slug: aws-elastic-beanstalk-api
  description: Returns list of event descriptions matching criteria up to the last
    6 weeks.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=DescribeEvents
  tags: Events
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actiondescribeevents-get-openapi.md
- name: AWS Elastic Beanstalk API Describe Instances Health
  x-api-slug: aws-elastic-beanstalk-api
  description: |-
    Retrives detailed information about the health of instances in your AWS Elastic
          Beanstalk.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=DescribeInstancesHealth
  tags: Instances Health
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actiondescribeinstanceshealth-get-openapi.md
- name: AWS Elastic Beanstalk API List Available Solution Stacks
  x-api-slug: aws-elastic-beanstalk-api
  description: Returns a list of the available solution stack names.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=ListAvailableSolutionStacks
  tags: Solution Stacks
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actionlistavailablesolutionstacks-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actionlistavailablesolutionstacks-get-openapi.md
- name: AWS Elastic Beanstalk API Rebuild Environment
  x-api-slug: aws-elastic-beanstalk-api
  description: |-
    Deletes and recreates all of the AWS resources (for example: the Auto Scaling group,
          load balancer, etc.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=RebuildEnvironment
  tags: Environments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actionrebuildenvironment-get-openapi.md
- name: AWS Elastic Beanstalk API Request Environment Info
  x-api-slug: aws-elastic-beanstalk-api
  description: |-
    Initiates a request to compile the specified type of information of the deployed
          environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=RequestEnvironmentInfo
  tags: Environments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actionrequestenvironmentinfo-get-openapi.md
- name: AWS Elastic Beanstalk API Restart App Server
  x-api-slug: aws-elastic-beanstalk-api
  description: |-
    Causes the environment to restart the application container server running on each
          Amazon EC2 instance.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=RestartAppServer
  tags: App Servers
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actionrestartappserver-get-openapi.md
- name: AWS Elastic Beanstalk API Retrieve Environment Info
  x-api-slug: aws-elastic-beanstalk-api
  description: Retrieves the compiled information from a.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=RetrieveEnvironmentInfo
  tags: Environments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actionretrieveenvironmentinfo-get-openapi.md
- name: AWS Elastic Beanstalk API Swap Environment C N A M Es
  x-api-slug: aws-elastic-beanstalk-api
  description: Swaps the CNAMEs of two environments.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=SwapEnvironmentCNAMEs
  tags: Environments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actionswapenvironmentcnames-get-openapi.md
- name: AWS Elastic Beanstalk API Terminate Environment
  x-api-slug: aws-elastic-beanstalk-api
  description: Terminates the specified environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=TerminateEnvironment
  tags: Environments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actionterminateenvironment-get-openapi.md
- name: AWS Elastic Beanstalk API Update Application
  x-api-slug: aws-elastic-beanstalk-api
  description: Updates the specified application to have the specified properties.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=UpdateApplication
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actionupdateapplication-get-openapi.md
- name: AWS Elastic Beanstalk API Update Application Resource Lifecycle
  x-api-slug: aws-elastic-beanstalk-api
  description: Modifies lifecycle settings for an application.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=UpdateApplicationResourceLifecycle
  tags: Application Resource Lifecycle
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actionupdateapplicationresourcelifecycle-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actionupdateapplicationresourcelifecycle-get-openapi.md
- name: AWS Elastic Beanstalk API Update Application Version
  x-api-slug: aws-elastic-beanstalk-api
  description: Updates the specified application version to have the specified properties.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=UpdateApplicationVersion
  tags: Applications
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actionupdateapplicationversion-get-openapi.md
- name: AWS Elastic Beanstalk API Update Configuration Template
  x-api-slug: aws-elastic-beanstalk-api
  description: |-
    Updates the specified configuration template to have the specified properties or
          configuration option values.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=UpdateConfigurationTemplate
  tags: Configuration Templates
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actionupdateconfigurationtemplate-get-openapi.md
- name: AWS Elastic Beanstalk API Update Environment
  x-api-slug: aws-elastic-beanstalk-api
  description: |-
    Updates the environment description, deploys a new application version, updates the
          configuration settings to an entirely new configuration template, or updates select
          configuration option values in the running environment.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=UpdateEnvironment
  tags: Environments
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actionupdateenvironment-get-openapi.md
- name: AWS Elastic Beanstalk API Validate Configuration Settings
  x-api-slug: aws-elastic-beanstalk-api
  description: |-
    Takes a set of configuration settings and either a configuration template or
          environment, and determines whether those values are valid.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: ://///?Action=ValidateConfigurationSettings
  tags: Configuration Settings
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/actionvalidateconfigurationsettings-get-openapi.md
- name: AWS Elastic Beanstalk API
  x-api-slug: aws-elastic-beanstalk-api
  description: AWS Elastic Beanstalk is an easy-to-use service for deploying and scaling
    web applications and services developed with Java,.NET, PHP, Node.js, Python,
    Ruby, Go, andDockeron familiar servers such as Apache, Nginx, Passenger, andIIS.You
    can simply upload your code and Elastic Beanstalk automatically handles the deployment,
    from capacity provisioning, load balancing, auto-scaling to application health
    monitoring. At the same time, you retain full control over the AWS resources powering
    your application and can access the underlying resources at any time.There is
    no additional charge for Elastic Beanstalk - you pay only for the AWS resources
    needed to store and run your applications.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/Compute_AWSElasticBeanstalk.png
  humanURL: https://aws.amazon.com/elasticbeanstalk/
  baseURL: :///
  tags: AWS Elastic Beanstalk
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/aws-elastic-beanstalk/master/_listings/aws-elastic-beanstalk/openapi.md
x-common:
- type: x-change-log
  url: http://aws.amazon.com/releasenotes/AWS-Elastic-Beanstalk
- type: x-command-line-interface
  url: http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/eb-cli3.html
- type: x-documentation
  url: http://docs.aws.amazon.com/elasticbeanstalk/latest/api/Welcome.html
- type: x-faq
  url: https://aws.amazon.com/elasticbeanstalk/faqs/
- type: x-forum
  url: https://forums.aws.amazon.com/forum.jspa?forumID=86
- type: x-getting-started
  url: https://aws.amazon.com/elasticbeanstalk/getting-started/
- type: x-pricing
  url: https://aws.amazon.com/elasticbeanstalk/pricing/
- type: x-website
  url: https://aws.amazon.com/elasticbeanstalk/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---