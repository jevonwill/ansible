# Ansible Automation for dailyWisdom App

# Phases


0: Configure dynamic inventory script for AWS.

1: Ansible create VPC, 2 private & 2 public subnets across 2 AZ
2: Create EC2 instance, install Apache, pull git repos and run script
3: Create auto-scaling group and ELB.
4: Cronjob on Ansible control node runs every 60 seconds.
