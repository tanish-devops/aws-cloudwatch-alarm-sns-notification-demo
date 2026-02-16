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


>> SNS Confirmation: A security step where you must click "Confirm subscription" in Gmail to authorize AWS to send you alerts.


<img width="1462" height="577" alt="Screenshot 2026-02-17 040909" src="https://github.com/user-attachments/assets/ff61006c-263d-445b-9b21-d394ae8f4e4c" />


>> CloudWatch Dashboard: AWS CloudWatch dashboard monitoring the CPU Utilization of an EC2 instance. The graph indicates that the 50% cpu utilization threshold was hit, triggering an "In alarm" state, as indicated by the red sections on the timeline.

<img width="1429" height="477" alt="Screenshot 2026-02-17 042743" src="https://github.com/user-attachments/assets/1d0689d7-8d4f-4f7d-a4b0-48d597dbde8d" />


>> The Alert: Real-Time Notification
The image is the resulting Gmail alert from Amazon SNS, confirming that the "ec2-surpass-50" alarm transitioned to the ALARM state because the metric exceeded the 50.0 limit.


<img width="1481" height="690" alt="Screenshot 2026-02-17 043820" src="https://github.com/user-attachments/assets/ce218d30-2154-49c2-8632-fc129f48147d" />



This implementation showcases how monitoring, alerting, and automated notifications work together to improve infrastructure reliability. It reflects practical knowledge of AWS observability services and demonstrates the ability to design and test real-time cloud monitoring solutions.

