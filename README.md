
# cloudtrainingnotes

## Pillaging Cloud Assets
    Gaining Access Review
    Situational Awareness
    Persistence
    Privilege Escalation
    Data Harvesting

## Labs

    Backdooring an AWS Account - Slide 36
    Azure Service Principal Backdoor - Slide 62
    AWS Privilege Escalation with Pacu and Obtaining Web Console Access - Slide 105
    Dumping Azure key Vault keys - Slide 142

    What's next after breaking in cloud environment?
        
        Maintain Access



## Gaining Access - Exploiting Misconfigs

Sometimes configuration issues cause data to leak publicly
Look for both sensitive data and additional access keys
Examples:
    -public azure blobs
    -public s3 buckets
    -s3 code injections
    -s3 domain hijacking

## Gaining access - footholds

Publicly exposed access keys on github/bitbucket/gitlab

password attacks
    -spraying
    -stuffing

Web server exploitation
Phishing
    -steal access tokens



# ROADMAP


# Situational Awareness

- General Post-Compromise REcon
- Who are we?
- What roles do we have?
- Is MFA enabled?
- What can we access (webapps, storage, etc?)
- Who are the admins?
- How are we going to escalate to admin?
- Any security protections in place (ATP, GuardDuty, etc.)?

## Situation Awareness - AWS

- Yay we got AWS keys! now what?
- at the top level you have an AWS account that has full access
- IAM users and groups
- Roles that provide temporary credentials

- AWS Command Line
    - https://aws.amazon.com/cli

    ![situationalawarenessAWS](https://user-images.githubusercontent.com/71202250/125658632-6f1baa77-427b-4d25-897b-a7f27be1b3fb.JPG)
    ![GCPsituationAwareness](https://user-images.githubusercontent.com/71202250/125658636-7c1d90cf-f086-4c9e-982b-460aa9535cec.JPG)
