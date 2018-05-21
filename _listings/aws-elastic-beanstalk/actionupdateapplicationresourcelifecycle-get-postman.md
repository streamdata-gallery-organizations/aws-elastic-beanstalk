{
  "info": {
    "name": "AWS Elastic Beanstalk API Update Application Resource Lifecycle",
    "_postman_id": "fec1ffc9-33dc-41d1-bd5c-81308c39bf15",
    "description": "Modifies lifecycle settings for an application.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Environments",
      "item": [
        {
          "id": "addd5c85-188d-4cca-bcca-8ff4937184ed",
          "name": "abortEnvironmentUpdate",
          "request": {
            "url": "http://example.com/api/?Action=AbortEnvironmentUpdate?EnvironmentId=EnvironmentId&EnvironmentName=EnvironmentName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Cancels in-progress environment configuration update or application version\n      deployment."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ce4ef804-5923-4966-88f8-f0e6431667d2"
            }
          ]
        },
        {
          "id": "26248be9-1411-44bd-8bff-de68ef1be40f",
          "name": "applyEnvironmentManagedAction",
          "request": {
            "url": "http://example.com/api/?Action=ApplyEnvironmentManagedAction?ActionId=ActionId&EnvironmentId=EnvironmentId&EnvironmentName=EnvironmentName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Applies a scheduled managed action immediately."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "010ca55b-ae05-46a7-b7dc-cc6577a16343"
            }
          ]
        },
        {
          "id": "0b9e8b99-e528-4c66-ba89-4d37673aef48",
          "name": "composeEnvironments",
          "request": {
            "url": "http://example.com/api/?Action=ComposeEnvironments?ApplicationName=ApplicationName&GroupName=GroupName&VersionLabels.member.N=VersionLabels.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Create or update a group of environments that each run a separate component of a single\n      application."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e77915ea-3155-49e8-8468-71cb7c3389db"
            }
          ]
        },
        {
          "id": "c3091703-2a41-47f0-a632-e8ddb46a8614",
          "name": "createEnvironment",
          "request": {
            "url": "http://example.com/api/?Action=CreateEnvironment?ApplicationName=ApplicationName&CNAMEPrefix=CNAMEPrefix&Description=Description&EnvironmentName=EnvironmentName&GroupName=GroupName&OptionSettings.member.N=OptionSettings.member.N&OptionsToRemove.member.N=OptionsToRemove.member.N&SolutionStackName=SolutionStackName&Tags.member.N=Tags.member.N&TemplateName=TemplateName&Tier=Tier&VersionLabel=VersionLabel",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Launches an environment for the specified application using the specified\n      configuration."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b2c049e5-bce9-46c0-9d41-f04f18efcc53"
            }
          ]
        },
        {
          "id": "5152ed57-b63a-4164-8806-4ed28f33fda0",
          "name": "deleteEnvironmentConfiguration",
          "request": {
            "url": "http://example.com/api/?Action=DeleteEnvironmentConfiguration?ApplicationName=ApplicationName&EnvironmentName=EnvironmentName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the draft configuration associated with the running environment."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "07fa033e-bbef-427e-82ac-e0c05f9c4586"
            }
          ]
        },
        {
          "id": "1c7854f7-73b5-45bc-bd77-d01059418ed1",
          "name": "describeEnvironmentHealth",
          "request": {
            "url": "http://example.com/api/?Action=DescribeEnvironmentHealth?AttributeNames.member.N=AttributeNames.member.N&EnvironmentId=EnvironmentId&EnvironmentName=EnvironmentName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns information about the overall health of the specified environment."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "af75ecaa-153c-473f-b2fd-2673eec4b2c9"
            }
          ]
        },
        {
          "id": "7c89d805-362a-4f07-92f5-21c3511b7669",
          "name": "describeEnvironmentManagedActionHistory",
          "request": {
            "url": "http://example.com/api/?Action=DescribeEnvironmentManagedActionHistory?EnvironmentId=EnvironmentId&EnvironmentName=EnvironmentName&MaxItems=MaxItems&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists an environment's completed and failed managed actions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7e2ca72e-58bb-4eb9-ae16-1f1da0ff5563"
            }
          ]
        },
        {
          "id": "3499be48-bbe9-49dc-9c5b-28ef6e58fe45",
          "name": "describeEnvironmentManagedActions",
          "request": {
            "url": "http://example.com/api/?Action=DescribeEnvironmentManagedActions?EnvironmentId=EnvironmentId&EnvironmentName=EnvironmentName&Status=Status",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Lists an environment's upcoming and in-progress managed actions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e559aacf-694c-4e67-a838-8cf9481a7a67"
            }
          ]
        },
        {
          "id": "663e0c46-4989-4c8e-881f-d2feb1b9f4c4",
          "name": "describeEnvironmentResources",
          "request": {
            "url": "http://example.com/api/?Action=DescribeEnvironmentResources?EnvironmentId=EnvironmentId&EnvironmentName=EnvironmentName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns AWS resources for this environment."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "50319a62-9575-4fdb-98ae-b5ac38d01641"
            }
          ]
        },
        {
          "id": "10762d88-d9ea-4bab-87ad-d3cc2316566e",
          "name": "describeEnvironments",
          "request": {
            "url": "http://example.com/api/?Action=DescribeEnvironments?ApplicationName=ApplicationName&EnvironmentIds.member.N=EnvironmentIds.member.N&EnvironmentNames.member.N=EnvironmentNames.member.N&IncludedDeletedBackTo=IncludedDeletedBackTo&IncludeDeleted=IncludeDeleted&VersionLabel=VersionLabel",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns descriptions for existing environments."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5db5a38f-587c-411c-819e-fb29bb447ec3"
            }
          ]
        },
        {
          "id": "e27560cb-0490-40a8-bfd1-df06ffa823ba",
          "name": "rebuildEnvironment",
          "request": {
            "url": "http://example.com/api/?Action=RebuildEnvironment?EnvironmentId=EnvironmentId&EnvironmentName=EnvironmentName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes and recreates all of the AWS resources (for example: the Auto Scaling group,\n      load balancer, etc."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "11fd6c90-804f-4bc2-8e1c-7a6c644629ec"
            }
          ]
        },
        {
          "id": "b5fbaca9-6874-4d6b-b5d6-def767d47a62",
          "name": "requestEnvironmentInfo",
          "request": {
            "url": "http://example.com/api/?Action=RequestEnvironmentInfo?EnvironmentId=EnvironmentId&EnvironmentName=EnvironmentName&InfoType=InfoType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Initiates a request to compile the specified type of information of the deployed\n      environment."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "521b6bed-c62a-4cec-b17e-05f6d9a40911"
            }
          ]
        },
        {
          "id": "1d0c6111-a204-496e-91c2-e5c32629e670",
          "name": "retrieveEnvironmentInfo",
          "request": {
            "url": "http://example.com/api/?Action=RetrieveEnvironmentInfo?EnvironmentId=EnvironmentId&EnvironmentName=EnvironmentName&InfoType=InfoType",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieves the compiled information from a."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2cec22b2-ef52-4d50-9482-eee51e460d8c"
            }
          ]
        },
        {
          "id": "5fdbd56c-dc6a-406e-94b2-0eb90a9ec8e9",
          "name": "swapEnvironmentCNAMEs",
          "request": {
            "url": "http://example.com/api/?Action=SwapEnvironmentCNAMEs?DestinationEnvironmentId=DestinationEnvironmentId&DestinationEnvironmentName=DestinationEnvironmentName&SourceEnvironmentId=SourceEnvironmentId&SourceEnvironmentName=SourceEnvironmentName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Swaps the CNAMEs of two environments."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "01c34639-43b4-4aa9-bf9e-395eb2438768"
            }
          ]
        },
        {
          "id": "cc682ea2-338b-4fb7-b9be-f757bd1cb460",
          "name": "terminateEnvironment",
          "request": {
            "url": "http://example.com/api/?Action=TerminateEnvironment?EnvironmentId=EnvironmentId&EnvironmentName=EnvironmentName&ForceTerminate=ForceTerminate&TerminateResources=TerminateResources",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Terminates the specified environment."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6665393c-3689-4b7d-bac0-2203939e5850"
            }
          ]
        }
      ]
    },
    {
      "name": "DNS",
      "item": [
        {
          "id": "a11c0c8f-38e1-490e-acb6-10de729a6ab5",
          "name": "checkDNSAvailability",
          "request": {
            "url": "http://example.com/api/?Action=CheckDNSAvailability?CNAMEPrefix=CNAMEPrefix",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Checks if the specified CNAME is available."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e0b10a45-de4a-4866-8d2d-cf847f16a288"
            }
          ]
        }
      ]
    },
    {
      "name": "Applications",
      "item": [
        {
          "id": "ec338cdc-0c18-47dc-87e4-6748a47d8875",
          "name": "createApplication",
          "request": {
            "url": "http://example.com/api/?Action=CreateApplication?ApplicationName=ApplicationName&Description=Description&ResourceLifecycleConfig=ResourceLifecycleConfig",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an application that has one configuration template named default\n      and no application versions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6bf475c9-b797-4c47-b226-ea72423e8188"
            }
          ]
        },
        {
          "id": "cbfb64f6-0084-4bc9-bdc8-a03dfd7f708f",
          "name": "createApplicationVersion",
          "request": {
            "url": "http://example.com/api/?Action=CreateApplicationVersion?ApplicationName=ApplicationName&AutoCreateApplication=AutoCreateApplication&BuildConfiguration=BuildConfiguration&Description=Description&Process=Process&SourceBuildInformation=SourceBuildInformation&SourceBundle=SourceBundle&VersionLabel=VersionLabel",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates an application version for the specified application."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "06bf2e6e-da3d-49cc-8618-e093f8856f20"
            }
          ]
        },
        {
          "id": "2705e833-8954-48bc-8d8b-3fe46125b4c9",
          "name": "deleteApplication",
          "request": {
            "url": "http://example.com/api/?Action=DeleteApplication?ApplicationName=ApplicationName&TerminateEnvByForce=TerminateEnvByForce",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified application along with all associated versions and\n      configurations."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9b5669e1-afcb-4ad1-a155-5206b44faddd"
            }
          ]
        },
        {
          "id": "53a74741-912b-4d25-9f3c-869494fb6d76",
          "name": "describeApplications",
          "request": {
            "url": "http://example.com/api/?Action=DescribeApplications?ApplicationNames.member.N=ApplicationNames.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns the descriptions of existing applications."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6f56c649-9cb8-4fea-b620-9a8289e5d828"
            }
          ]
        },
        {
          "id": "2d5f37f4-0aa2-417b-814a-ef17b2c6072b",
          "name": "updateApplication",
          "request": {
            "url": "http://example.com/api/?Action=UpdateApplication?ApplicationName=ApplicationName&Description=Description",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Updates the specified application to have the specified properties."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "876227a2-5399-49c2-a008-ec0b74d69f0d"
            }
          ]
        }
      ]
    },
    {
      "name": "Configuration Templates",
      "item": [
        {
          "id": "85a1178f-9b1a-49d3-bc76-ccde26f1f9dd",
          "name": "createConfigurationTemplate",
          "request": {
            "url": "http://example.com/api/?Action=CreateConfigurationTemplate?ApplicationName=ApplicationName&Description=Description&EnvironmentId=EnvironmentId&OptionSettings.member.N=OptionSettings.member.N&SolutionStackName=SolutionStackName&SourceConfiguration=SourceConfiguration&TemplateName=TemplateName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates a configuration template."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "86760e4d-4fc8-4120-95f5-84d1f5e9f33f"
            }
          ]
        },
        {
          "id": "ed31cad7-d2e1-433e-85c7-51614833c593",
          "name": "deleteConfigurationTemplate",
          "request": {
            "url": "http://example.com/api/?Action=DeleteConfigurationTemplate?ApplicationName=ApplicationName&TemplateName=TemplateName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified configuration template."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "350fac4a-9915-47e1-adfd-f873f8fd46e5"
            }
          ]
        }
      ]
    },
    {
      "name": "Storage Location",
      "item": [
        {
          "id": "9941e823-2c01-465d-8abb-3fd07178ea6f",
          "name": "createStorageLocation",
          "request": {
            "url": "http://example.com/api/?Action=CreateStorageLocation?S3Bucket=S3Bucket",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Creates the Amazon S3 storage location for the account."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "69fd0448-7646-4da5-b8c7-ff6c0e2accf6"
            }
          ]
        }
      ]
    },
    {
      "name": "Application Version",
      "item": [
        {
          "id": "a4b33848-2aaf-48b0-b0f2-1b9238431d9c",
          "name": "deleteApplicationVersion",
          "request": {
            "url": "http://example.com/api/?Action=DeleteApplicationVersion?ApplicationName=ApplicationName&DeleteSourceBundle=DeleteSourceBundle&VersionLabel=VersionLabel",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Deletes the specified version from the specified application."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e83fd5ba-a04d-4b5c-b447-bea2cae6d6d4"
            }
          ]
        },
        {
          "id": "d38ff87d-16c8-49b8-9109-367a6e682a2b",
          "name": "describeApplicationVersions",
          "request": {
            "url": "http://example.com/api/?Action=DescribeApplicationVersions?ApplicationName=ApplicationName&MaxRecords=MaxRecords&NextToken=NextToken&VersionLabels.member.N=VersionLabels.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve a list of application versions."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9b79e35b-6c04-4ef1-a010-02d13c44b804"
            }
          ]
        }
      ]
    },
    {
      "name": "ConfigurationOptions",
      "item": [
        {
          "id": "12b3f80e-4dcc-4f6b-9cb7-0e9429af6e8d",
          "name": "describeConfigurationOptions",
          "request": {
            "url": "http://example.com/api/?Action=DescribeConfigurationOptions?ApplicationName=ApplicationName&EnvironmentName=EnvironmentName&Options.member.N=Options.member.N&SolutionStackName=SolutionStackName&TemplateName=TemplateName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Describes the configuration options that are used in a particular configuration\n      template or environment, or that a specified solution stack defines."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "214559a4-6898-4d9f-8ecb-59935ac60903"
            }
          ]
        }
      ]
    },
    {
      "name": "Configuration Settings",
      "item": [
        {
          "id": "15b78627-e02c-43b6-b59d-98703b58351a",
          "name": "describeConfigurationSettings",
          "request": {
            "url": "http://example.com/api/?Action=DescribeConfigurationSettings?ApplicationName=ApplicationName&EnvironmentName=EnvironmentName&TemplateName=TemplateName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a description of the settings for the specified configuration set, that is,\n      either a configuration template or the configuration set associated with a running\n      environment."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3e0d18f7-1c0e-4b20-b53b-d29b98663c0d"
            }
          ]
        }
      ]
    },
    {
      "name": "Events",
      "item": [
        {
          "id": "37e044d5-4c30-48c1-a55d-1a862babe113",
          "name": "describeEvents",
          "request": {
            "url": "http://example.com/api/?Action=DescribeEvents?ApplicationName=ApplicationName&EndTime=EndTime&EnvironmentId=EnvironmentId&EnvironmentName=EnvironmentName&MaxRecords=MaxRecords&NextToken=NextToken&RequestId=RequestId&Severity=Severity&StartTime=StartTime&TemplateName=TemplateName&VersionLabel=VersionLabel",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns list of event descriptions matching criteria up to the last 6 weeks."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7f16b8d9-21fe-4f15-86c7-2c5c263d983b"
            }
          ]
        }
      ]
    },
    {
      "name": "Instances Health",
      "item": [
        {
          "id": "1c31e081-a15f-4071-948f-2b80db807c47",
          "name": "describeInstancesHealth",
          "request": {
            "url": "http://example.com/api/?Action=DescribeInstancesHealth?AttributeNames.member.N=AttributeNames.member.N&EnvironmentId=EnvironmentId&EnvironmentName=EnvironmentName&NextToken=NextToken",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrives detailed information about the health of instances in your AWS Elastic\n      Beanstalk."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cfb15e3e-a3cc-4c63-b956-624c7d737aac"
            }
          ]
        }
      ]
    },
    {
      "name": "Solution Stacks",
      "item": [
        {
          "id": "3ef14aa9-cd17-4c0d-9b2f-423f982dc5d9",
          "name": "listAvailableSolutionStacks",
          "request": {
            "url": "http://example.com/api/?Action=ListAvailableSolutionStacks?SolutionStackDetails.member.N=SolutionStackDetails.member.N&SolutionStacks.member.N=SolutionStacks.member.N",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Returns a list of the available solution stack names."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3363d0c4-6d26-4a00-9b44-8ff3437746eb"
            }
          ]
        }
      ]
    },
    {
      "name": "App Servers",
      "item": [
        {
          "id": "593d5ccd-b964-4da0-aa3e-3c848e17a28d",
          "name": "restartAppServer",
          "request": {
            "url": "http://example.com/api/?Action=RestartAppServer?EnvironmentId=EnvironmentId&EnvironmentName=EnvironmentName",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Causes the environment to restart the application container server running on each\n      Amazon EC2 instance."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e1266465-63bc-463c-8089-9c57cd26b0cc"
            }
          ]
        }
      ]
    },
    {
      "name": "Application Resource Lifecycle",
      "item": [
        {
          "id": "72f6df11-2739-4cfd-9221-db220c48fe88",
          "name": "updateApplicationResourceLifecycle",
          "request": {
            "url": "http://example.com/api/?Action=UpdateApplicationResourceLifecycle?ApplicationName=ApplicationName&ResourceLifecycleConfig=ResourceLifecycleConfig",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Modifies lifecycle settings for an application."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5938e0a5-1c8c-4272-b759-74003375b296"
            }
          ]
        }
      ]
    }
  ]
}