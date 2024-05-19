# jenkins_documentation

How to use Jenkins to run automated Python tests
---> https://www.linkedin.com/pulse/how-use-jenkins-run-automated-python-tests-antonio-quarta/

Receive Github webhooks on Jenkins without public IP
--> https://webhookrelay.com/blog/2017/11/23/github-jenkins-guide/
--> https://www.youtube.com/watch?v=S1MiCgns0hg
--> https://mega.nz/file/6jgDBRAD#NgbRU8vDjnbMw0MCBOMknurpZ-Mi--7opcqmPou2IeE


how to install ceedling
--> https://embetronicx.com/tutorials/unit_testing/unit-testing-in-c-testing-with-unity/

 How to download and install Jenkins on Windows 10/11 or Windows Server
 --> https://www.youtube.com/watch?v=taJAfnFFdOE

imporatant : usually you will set jenkins schedule at 15 or 30 minute , don't set it at 1 minute , it wii be a load 
imporatant : You need to successfully run jenkins job al least once manually before webhook would work

comparison between Webhook Relay and ngrok
-----------------------------------------------
Webhook Relay is a service designed specifically to relay webhooks to servers behind firewalls or NAT. It provides a way to forward webhooks from external services to your local development environment without exposing it directly to the internet.

Purpose: Primarily designed for securely relaying webhooks to your local machine or private server.
Setup: Usually involves setting up a relay endpoint provided by Webhook Relay, which forwards requests to your local server.
Security: Offers features like IP whitelisting, secure tunnels, and more to ensure that only specific, authorized requests are forwarded.
Ease of Use: Simplified setup for webhook forwarding, often with minimal configuration required.
Use Case: Ideal for scenarios where you need to receive webhooks from external services (like GitHub, GitLab, or Stripe) on a local or private server.

ngrok is a more general-purpose tool that creates secure tunnels to your local server. It allows you to expose a local web server to the internet, making it accessible via a public URL.

Purpose: General-purpose tunneling solution for exposing local servers, not limited to webhooks.
Setup: Requires installing the ngrok client and starting a tunnel to the desired local port.
Security: Provides secure tunnels with options for authentication, access control, and custom subdomains.
Ease of Use: Simple to set up and use, with a single command to start a tunnel.
Use Case: Useful for a variety of scenarios, including testing webhooks, demonstrating web applications, developing APIs, and accessing local services remotely.

Which to Choose?
Webhook Relay: If your primary need is to receive webhooks from external services on a local or private server, Webhook Relay is the better choice due to its specialized features and security options.
ngrok: If you need a versatile tool for exposing any local server to the internet, whether for webhooks, demonstrations, remote access, or testing, ngrok offers more flexibility and a broader range of use cases.

Conclusion
Both tools are valuable for different purposes. If your focus is on handling webhooks securely and efficiently, Webhook Relay is ideal. For general-purpose tunneling and exposing local services to the internet, ngrok is the more versatile option.


cron syntax
---------------
*/5 * * * * <command to execute> Here, */5 in the minute field means the task will run at every 5-minute schedule.
* * * * * <command to execute> Here,  means the task will run at every 1-minute schedule.
 
