# TASK_02

## AWS Command Line Interface
✍ Create a Key pair.
✍ Create a Security group.
✍ Launch an INSTANCE using the above created Key pair and Security group.
✍ Create an EBS Volume of size 1 GB.
✍ And the final step is to attach above created EBS volume to the Instance created in previous steps.

# TASK_03

##  Deploying Amazon RDS with Wordpress
🔆 Create an AWS EC2 instance
🔅 Configure the instance with Apache webserver.
🔅 Download PHP application name wordpress.
🔅 As wordpress stores data at the backend in MySQL database server. Therefore we need to Setup a MySQL server using AWS RDS service using Free tier.
🔅 Provide the endpoint/ connection string to PHP application to make it work.

# Task_05

## High Availability Architecture with AWS cli
📌 Webserver configured on EC2 Instance.
📌 Document Root(/var/www/html) made persistent by mounting on EBS Block Device.
📌 Static objects used in code such as pictures stored in S3
📌 Setting up Content Delivery Network using CloudFront and using the origin domain as S3 bucket.
📌 Finally,place the Cloud Front URL on the web app code for security and low latency.
