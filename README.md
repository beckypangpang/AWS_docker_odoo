# AWS_docker_odoo
deploying Odoo in Docker on an AWS EC2 instance
# AWS_EC2_Docker

## AWS Framework

<p align="center">
  <img src="https://github.com/beckypangpang/AWS_docker_odoo/blob/main/AWS%20(2019)%20horizontal%20framework.jpeg" alt="AWS Framework" width="500">
</p>

# AWS EC2 Instance Setup with Docker

## Launch an AWS EC2 Instance

1. Go to [AWS EC2](https://aws.amazon.com/ec2/) and launch an instance.
2. Choose the OS image (e.g., Ubuntu, macOS, Windows) and select a free tier eligible instance type (CPU/memory).
3. Set up a security group to control the instance's traffic.

## Install Docker on EC2 Instance

Connect to your EC2 instance and execute the following commands:

### Using apt (for Ubuntu):

```bash
sudo apt update
sudo apt install docker.io
```


