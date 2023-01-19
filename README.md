## AmazonMSK-Managed-Observability



CloudFormation Templates :

* If you have an existing Amazon MSK cluster and want to deploy this observability solution for the same cluster, use below mentioned template files
	* Prometheus_Cloudformation.yml - Deploys EC2 with docker service, Security Groups, etc.
	* AMG_AMP_Cloudformation.yml - Deploys resource for Amazon Managed Prometheus and Amazon Managed Grafana

* If you don't have any existing Amazon MSK cluster or you would like to do a PoC for this Amazon Managed observability solution for MSK, use below template files to deploy the resources
	* MSKResource_Cloudformation.yml - Deploys resources for needed to run Amazon MSK Cluster in a new VPC viz. VPC, Subnets, IAM Roles, Kafka Client, Cloud9, EC2 to run Prometheus service, etc.
	* AmazonMSK_Cloudformation.yml - Deploys resources for Amazon MSK
	* AMG_AMP_Cloudformation.yml - Deploys resource for Amazon Managed Prometheus and Amazon Managed Grafana



## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

