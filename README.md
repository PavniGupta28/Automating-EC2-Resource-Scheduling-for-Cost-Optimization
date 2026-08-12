# EC2 Automation with AWS Lambda

An AWS automation project that automatically **starts and stops EC2 instances on a scheduled basis** using **AWS Lambda, Amazon EventBridge Scheduler, and Boto3**.

## Architecture

Amazon EventBridge Scheduler
            ↓
       AWS Lambda
        ↙      ↘
   EC2 Start   EC2 Stop
            ↓
       Amazon EC2
```

##  AWS Services

* AWS Lambda
* Amazon EventBridge Scheduler
* Amazon EC2
* AWS IAM
* Amazon CloudWatch
* Boto3

##  Key Features

* Automated EC2 start and stop
* Cron-based scheduling
* Lambda functions using Python and Boto3
* IAM-based permissions
* Reduced unnecessary EC2 running time and costs

##  Verification
The automation was tested successfully, and the EC2 instance was confirmed to transition between **Running** and **Stopped** states according to the configured schedules.



## Author

**Pavni Gupta**
