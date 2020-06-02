# The Bible: AWS Well Architected Framework
This is THE most important official guide to the exam, or any AWS certification exam really. Study this inside out.

# Five Pillars
## Operational Excellence
The ability to run and monitor systems to deliver business value and to continually imrpove supporting processes and procedures.
### Design Principles for Operational Excellence (6 in total)
- Perform operaiotns as code.
- Annotate documentation.
- Make frequent, small, reversible changes.
- Refine operations procedures frequently.
- Anticipate failure.
- Learn from all operational failures.

## Security
The ability to protect information, system, and assets while delivering business value through risk assessments and mitigation strategies. 
### Design Principles for Security (7 in total)
- Implement a strong identity foundation.
- Enable traceability.
- Apply security at all layers.
- Automate security best practices.
- Protect data in transit and at rest.
- Keep people away from data.
- Prepare for security events.
### Services Involved
- AWS Identity and Access Management (IAM)
- AWS MFA
- AWS Organizations
- AWS CloudTrail
- AWS Virtual Private Cloud (VPC)
- AWS CloudFront
- AWS Web Application Firewall (WAF)
- AWS Key Management Services (AWS KMS)
- AWS CloudWatch Events
- AWS CloudFormation

## Reliability
The ability of a system to recover from infrastructure or service disruptions, dynamically acquire computing resources to meet demand, and mitigate disruptions such as misconfigurations or transient network issues.
### Design Principles for Reliability (5 in total)
- Test recovery procedures
- Automatically recover from failure
- Scale horizontally to increase aggregate system availability
- Stop guessing capacity
- Manage change in automation

## Performance Efficiency
The ability to use computing resources efficiently to meet system requirements, and to maintain that efficiency as demand changes and technology evolve.
### Design Principles for Performance Efficiency (5 in total)
- Democratize advanced technologies
- Go glocal in minutes
- Use serverless architectures
- Experiment more often
- Mechanical sympathy

## Cost Optimization
The ability to run systems to deliver business value at the lowest price point.
### Design Principles for Cost Optimization (5 in total)
- Adopt a consumption model
- Measure overall efficency
- Stop spending money on data center operations
- Analyze and attribute expenditure
- Use managed and application level services to reduce cost of ownership

# General Design Principles
- Stop guessing your capacity needs.
- Test systems at production scale.
- Automate to make architectural experimentation easier.
- Allow for evolutionary architectures.
- Drive architectures using data.
- Improve through game days.
