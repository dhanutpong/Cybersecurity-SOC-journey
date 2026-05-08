# Cybersecurity-SOC-journey
A Journey to Cyber-security &amp;&amp; SOC at the age of 44+

Knowing Growing Step by step I change

6 May 2026

The Discovery
- I knew DIRB (while I explore THM) yesterday and was amazed by how easy we can uncover hidden vulnerabilities.
- It does open my eyes to the world of modern day cybersecurity compare to 30 years ago that you can root to many site to get an admin access.

The Implementation
- I applied this knowledge to my current workplace's website to test it
- When i discover that there are so many + sign (numerous accessible directories), I inform my IT Director about the issue and what i have found and 
- then I helped implement a security measure to mitigate potential attacks. We configured the system to:
    - Detect rapid, automated requests (Anti-DDoS/Brute-force pattern).
    - Automatically block the source IP if it exceeds the threshold.
    - Once blocked, the attacker will no longer receive any response from the server and will be unable to access any URLs.

Reflection: Learning is fun :)

//note: I wrote this with the help of Gemini & GPT //

May 8, 2026 - Module 3
Topic: How the Web Works

1. DNS & Security
Understanding A / CNAME records.
Why Port 443 (HTTPS) is the industry standard over Port 80 (HTTP) due to SSL/TLS encryption.

2. HTTP Methods & The "GET" Confusion

HTTP GET: Used to retrieve data from a web server.
The Confusion: Initially confused GET with a direct Linux CLI command (due to its usage in FTP or PowerShell commands).
The Realization: In a Web context, GET is a Request Method sent inside the protocol, not a direct terminal command. A tool like curl is required to execute it via CLI.
Other Methods: POST (Create), PUT (Replace), and DELETE (Remove).

3. HTML Revival
Re-learning basic tags after 20+ years! * Key tags: <a> for links (Anchor) and <h1> for headers.

4. Put it together
Connected the dots of a single web request:
DNS lookup → SSL Handshake → GET Request → HTML Rendering.



