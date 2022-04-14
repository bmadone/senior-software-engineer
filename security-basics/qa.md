## What is the difference between Authentication vs Authorization? 

**Answer:**

* **Authentication** is the process of ascertaining that somebody really is who he claims to be.
* **Authorization** refers to rules that determine who is allowed to do what. E.g. Adam may be authorized to create and delete databases, while Usama is only authorised to read.

Or in short:
* **Authentication** = login + password (who you are)
* **Authorization** = permissions (what you are allowed to do)

Also:
* Authentication = **Verification**
* Authorization = **Permissions**

## What is SQL injection? 

**Answer:**

Injection attacks stem from a lack of strict separation between program instructions (i.e., code) and user-provided (or external) input. This allows an attacker to inject malicious code into a data snippet.

*SQL injection* is one of the most common types of injection attack. To carry it out, an attacker provides malicious SQL statements through the application.

How to prevent:
* **Prepared statements with parameterized queries**
* **Stored procedures**
* **Input validation** - blacklist validation and whitelist validation
* **Principle of least privilege** - Application accounts shouldn’t assign DBA or admin type access onto the database server. This ensures that if an application is compromised, an attacker won’t have the rights to the database through the compromised application.

## What is a DDOS attack? 

**Answer:**

**A denial-of-service attack (DoS attack)** is an attempt to make a computer resource unavailable to its intended users.

Denial of service is typically accomplished by flooding the targeted machine or resource with superfluous requests in an attempt to overload systems and prevent some or all legitimate requests from being fulfilled.

In a **distributed denial-of-service attack (DDoS attack)**, the incoming traffic flooding the victim originates from many different sources. This effectively makes it impossible to stop the attack simply by blocking a single source.


## What is a botnet? 

**Answer:**

A **botnet** is a number of Internet-connected devices, each of which is running one or more bots. Botnets can be used to perform distributed denial-of-service attack (DDoS attack), steal data, send spam, and allows the attacker to access the device and its connection.

## What is Security Testing? 

**Answer:**

Security testing can be considered most important in all type of software testing. Its main objective is to find vulnerabilities in any software (web or networking) based application and protect their data from possible attacks or intruders.

As many applications contains confidential data and needs to be protected being leaked. Software testing needs to be done periodically on such applications to identify threats and to take immediate action on them.

## What is “Vulnerability”? 

**Answer:**

The **Vulnerability** can be defined as weakness of any system through which intruders or bugs can attack on the system.

If security testing has not been performed rigorously on the system then chances of vulnerabilities get increase. Time to time patches or fixes requires preventing a system from the vulnerabilities

##  List the various methodologies in Security testing? 

**Answer:**

Methodologies in Security testing are:
* **White Box** - All the information are provided to the testers.
* **Black Box** - No information is provided to the testers and they can test the system in real world scenario.
* **Grey Box** - Partial information is with the testers and rest they have to rest on their own.

## What is OWASP? 

**Answer:**

**OWASP** stands for *Open Web Application Security Project*.  It is an organization which supports secure software development.

## What is impersonation? 

**Answer:**

Impersonation is an act of pretending to be another person. For IT Systems impersonation means that some specific users (usually Admins) could get an access to other user's data.

## What is Cross-Site Scripting (XSS)? 

**Answer:**

Cross-Site Scripting (XSS) is an attack that occurs when an attacker uses a web application to send malicious code, generally in the form of a browser side script, to a different end user.

The page provided by the server when someone requests it is unaltered. Instead, an XSS attack exploits a weakness in a page that include a variable submitted in a request to show up in raw form in the response. The page is only reflecting back what was submitted in that request.

## What is Intrusion Detection System (IDS)? 

**Answer:**

An **intrusion detection system (IDS)** is a device or software application that monitors a network or systems for malicious activity or policy violations.

Intrusion detection check following:

* Possible attacks
* Any abnormal activity
* Auditing the system data
* Analysis of different collected data etc.

## What is Content Security Policy? 

**Answer:**

**Content Security Policy (CSP)** is an HTTP header that allows site operators fine-grained control over where resources on their site can be loaded from. The use of this header is the best method to prevent cross-site scripting (XSS) vulnerabilities. Due to the difficulty in retrofitting CSP into existing websites, CSP is mandatory for all new websites and is strongly recommended for all existing high-risk sites.

The primary benefit of CSP comes from disabling the use of unsafe inline JavaScript. Inline JavaScript – either reflected or stored – means that improperly escaped user-inputs can generate code that is interpreted by the web browser as JavaScript. By using CSP to disable inline JavaScript, you can effectively eliminate almost all XSS attacks against your site.

## What is CORS and how to enable one? 

**Answer:**

