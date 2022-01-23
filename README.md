# AWS-Monitoring-Logging
AWS-Monitoring &amp; Logging

# Cloudtrail
cloudtrail will by default record of the actions performed in our AWS account.
- This events can be delivered to S3 bucket or to a Cloudwatch logs by creating a trail.
- To craete a trail, give trail name, for the event management, we can slect all the reads/writes, 
- For the data events, we can record S3 object-level API activity, we can also capture data events for lambda by looking at the record invoke API operations for individual functions for all and future functions in your AWS account. For the data event source, select an S3 bucket.
- 
