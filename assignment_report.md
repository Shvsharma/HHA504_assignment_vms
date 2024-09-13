VM Creation in Google Cloud Platform (GCP)
Screenshots of VM Creation:
![Screenshot (63)](https://github.com/user-attachments/assets/45691bc5-5e09-48a7-a921-82aa679c6e22)
![Screenshot (64)](https://github.com/user-attachments/assets/468ece55-a4de-455c-8357-082ceee0ed52)
![Screenshot (61)](https://github.com/user-attachments/assets/29cd7928-ccbb-4255-8a3a-714c04841bf2)
![Screenshot (62)](https://github.com/user-attachments/assets/765711b1-c9b1-44fd-aa58-e308a5c64e62)

Steps Followed:
- Signed in to Google Cloud Platform.
- Navigated to Compute Engine > VM instances.
- Configured a new VM using the e2-micro instance type.
- Created and started the VM.
- Let the VM run for a few minutes and then stopped it.

Cost Comparison (GCP)
Since Azure was not accessible during this project, I focused on GCP:
- Pricing Structure: GCP’s pricing is based on per-second billing, which allows for precise cost control. This makes it ideal for dynamic workloads where VMs are frequently started and stopped.
- Costs: vCPU + 1 GB memory: $6.11 per month.
- 10 GB balanced persistent disk: $1.00 per month.
- Total Estimated Cost: $7.11 per month, which includes the compute resources and storage. This estimate is based on 720 hours (one month of constant usage) and includes per-second billing.
- Hourly Cost: Approximately $0.01 per hour for running the instance continuously.

Reflections on My Experience with GCP:
- Ease of Use: Google Cloud Platform’s Console is very user-friendly. The step-by-step VM creation process is straightforward, even for beginners. The interface provides helpful tips and automatic suggestions for instance types, zones, and configurations.
- Cost Management: The ability to monitor costs in real-time through GCP’s billing reports is a helpful feature. The transparency of the billing system allowed me to easily check how much my instance cost during the runtime, with clear breakdowns of potential future charges.
- Performance Monitoring: GCP provides built-in monitoring tools that show resource usage, helping me understand how the VM performs. This is useful for optimizing VM configurations.
- Overall Experience: GCP made it simple to create, manage, and monitor VM instances. The free tier and the flexibility of stopping and restarting VMs, ensured that I didn’t incur any costs while completing this assignment.