A request for a resource (like an image or a font) outside of the origin is known as a *cross-origin request*. CORS (cross-origin resource sharing) manages cross-origin requests. CORS allows servers to specify who (i.e., which origins) can access the assets on the server, among many other things.

**Access-Control-Allow-Origin** is an HTTP header that defines which foreign origins are allowed to access the content of pages on your domain via scripts using methods such as XMLHttpRequest.

For example, if your server provides both a website and an API intended for XMLHttpRequest access on a remote websites, only the API resources should return the Access-Control-Allow-Origin header. Failure to do so will allow foreign origins to read the contents of any page on your origin.

```sh
# Allow any site to read the contents of this JavaScript library, so that subresource integrity works
Access-Control-Allow-Origin: *
```

## Provide some "robots.txt" anti-pattern usage 

**Answer:**

`robots.txt` is a text file placed within the root directory of a site that tells robots (such as indexers employed by search engines) how to behave, by instructing them not to index certain paths on the website.

It should not be used as a way to prevent the disclosure of private information or to hide portions of a website. Although this does prevent these sites from appearing in search engines, it does not prevent its discovery from attackers, as robots.txt is frequently used for reconnaisance.

```sh
# Using robots.txt to hide certain directories is a terrible idea
User-agent: *
Disallow: /secret/admin-interface
```

## What is Session Hijacking? 

**Answer:**

**Session Hijacking** involves the exploitation of the web session control mechanism. The attacker basically exploits vulnerable connections and steals HTTP cookies to gain unauthorized access to sensitive information/data stored in web servers.

The most effective countermeasure network-level session hijacking is to pick encrypted transport protocols that enable secure connections.

## Explain what threat arises from not flagging HTTP cookies with tokens as secure? 

**Answer:**

*Access Control Violation* threat arises from not flagging HTTP cookies with tokens as secure.

## Mention what flaw arises from session tokens having poor randomness across a range of values? 

**Answer:**

*Session hijacking*, is the issue related to A2: 2017 – Broken Authentication. It is also called cookie hijacking. In this type of attack, there is the possibility of exploitation of a valid computer session—sometimes also called a session key—to gain unauthorized access to information or services in a system. This flaw comes when there is a poor randomness in session key.

## How to mitigate the SQL Injection risks? 

**Answer:**

To mitigate SQL injection:

*   **Prepared Statements with Parameterized Queries:** Always ensure that your SQL interpreter always able to differentiate between code and data. Never use dynamic queries which fail to find the difference between code and data. Instead, use static SQL query and then pass in the external input as a parameter to query.  Use of Prepared Statements (with Parameterized Queries) force developer to first define all the SQL code, and then pass in each parameter to the query later.
*   **Use of Stored Procedures:** Stored Procedure is like a function in C where database administrator call it whenever he/she need it. It is not completely mitigated SQL injection but definitely helps in reducing risks of SQL injection by avoiding dynamic SQL generation inside.
*   **White List Input Validation:** Always use white list input validation and allow only preapproved input by the developer. Never use blacklist approach as it is less secure than whitelist approach.
*   **Escaping All User Supplied Input**
*   **Enforcing Least Privilege**

## How can we Protect Web Applications From Forced Browsing? 

**Answer:**

To protect web applications from forced browsing, strictly monitor access-control settings are accurate and up to date on every page and application on the site.

## What is Cross Site Scripting (XSS)? 

**Answer:**

By using **Cross Site Scripting (XSS)** technique, users executed malicious scripts (also called payloads) unintentionally by clicking on untrusted links and hence, these scripts pass cookies information to attackers.

## What is DOM-based XSS? 

**Answer:**

**DOM-based XSS** is a type of cross-site scripting which appears in DOM(Document Object Model), instead of HTML.

## How can I prevent XSS? 

**Answer:**

XSS can be prevented by sanitizing user input to the application. Always allowed those elements as input which is absolutely essential for that field.

## What is an SSL Certificate? 

**Answer:**

**SSL Certificates** are small data files that digitally bind a *cryptographic key* to an organization’s details. When installed on a web server, it activates the padlock and the https protocol (over port 443) and allows secure connections from a web server to a browser.

## Why is the Root Certificate important? 

**Answer:**

A **Root SSL certificate** is a certificate issued by a trusted certificate authority (CA).

In the SSL ecosystem, anyone can generate a signing key and sign a new certificate with that signature. However, that certificate is not considered valid unless it has been directly or indirectly signed by a trusted CA.

A **trusted certificate authority** is an entity that has been entitled to verify that someone is effectively who it declares to be. In order for this model to work, all the participants on the game must agree on a set of CA which they trust. All operating systems and most of web browsers ship with a set of trusted CAs.
