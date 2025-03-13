# Cloud-Monitoring-and-Alerts

COMPANY NAME: CODTECH IT SOLUTIONS

NAME: ANWAY DHARKAR

INTERN ID: CT08WPV

DOMAIN: CLOUD TECHNOLOGY

DURATION: 4 WEEKS

MENTOR: NEELA SANTOSH

DESCRIPTION: **TASK 2**: CLOUD MONITORING AND ALERTS

🚀 Step 1: Enable Google Cloud Monitoring
Go to Google Cloud Console: https://console.cloud.google.com/.
Select your project (my-unwritten-chapters)
Navigate to Monitoring → Overview.
Click on Enable Monitoring API (if not enabled).
Wait a few seconds for the service to activate.
![Screenshot 2025-03-11 004226](https://github.com/user-attachments/assets/f74603f4-208a-47d1-911e-7f6a2dbcaef1)

📊 Step 2: Create a Custom Dashboard
In the Google Cloud Console, navigate to:
Monitoring → Dashboards → + Create Dashboard.
Give your dashboard a name, like App Monitoring Dashboard.
Click Add Chart.
Choose metrics you want to monitor like:
CPU Usage → For Compute Engine.
HTTP Requests → For App Engine or Cloud Run.
Memory Usage → For Compute Engine instances.
Configure the chart and click Save.
You can add multiple charts to your dashboard.
![Screenshot 2025-03-11 005803](https://github.com/user-attachments/assets/3258f62f-5c7d-4492-afa4-0db82ccc7a39)

⚠️ Step 3: Configure Alerts
Go to Monitoring → Alerting → + Create Policy.
Under Conditions, click Add Condition.
Select a Resource Type like:
Compute Engine VM Instance → CPU usage, Memory usage, Disk usage.
App Engine → HTTP traffic, Error Rate.
Define your alert threshold (e.g., CPU usage > 80%).
Under Notifications, add your email or SMS (if configured).
Name the alert policy like High CPU Usage Alert.
Click Create Policy.
![Screenshot 2025-03-13 171858](https://github.com/user-attachments/assets/35aa21fc-f62a-4834-b20f-de84f178b03d)

✅ Step 4: Test Alerts
Stress test your application (optional) or wait until a threshold is crossed.
Check if the alert gets triggered.
Verify you receive an email notification (if configured).
Go to Monitoring → Alerting → View Incidents.
![Screenshot 2025-03-13 155359](https://github.com/user-attachments/assets/4f2d9486-ca56-4c07-aea6-ccb351515c59)
