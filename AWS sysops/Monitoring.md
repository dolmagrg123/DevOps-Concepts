### Cloud Watch

* Monitor resources and applications that run on AWS

#### Host Level metrics consists of:
1. CPU utilization
2. Network
3. Disk
4. Status Checks

* Ram Utilization is a custom metric
* For Custom Metric: min granularity=1 minute(Turn on detailed monitoring)
* Standard monitoring set in EC2 will give 5 minute intervals

#### Terminated Instances
You can retrieve data from any terminated EC2 or ELB instance after its termination. CloudWatch Logs by default are stored indefinitely.

#### Metric Granularity

* 1 minute for detailed monitoring
* 5 minutes for standard monitoring

##### Cloudwatch can also be used on premise
Not Restricted to just AWS resources. Can be on premise too. Just need to download and install the SSM agent and CloudWatch agent










