# Analysis-of-network-hardening
<h2>Analysis of network Hardening</h2>
Activity Overview

In this activity, you will be presented with a scenario about a social media organization that recently experienced a major data breach caused by undetected vulnerabilities. To address the breach, you will identify some common network hardening tools that can be implemented to protect the organization’s overall security. Then, you will select a specific vulnerability that the company has and propose different network hardening methods. Finally, you will explain how the methods and tools you chose will be effective for managing the vulnerability and how they will prevent potential breaches in the future. 

In the course, you learned network hardening and network security-related hardening practices, such as port filtering, network access privileges, and encryption over networks. Network hardening practices help organizations monitor potential threats and attacks on their network and prevent some attacks from occurring. Some hardening practices are implemented every day, while others are executed every once in a while, such as every other week or once a month. Understanding how to use network hardening tools and methods will help you better monitor network activity and protect your organization’s network against various attacks.

Be sure to complete this activity before moving on. The next course item will provide you with a completed exemplar to compare to your own work. 

--------------------

## Scenario

Review the following scenario. Then complete the step-by-step instructions.

You are a security analyst working for a social media organization. The organization recently experienced a major data breach, which compromised the safety of their customers’ personal information, such as names and addresses. Your organization wants to implement strong network hardening practices that can be performed consistently to prevent attacks and breaches in the future. 

After inspecting the organization’s network, you discover four major vulnerabilities. The four vulnerabilities are as follows:

-  The organization’s employees' share passwords.

-  The admin password for the database is set to the default.

-  The firewalls do not have rules in place to filter traffic coming in and out of the network.

-  Multifactor authentication (MFA) is not used. 

If no action is taken to address these vulnerabilities, the organization is at risk of experiencing another data breach or other attacks in the future. 

In this activity, you will write a security risk assessment to analyze the incident and explain what methods can be used to further secure the network.

--------------------------
<h2>Step 1: Accessing the template </h2>

[Cybersecurity incident report.pdf]([[https://github.com/kalemriah/Analyzing-A-Network-Attack/files/12285915/Cybersecurity.incident.report.pdf](https://docs.google.com/document/d/1vkA_0hML_p1k1eKY_Phq0tUaPSQ5hv5hoRNlveVgV10/edit?usp=sharing)](https://docs.google.com/document/d/1X-vXSpw50fayEag0ej526Mt4lkwcfKJ4JbtJyXPvvn4/template/preview?usp=sharing&resourcekey=0-oajIyd93Jwql2MAckWYLUg))

----------------------------

### Security Risk Assessment
### Part 1: Hardening Tools and Methods to Implement
1. Enforce Strong Password Policies

2. Implement Multi-Factor Authentication (MFA)

3. Configure Firewall Rules

### Part 2: Explanation of Recommendations
## 1. Enforce Strong Password Policies:

- Description: Implementing strong password policies ensures that all passwords used within the organization are complex, unique, and not easily guessable. This includes setting requirements for minimum length, complexity (use of uppercase and lowercase letters, numbers, and special characters), and regular password changes.

- Purpose: Strong passwords reduce the risk of unauthorized access due to easily guessable or shared passwords. It also minimizes the likelihood of brute force attacks.

- Implementation Steps:

   - Mandate that all employees create passwords that meet complexity requirements.

   - Prohibit password sharing among employees.

   - Implement a password manager to securely store and manage passwords.

   - Educate employees on the importance of strong passwords and the risks of sharing them.

## 2. Implement Multi-Factor Authentication (MFA):

- Description: Multi-Factor Authentication (MFA) adds an extra layer of security by requiring users to provide two or more verification factors to gain access to resources. This typically includes something the user knows (password), something the user has (security token or mobile app), and something the user is (biometrics).

- Purpose: MFA significantly increases the security of user accounts by ensuring that even if a password is compromised, an attacker would still need the additional verification factors to gain access.

- Implementation Steps:

   - Enable MFA for all critical systems and user accounts, particularly those with administrative access.

   - Use MFA tools such as authentication apps, hardware tokens, or SMS-based verification.

   - Regularly review and update MFA settings to adapt to emerging security threats.

   - Train employees on how to use MFA and the importance of this security measure.

## 3. Configure Firewall Rules:

- Description: Firewalls are crucial for protecting the organization's network by filtering incoming and outgoing traffic based on predetermined security rules. Properly configured firewall rules help to prevent unauthorized access, data breaches, and malicious activities.

- Purpose: Configuring firewall rules ensures that only legitimate traffic is allowed to enter or leave the network, thus protecting the network from potential threats and unauthorized access.

- Implementation Steps:

   - Create and enforce firewall rules that restrict access to sensitive systems and data.

   - Regularly update firewall rules to reflect changes in the network architecture and emerging threats.

   - Monitor firewall logs and alerts to detect and respond to suspicious activities promptly.

   - Perform regular security audits to ensure firewall rules are effective and up to date.

-------------------------------

<h2>Step 2: Accessing the supporting Material </h2>

[Cybersecurity incident report.pdf]([[https://github.com/kalemriah/Analyzing-A-Network-Attack/files/12285915/Cybersecurity.incident.report.pdf](https://docs.google.com/document/d/1vkA_0hML_p1k1eKY_Phq0tUaPSQ5hv5hoRNlveVgV10/edit?usp=sharing](https://docs.google.com/spreadsheets/d/1G1gSxuCyKTNmc1zPKzB7ETNdL7HkhB_QIHGZJ8aZkSk/template/preview?usp=sharing))







