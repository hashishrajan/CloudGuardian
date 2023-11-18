# CloudGuardian
Cloud Guardian is an AI based Cybersecurity Assistant with deep knowledge for Cloud Security in Public &amp; Hybrid Cloud environments.

In other words, Cloud Guardian is a Custom AI agent which is trained on interviews from guests across 150+ episodes that are in the Cloud Security Engineering, Cloud Security Architecture, Cloud Security Directors, CISOs, Cloud Security Researchers that have been interviewed on Cloud Security Podcast a Top 10 ranked podcast & YouTube channel for Cloud Security.

![DALL·E 2023-11-14 22 36 05 - A professional and friendly cloud character for 'Cloud Guardian', with a builder's hat featuring a cybersecurity shield logo  The cloud is designed in](https://github.com/hashishrajan/CloudGuardian/assets/10039370/743ad8a6-cb56-41a9-b797-6b5a61c9aec1)


## Who are we?
We are [Cloud Security Podcast](https://www.cloudsecuritypodcast.tv/), an award winning Top 10 ranked "VodCast" which release new episodes on Cloud Security every week on all popular Audio and Video Platform across the social media.

## What is in this repository
This is an open source repository, which is the current space to store the Training data used to train Cloud Guardian. If you would like access to the API for the AI Agent, please raise an Issue and we will get back to.

## What can it do?
- Help understand Cloud Security Concepts from AWS, Azure & GCP
- Provide example templates for Infrastructure as Code and other forms of cloud security automation
- Provide example of cloud security best practices
- Provide sample architecture (it is linked to Dalle)
- Sky is the limit - please feel free to raise a PR

## What it cannot do?
- Cannot provide Medical Advice
- Cannot provide Legal Advice
- Cannot provide guarrantee that all provided information is accurate at any point in time - please use your judgement and understanding of cloud security to know if the provided answer is what you expect.


## Current Gaps with Custom AI Agent and hence "Cloud Guardian"
- No response from ChatGPT interface once the training data is uploaded. No confirmation on if it understood the provided training data and if the format is right, is there a need for ETL. 
- It only shares conceptual information in great detail but
- Prompt engineering is limited as the description of what the Custom AI Agent can do is the extent of what you prompt
- There is no way to educate or correct if a security standard is no longer considered safe e.g in 1998 only having username & password was good security but in 2023 you must have username/password and multi-factor authentication
- Asking for code examples doesn't share
- There are limited number of AWS & Azure services that can linked to the Agent using AI Actions. However, none exist for Google Cloud APIs in Zapier (the provider to use to integrate AI agent to other services).
- Even though this uses GPT-4 engine, there seems to be no internet connectivity
- Initial Data set for AI Agent when created is limited to what the ChatGPT dataset is, which is April,2023.

Last Update: 16-Nov-2023
