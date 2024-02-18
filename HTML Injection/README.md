HTML:
       - Definition: HTML, or Hypertext Markup Language, serves as the foundation of web pages, providing a standard markup language for structuring content.
       - Functionality: A website comprises a collection of web pages, with HTML elements denoted by angle brackets (<>) representing various functionalities.
HTML Injection Attack:
       -	Vulnerability: HTML Injection occurs in web applications, allowing users to inject HTML code via specific parameters or entry points.
       -	Comparison to XSS: Unlike Cross-site Scripting (XSS), HTML Injection limits attackers to inserting certain HTML tags rather than executing JavaScript code.
       -	Exploitation: When applications fail to handle user-supplied data correctly, attackers can inject valid HTML code, often via parameters, to insert their own content into the page.
       -	Tactics: Social engineering techniques are commonly employed to deceive legitimate users into interacting with malicious content or disclosing sensitive information.
Severity Assessment:
       -	Rating: HTML Injection vulnerabilities are typically classified as P4 bugs with a CVSS score ranging from 0.1 to 3.9, indicating a low severity level.
       -	Potential Impact: In scenarios involving an account takeover, the severity level can elevate to P3.
