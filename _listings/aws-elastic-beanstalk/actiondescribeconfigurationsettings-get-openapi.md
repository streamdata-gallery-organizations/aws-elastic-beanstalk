---
swagger: "2.0"
x-collection-name: AWS Elastic Beanstalk
x-complete: 0
info:
  title: AWS Elastic Beanstalk API Describe Configuration Settings
  version: 1.0.0
  description: |-
    Returns a description of the settings for the specified configuration set, that is,
          either a configuration template or the configuration set associated with a running
          environment.
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /?Action=AbortEnvironmentUpdate:
    get:
      summary: Abort Environment Update
      description: |-
        Cancels in-progress environment configuration update or application version
              deployment.
      operationId: abortEnvironmentUpdate
      x-api-path-slug: actionabortenvironmentupdate-get
      parameters:
      - in: query
        name: EnvironmentId
        description: This specifies the ID of the environment with the in-progress
          update that you want to      cancel
        type: string
      - in: query
        name: EnvironmentName
        description: This specifies the name of the environment with the in-progress
          update that you want to      cancel
        type: string
      responses:
        200:
          description: OK
      tags:
      - Environments
  /?Action=ApplyEnvironmentManagedAction:
    get:
      summary: Apply Environment Managed Action
      description: Applies a scheduled managed action immediately.
      operationId: applyEnvironmentManagedAction
      x-api-path-slug: actionapplyenvironmentmanagedaction-get
      parameters:
      - in: query
        name: ActionId
        description: The action ID of the scheduled managed action to execute
        type: string
      - in: query
        name: EnvironmentId
        description: The environment ID of the target environment
        type: string
      - in: query
        name: EnvironmentName
        description: The name of the target environment
        type: string
      responses:
        200:
          description: OK
      tags:
      - Environments
  /?Action=CheckDNSAvailability:
    get:
      summary: Check D N S Availability
      description: Checks if the specified CNAME is available.
      operationId: checkDNSAvailability
      x-api-path-slug: actioncheckdnsavailability-get
      parameters:
      - in: query
        name: CNAMEPrefix
        description: The prefix used when this CNAME is reserved
        type: string
      responses:
        200:
          description: OK
      tags:
      - DNS
  /?Action=ComposeEnvironments:
    get:
      summary: Compose Environments
      description: |-
        Create or update a group of environments that each run a separate component of a single
              application.
      operationId: composeEnvironments
      x-api-path-slug: actioncomposeenvironments-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application to which the specified source bundles
          belong
        type: string
      - in: query
        name: GroupName
        description: The name of the group to which the target environments belong
        type: string
      - in: query
        name: VersionLabels.member.N
        description: A list of version labels, specifying one or more application
          source bundles that belong      to the target application
        type: string
      responses:
        200:
          description: OK
      tags:
      - Environments
  /?Action=CreateApplication:
    get:
      summary: Create Application
      description: |-
        Creates an application that has one configuration template named default
              and no application versions.
      operationId: createApplication
      x-api-path-slug: actioncreateapplication-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application
        type: string
      - in: query
        name: Description
        description: Describes the application
        type: string
      - in: query
        name: ResourceLifecycleConfig
        description: Specify an application resource lifecycle configuration to prevent
          your application      from accumulating too many versions
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /?Action=CreateApplicationVersion:
    get:
      summary: Create Application Version
      description: Creates an application version for the specified application.
      operationId: createApplicationVersion
      x-api-path-slug: actioncreateapplicationversion-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application
        type: string
      - in: query
        name: AutoCreateApplication
        description: Set to true to create an application with the specified name
          if it doesnt      already exist
        type: string
      - in: query
        name: BuildConfiguration
        description: Settings for an AWS CodeBuild build
        type: string
      - in: query
        name: Description
        description: Describes this version
        type: string
      - in: query
        name: Process
        description: Preprocesses and validates the environment manifest and configuration
          files in the      source bundle
        type: string
      - in: query
        name: SourceBuildInformation
        description: Specify a commit in an AWS CodeCommit Git repository to use as
          the source code for the      application version
        type: string
      - in: query
        name: SourceBundle
        description: The Amazon S3 bucket and key that identify the location of the
          source bundle for this      version
        type: string
      - in: query
        name: VersionLabel
        description: A label identifying this version
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /?Action=CreateConfigurationTemplate:
    get:
      summary: Create Configuration Template
      description: Creates a configuration template.
      operationId: createConfigurationTemplate
      x-api-path-slug: actioncreateconfigurationtemplate-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application to associate with this configuration
          template
        type: string
      - in: query
        name: Description
        description: Describes this configuration
        type: string
      - in: query
        name: EnvironmentId
        description: The ID of the environment used with this configuration template
        type: string
      - in: query
        name: OptionSettings.member.N
        description: If specified, AWS Elastic Beanstalk sets the specified configuration
          option to the      requested value
        type: string
      - in: query
        name: SolutionStackName
        description: The name of the solution stack used by this configuration
        type: string
      - in: query
        name: SourceConfiguration
        description: If specified, AWS Elastic Beanstalk uses the configuration values
          from the specified      configuration template to create a new configuration
        type: string
      - in: query
        name: TemplateName
        description: The name of the configuration template
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Templates
  /?Action=CreateEnvironment:
    get:
      summary: Create Environment
      description: |-
        Launches an environment for the specified application using the specified
              configuration.
      operationId: createEnvironment
      x-api-path-slug: actioncreateenvironment-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application that contains the version to be deployed
        type: string
      - in: query
        name: CNAMEPrefix
        description: If specified, the environment attempts to use this value as the
          prefix for the CNAME
        type: string
      - in: query
        name: Description
        description: Describes this environment
        type: string
      - in: query
        name: EnvironmentName
        description: A unique name for the deployment environment
        type: string
      - in: query
        name: GroupName
        description: The name of the group to which the target environment belongs
        type: string
      - in: query
        name: OptionSettings.member.N
        description: If specified, AWS Elastic Beanstalk sets the specified configuration
          options to the      requested value in the configuration set for the new
          environment
        type: string
      - in: query
        name: OptionsToRemove.member.N
        description: A list of custom user-defined configuration options to remove
          from the configuration      set for this new environment
        type: string
      - in: query
        name: SolutionStackName
        description: This is an alternative to specifying a template name
        type: string
      - in: query
        name: Tags.member.N
        description: This specifies the tags applied to resources in the environment
        type: string
      - in: query
        name: TemplateName
        description: The name of the configuration template to use in deployment
        type: string
      - in: query
        name: Tier
        description: This specifies the tier to use for creating this environment
        type: string
      - in: query
        name: VersionLabel
        description: The name of the application version to deploy
        type: string
      responses:
        200:
          description: OK
      tags:
      - Environments
  /?Action=CreateStorageLocation:
    get:
      summary: Create Storage Location
      description: Creates the Amazon S3 storage location for the account.
      operationId: createStorageLocation
      x-api-path-slug: actioncreatestoragelocation-get
      parameters:
      - in: query
        name: S3Bucket
        description: The name of the Amazon S3 bucket created
        type: string
      responses:
        200:
          description: OK
      tags:
      - Storage Location
  /?Action=DeleteApplication:
    get:
      summary: Delete Application
      description: |-
        Deletes the specified application along with all associated versions and
              configurations.
      operationId: deleteApplication
      x-api-path-slug: actiondeleteapplication-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application to delete
        type: string
      - in: query
        name: TerminateEnvByForce
        description: When set to true, running environments will be terminated before
          deleting the      application
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /?Action=DeleteApplicationVersion:
    get:
      summary: Delete Application Version
      description: Deletes the specified version from the specified application.
      operationId: deleteApplicationVersion
      x-api-path-slug: actiondeleteapplicationversion-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application to which the version belongs
        type: string
      - in: query
        name: DeleteSourceBundle
        description: Set to true to delete the source bundle from your storage bucket
        type: string
      - in: query
        name: VersionLabel
        description: The label of the version to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Application Version
  /?Action=DeleteConfigurationTemplate:
    get:
      summary: Delete Configuration Template
      description: Deletes the specified configuration template.
      operationId: deleteConfigurationTemplate
      x-api-path-slug: actiondeleteconfigurationtemplate-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application to delete the configuration template
          from
        type: string
      - in: query
        name: TemplateName
        description: The name of the configuration template to delete
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Templates
  /?Action=DeleteEnvironmentConfiguration:
    get:
      summary: Delete Environment Configuration
      description: Deletes the draft configuration associated with the running environment.
      operationId: deleteEnvironmentConfiguration
      x-api-path-slug: actiondeleteenvironmentconfiguration-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application the environment is associated with
        type: string
      - in: query
        name: EnvironmentName
        description: The name of the environment to delete the draft configuration
          from
        type: string
      responses:
        200:
          description: OK
      tags:
      - Environments
  /?Action=DescribeApplications:
    get:
      summary: Describe Applications
      description: Returns the descriptions of existing applications.
      operationId: describeApplications
      x-api-path-slug: actiondescribeapplications-get
      parameters:
      - in: query
        name: ApplicationNames.member.N
        description: If specified, AWS Elastic Beanstalk restricts the returned descriptions
          to only include      those with the specified names
        type: string
      responses:
        200:
          description: OK
      tags:
      - Applications
  /?Action=DescribeApplicationVersions:
    get:
      summary: Describe Application Versions
      description: Retrieve a list of application versions.
      operationId: describeApplicationVersions
      x-api-path-slug: actiondescribeapplicationversions-get
      parameters:
      - in: query
        name: ApplicationName
        description: Specify an application name to show only application versions
          for that      application
        type: string
      - in: query
        name: MaxRecords
        description: Specify a maximum number of application versions to paginate
          in the request
        type: string
      - in: query
        name: NextToken
        description: Specify a next token to retrieve the next page in a paginated
          request
        type: string
      - in: query
        name: VersionLabels.member.N
        description: Specify a version label to show a specific application version
        type: string
      responses:
        200:
          description: OK
      tags:
      - Application Version
  /?Action=DescribeConfigurationOptions:
    get:
      summary: Describe Configuration Options
      description: |-
        Describes the configuration options that are used in a particular configuration
              template or environment, or that a specified solution stack defines.
      operationId: describeConfigurationOptions
      x-api-path-slug: actiondescribeconfigurationoptions-get
      parameters:
      - in: query
        name: ApplicationName
        description: The name of the application associated with the configuration
          template or environment
        type: string
      - in: query
        name: EnvironmentName
        description: The name of the environment whose configuration options you want
          to describe
        type: string
      - in: query
        name: Options.member.N
        description: If specified, restricts the descriptions to only the specified
          options
        type: string
      - in: query
        name: SolutionStackName
        description: The name of the solution stack whose configuration options you
          want to      describe
        type: string
      - in: query
        name: TemplateName
        description: The name of the configuration template whose configuration options
          you want to      describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - ConfigurationOptions
  /?Action=DescribeConfigurationSettings:
    get:
      summary: Describe Configuration Settings
      description: |-
        Returns a description of the settings for the specified configuration set, that is,
              either a configuration template or the configuration set associated with a running
              environment.
      operationId: describeConfigurationSettings
      x-api-path-slug: actiondescribeconfigurationsettings-get
      parameters:
      - in: query
        name: ApplicationName
        description: The application for the environment or configuration template
        type: string
      - in: query
        name: EnvironmentName
        description: The name of the environment to describe
        type: string
      - in: query
        name: TemplateName
        description: The name of the configuration template to describe
        type: string
      responses:
        200:
          description: OK
      tags:
      - Configuration Settings
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---