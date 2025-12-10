# Ansible Automation Platform (AAP) - Running a Playbook in AAP
Author: Russell Zachary Feeser  
GitLab & GitHub: @RZFeeser  
Contact: https://iris7.com || https://rzfeeser.com  

This solution is intentionally kept simple for the purposes of education and testing scenarios.

## Overview
Hey gang! Professor Feeser here. This repository is used to demo running a playbook within AAP via a video on my [YouTube Channel @CodeWithFeeser](https://www.youtube.com/@CodeWithFeeser). More broadly, it contains a simple playbook that queries http://api.open-notify.org/astros.json with the Ansible uri module, registers the results, and debugs that too the screen.


## Video Demos
Videos demonstrating use of this playbook in Ansible Automation Platform is available on the author's [YouTube Channel @CodeWithFeeser](https://www.youtube.com/@CodeWithFeeser):  

- [Ansible Automation Platform - Running a Playbook in AAP](https://youtu.be/_3sNz4kYSUs?si=megIY5LCbSMCZSbr)

If you found a video helpful, be sure to hit **like** and **subscribe** for weekly lessons from [YouTube Channel @CodeWithFeeser](https://www.youtube.com/@CodeWithFeeser)


## How It Works
There are some notable features of playbooks/playbook01.yml

1. Queries an Open API `http://api.open-notify.org/astros.json`
2. The JSON returned is a list of humans currently housed on spaceports around the Earth


## Resources
- https://access.redhat.com/products/red-hat-ansible-automation-platform


### About the Author
Russell Zachary Feeser (@RZFeeser) is the owner of [IRIS7](https://iris7.com), which provides consultantcy services, and professional training across various technologies including Ansible, Python, AWX/Tower/AAP, Terraform, Go, Cloud Hyperscalering (Azure, AWS, GCI), 5G and core telecom communications. If you're interested in discussing a consulting or training project, feel free to reach out.  
- https://iris7.com
- https://rzfeeser.com
