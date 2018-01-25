# quickstart-datalake-informatica
## Informatica Data Lake Management on the AWS Cloud

This Quick Start builds a data lake environment on the Amazon Web Services (AWS) Cloud by deploying the Informatica Data Lake Management solution and AWS services such as Amazon EMR, Amazon Redshift, Amazon Simple Storage Service (Amazon S3), and Amazon Relational Database Service (Amazon RDS).

The Quick Start configures the AWS infrastructure, deploys the Informatica Data Lake Management components, and automatically embeds Hadoop clusters in the virtual private cloud (VPC) for metadata storage and processing. It assigns the connection to the Amazon EMR cluster for the Hadoop Distributed File System (HDFS) and Hive. It also sets up connections to enable scanning of Amazon S3 and Amazon Redshift environments as part of the data lake.

The Quick Start offers two deployment options:

- Deploying the data lake into a new VPC on AWS
- Deploying the data lake into an existing VPC on AWS

You can also use the AWS CloudFormation templates as a starting point for your own implementation.

![Quick Start architecture for Informatica Data Lake Management on AWS](https://d0.awsstatic.com/partner-network/QuickStart/datasheets/informatica-data-lake-architecture-on-aws.png)

For architectural details, best practices, step-by-step instructions, and customization options, see the 
[deployment guide](https://s3.amazonaws.com/quickstart-reference/datalake/informatica/latest/doc/informatica-data-lake-management-on-the-aws-cloud.pdf).

To post feedback, submit feature ideas, or report bugs, use the **Issues** section of this GitHub repo.
If you'd like to submit code for this Quick Start, please review the [AWS Quick Start Contributor's Kit](https://aws-quickstart.github.io/). 
