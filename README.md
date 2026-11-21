# Chapter-4-Compute-Fundamentals
Lab Work for Mad Hat
INTERVIEW STORIES THIS CREATES
1. Walk me through how you would review a deployment before it goes to production.

I would follow a five-part security review to identify potential risks before approving a production deployment.

Step

Security Check

What I Look For

1. Exposed URLs

Public exposure

Publicly accessible URLs, API keys, tokens, or other sensitive information.

2. Identity

Authentication & permissions

Proper authentication, managed identities, and least-privilege access.

3. Open Front Door

Network security

Network security rules, firewalls, and unnecessary public entry points.

4. Wrong Region

Resource compliance

Resources deployed in approved Azure regions and compliance with organizational policies.

5. Final Review

Monitoring & configuration

Logs, security alerts, resource configurations, and deployment policies.


2. You find four or more issues at once. How do you decide what to fix first?

My approach: Exposure beats hygiene. Active threats beat potential threats.

I would prioritize the exposed URL first because it could contain sensitive information or credentials that an attacker could use to gain access.


3. What is a managed identity and why does it matter?

A managed identity allows an Azure resource to authenticate to other Azure services without storing credentials in configuration files.

4. How would you prove a storage container is actually exposed rather than just misconfigured?

If you can list or receive files from a storage container without authentication then it proves it was exposed. The misconfiguration of files from storage container is when the settings don't follow the security requirements issued by the organization.



5. "Tell me about a time you had to block or push back on something." You blocked a ship. That is the story.
I have experience moderating Twitch streams, where I've had to block people who repeatedly violated community rules or appeared to be bots. I would look at their behavior, determine whether they were legitimate viewers or suspicious accounts, and take action when necessary. Sometimes that meant blocking someone to prevent spam or protect the community. I learned that it's important to recognize suspicious activity and act on it rather than ignore it just because it might be inconvenient.
