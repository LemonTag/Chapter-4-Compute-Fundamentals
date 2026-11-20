# Chapter-4-Compute-Fundamentals
Lab Work for Mad Hat
INTERVIEW STORIES THIS CREATES
"Walk me through how you would review a deployment before it goes to production." You have a five-part answer and most candidates have none. 

1.Exposed URL: Check for publicly exposed URLs, API keys, tokens, or other sensitive information.

2.Identity: Verify that users and services have proper authentication, managed identities, and only the permissions they need.

3.Open Front Door: Review network security rules, firewalls, and public access to make sure unnecessary entry points are closed.

4.Wrong Region: Verify that resources are deployed in the approved Azure region and meet company policies.

5.Final review: Check logs, security alerts, configurations, and deployment policies before approving production.


"You find four (or more) issues at once. How do you decide what to fix first?" Exposure beats hygiene, active beats potential. Give the example.

I would prioritize the exposed URL first because it could contain sensitive information or credentials that an attacker could use to gain access. I prioritize active security threats over configuration and compliance issues. I would focus on exposure first, then identity and network security, and finally less urgent configuration issues like the wrong region.



"What is a managed identity and why does it matter?" Because the alternative is a credential sitting in configuration, and credentials in configuration end up in places like a public container.

Managed identity allows an Azure resource to authenticate to other services without storing credentials in configuration files. It matters because it reduces the risk of exposed passwords, API keys, and secrets. It also allows administrators to control what resources that identity can access.

"How would you prove a storage container is actually exposed rather than just misconfigured?" Private window, no session, open the URL... 

If you can list or receive files from a storage container without authentication then it proves it was exposed. The misconfiguration of files from storage container is when the settings don't follow the security requirements issued by the organization.



"Tell me about a time you had to block or push back on something." You blocked a ship. That is the story.
I have experience moderating Twitch streams, where I've had to block people who repeatedly violated community rules or appeared to be bots. I would look at their behavior, determine whether they were legitimate viewers or suspicious accounts, and take action when necessary. Sometimes that meant blocking someone to prevent spam or protect the community. I learned that it's important to recognize suspicious activity and act on it rather than ignore it just because it might be inconvenient.
