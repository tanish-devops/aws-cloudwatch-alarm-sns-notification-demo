# aws-cloudwatch-alarm-sns-notification-demo

AWS CloudWatch is a comprehensive monitoring and observability service designed for DevOps engineers, developers, and IT managers to track, monitor, and analyze metrics, logs, and events from AWS resources and on-premises servers in real time.

Key components of CloudWatch:
Metrics: Collects and tracks performance data (e.g., CPU utilization) for AWS services like EC2 and RDS.
Logs: Centralizes and monitors logs from applications and services, allowing for anomaly detection.
Alarms: Automates actions, such as stopping underused instances or sending alerts, based on defined thresholds.
Dashboards: Provides a single, customizable view of system-wide health and resource performance. 

Key Benefits:
Real-time Monitoring: Provides instantaneous visibility into application performance and infrastructure health.
Operational Health: Helps identify performance bottlenecks and system-wide changes to ensure smooth operations.
Cost Optimization: Aids in identifying underutilized resources, leading to potential cost savings. 

I have monitored EC2 CPU usage by :-

I have spiked the cpu utilization, and an alarm was created to trigger when the metric crossed a specified threshold. The alarm was integrated with Amazon Simple Notification Service (SNS), which delivered real-time email notifications upon state changes. This implementation demonstrates how monitoring, alerting, and automated notification systems can be built to improve reliability, availability, and operational visibility in cloud environments
