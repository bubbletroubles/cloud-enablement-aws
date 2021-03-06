# Cloud Enablement

This repository contains open source projects to enable MarkLogic running in the Cloud.  
For general information about MarkLogic in the Cloud, please visit [MarkLogic in the Cloud](https://developer.marklogic.com/products/cloud).

## MarkLogic CloudFomration Template on AWS

The CloudFormation templates provide options to launch MarkLogic clusters with different settings. The parameterized templates will ask users to choose configurations prior to launch. With the chosen setting, the template will create resources by AWS service including but not limited to Elastic Compute Cloud, Elastic Block Storage, Virtual Private Cloud, DynamoDB, Simple Notification Service, CloudWatch, Lambda Functions, Elastic Load Balancer. The following image shows a typical architecture of the cluster on AWS.

This repository contains master templates, sub-templates and other resources that are used by CloudFormation such as Lambda function source code.

For details, see [Getting Started and Reference Architecture Guide](https://github.com/marklogic/cloud-enablement/blob/master/aws/README.md) in AWS directory.

## MarkLogic Solution Template on Azure

The Solution Template for MarkLogic on Azure helps to deloy clusters on Azure. It is publicly offered on Azure Marketplace. This repository contains templates and resources to set up and initialize MarkLogic clusters with these Azure features: Availability Set, Virtual Network, Load Balancer, Network Security Group, Virtual Machines, etc. MarkLogic features such as local-disk failover will be configured for the cluster.

For details, see [Getting Started and Reference Architecture Guide](https://github.com/marklogic/cloud-enablement/blob/master/azure/README.md) in Azure directory.

## Support

The cloud-enablement repository is maintained by MarkLogic Engineering and distributed under the [Apache 2.0 license](https://github.com/marklogic/cloud-enablement/blob/master/LICENSE.TXT). Everyone is encouraged [to file bug reports, feature requests, and pull requests through GitHub](https://github.com/marklogic/cloud-enablement/issues/new). Your input is important and will be carefully considered. However, we can’t promise a specific resolution or timeframe for any request. In addition, MarkLogic provides technical support for [releases](https://github.com/marklogic/cloud-enablement/releases) of cloud-enablement to licensed customers under the terms outlined in the [Support Handbook](http://www.marklogic.com/files/Mark_Logic_Support_Handbook.pdf). For more information or to sign up for support, visit [help.marklogic.com](http://help.marklogic.com).
