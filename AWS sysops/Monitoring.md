### Cloud Watch

* Monitor resources and applications that run on AWS(monitor performance)

##### Host Level metrics consists of:
1. CPU utilization
2. Network
3. Disk
4. Status Checks

Note **

* Ram Utilization is a custom metric
* For Custom Metric: min granularity=1 minute(Turn on detailed monitoring)
* Standard monitoring set in EC2 will give 5 minute intervals

#### Terminated Instances
You can retrieve data from any terminated EC2 or ELB instance after its termination. CloudWatch Logs by default are stored indefinitely.

#### Metric Granularity

* 1 minute for detailed monitoring
* 5 minutes for standard monitoring

###### Cloudwatch can also be used on premise
Not Restricted to just AWS resources. Can be on premise too. Just need to download and install the SSM agent and CloudWatch agent.

#### EBS Different Volume Types

5 Different Types of EBS Storage:
* General Purpise(SSD)
* Provisioned IOPS(SSD)
* Throughput Optimised Hard Disk Drive
* Cold Hard Disk Drive
* Magnetic
 ###### Key IOPS Metrics:
 You can burst up to 3000 IOPS. If you need more than 3000 but less than 10,000 just increase the volume size. Anything over 10,000 IOPS move to PIOPS.(Provisioned IOPS)

#### CloudTrail

CloudTrail monitors API calls in the AWS platform.

#### ELB- Monitoring Types
4 Different Ways to monitor your load balancers

1. CloudWatch metrics
2. Access logs: Trace errors using **Access Logs** stored in S3 for EC2 instances that are already deleted.
3. Request Tracing
4. CloudTrail logs
























