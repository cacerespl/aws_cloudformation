Description

This is a Cloud Formation template in yaml format, that create the following:

- A VPC with cidr block 10.0.0.0/16
- A public subnet with cidr block 10.0.0.0/24
- Two (02) security groups (SG): one for a Linux instance and aonther for a Windows instance.
- One (01) Linux instance that will have apache installed.
- One (01) Windows instance that will have IIS installed.

The template should run on the Virginia Region.
