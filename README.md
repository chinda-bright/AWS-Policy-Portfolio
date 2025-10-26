# AWS Cloud Practice & Policy Portfolio

This repository documents my journey toward becoming an AWS Solutions Architect and AI specialist. It contains practical AWS implementations, policies, and solutions I've built while mastering cloud architecture and security.

## Current Focus: IAM & Security Foundations

As I work toward AWS Solutions Architect certification, I'm building a strong foundation in identity and access management.

### IAM Policies

#### (1) HR User Management Policy

**Purpose:** Basic user account management for HR team

**Use Case:** New employee onboarding, password resets, user group management

**Security Considerations:** Prevents user deletion and policy modification to maintain security boundaries

**File:** `iam-policies/HR-User-Management.json`

**Key Permissions:**
- Create new IAM users
- Add users to existing groups  
- Reset user passwords
- View user and group information
- Explicitly denies user deletion and policy creation

---
#### (2) Finance Team Billing Policy

**Purpose:** Read-only access to AWS billing and cost data for finance team  
**Use Case:** Read-Only Billing and Cost usage for Finance Teams to support Budget Planning and Cost Reporting  
**Security Considerations:** Provides visibility into costs without any ability to modify AWS resources or infrastructure settings 

**File:** `iam-policies/FinanceTeam-BillingReadOnly.json`

**Key Permissions:**

- View AWS billing information and charges
- Access detailed usage reports
- Generate cost analysis through Cost Explorer
- View AWS Cost and Usage Reports
- Monitor spending across all AWS services
- Read-only access only - no modification rights to any resources

----

#### (3) Developer Team Resource Access Policy

**Purpose:** Development environment access for application developers  
**Use Case:** Code repository management, application debugging, and serverless development with strict development-only resource restrictions  
**Security Considerations:** Restricted to "dev-*" named resources only, preventing access to production or staging environments  
**File:** `iam-policies/DevTeam-ResourceAccess.json`  

**Key Permissions:**

- Git operations on CodeCommit repositories (pull, push, view)
- Read/write access to development S3 buckets and objects
- CloudWatch logs access for application debugging and monitoring
- Lambda function management for serverless development
- All access restricted to resources with "dev-" naming prefix
- No production or critical infrastructure access

----------

#### IAM SUMMARY

I have now completed the IAM lessons and created some IAM Policies 
This section is where I summarise ALL I have learned about IAM  
**File:** `learning-logs/IAM Summary.json`

----------

## Future Sections (Coming Soon)
- **S3 & Storage Solutions**
- **EC2 & Compute Architecture** 
- **AI/ML Service Implementations**
- **Multi-tier Application Architectures**
- **Cost Optimization Strategies**

## About My Learning Path

🎯 **Goal:** AWS Solutions Architect → AI/ML Specialist  
📚 **Current:** AWS Cloud Practitioner Foundations  
🔄 **Next:** AWS AI Practitioner Foundations

This portfolio showcases practical, real-world scenarios and security-first thinking as I build toward enterprise-level cloud architecture expertise.
