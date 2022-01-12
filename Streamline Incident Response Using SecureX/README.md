# Streamline Incident Response Using SecureX

Simplify, automate, and streamline incident response by integrating Secure X, Service Now, WebEx, with Umbrella & Cloud Security Analytics.

 
## Use Case Description

CloudAIR simplifies and automates incident response procedures for Amazon EC2 instances. Running the workflow on a schedule, it will query Cisco Umbrella, Cisco Secure Cloud Analytics (formerly known as Stealthwatch Cloud), and Amazon GuardDuty to detect indications of compromise. If a compromise is suspected, the workflow will create a ServiceNow ticket, generate a remediation request and push instance details and request WebEx room.

Incident response procedures are detailed in the published [Amazon AWS Incident Response Guide](https://docs.aws.amazon.com/whitepapers/latest/aws-security-incident-response-guide/aws-security-incident-response-guide.pdf) and include:
  
  	• Enabling Termination Protection
	• Moving the compromised instance to an isolated security group.
	• Removing the instance from auto-scaling groups (ASGs).
	• Removing the instance from an elastic load balancer (ELB).
	• Creating forensic snapshots of elastic block devices.• • Adding tags to compromised hosts.

## Related Code Exchange Submission

 •Please see the serverless relay module installation information [here](https://developer.cisco.com/codeexchange/github/repo/CiscoDevNet/tr-05-aws-vpc-logs)
 •[Code Exchange submission for this project] https://developer.cisco.com/codeexchange/github/repo/CiscoDevNet/sxo_aws_ir
 •

## White Paper

[AWS IR Whitepaper](https://docs.aws.amazon.com/whitepapers/latest/aws-security-incident-response-guide/aws-security-incident-response-guide.pdf#welcome/)

[From Complex to Cohesive](https://www.cisco.com/c/en/us/products/collateral/security/white-paper-c11-744498.html)

[Watch Brian Sak & Brennan Bouchard present at Devnet Create](https://www.youtube.com/watch?v=jGAC1RSKzMw)
## Usage

Show users how to use the code. Be specific.
Use appropriate formatting when showing code snippets or command line output.

### Related Sandbox

Anyone may create a [SecureX account](https://sign-on.security.cisco.com/) for free.

## DevNet Learning Labs

Get Started with theses [SecureX Modules](https://developer.cisco.com/learning/tracks/SecureX) on Devnet

## Solutions on Ecosystem Exchange

More SecureX solutions on [Cisco Ecosystem Exchange here](https://developer.cisco.com/ecosystem/solutions/#key=securex)



## Author(s)

This project was written and is maintained by the following individuals:

* Brian Sak <brsak@cisco.com>
