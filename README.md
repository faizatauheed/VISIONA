VISIONA — Web Security & Vulnerability Assessment

VISIONA is a responsive sunglasses-brand website developed using HTML, CSS, and JavaScript and deployed on Vercel.

As part of this project, I performed a preliminary web application security assessment of my own deployment using Burp Suite Community Edition.

Live Demo:
https://mywebpgehtml.vercel.app/

Technologies:

HTML5
CSS3
JavaScript
Vercel

Security Tools:

Burp Suite Community Edition
Burp Proxy
Burp HTTP History
Browser Developer Tools

Security Assessment:

The assessment focused on:

HTTP request and response analysis
Security header analysis
HTTPS/HSTS configuration
CORS configuration
Client-side JavaScript inspection
Information disclosure
Security-hardening opportunities

Findings:

Content Security Policy was not observed in the captured response.
X-Content-Type-Options was not observed.
A wildcard CORS configuration was observed and reviewed.
Vercel server information was disclosed in the HTTP response.
Inline JavaScript was identified and considered when evaluating CSP.
HTTPS/HSTS was successfully enabled.

Methodology:

HTTP Traffic Capture → Request/Response Analysis → Security Header Review → CORS Analysis → JavaScript Inspection → Finding Documentation → Remediation → Retesting

Evidence:

Burp Suite screenshots are included in the repository to document the assessment process, including HTTP traffic, response headers, and client-side JavaScript inspection.

Security Assessment Report:

A detailed security assessment report is included in the repository. It contains the assessment scope, methodology, findings, evidence, recommendations, limitations, and conclusion.

Learning Outcomes:

Through this project, I gained practical experience in:

Using Burp Suite for web security testing
Intercepting and analyzing HTTP requests and responses
Reviewing HTTP security headers
Analyzing CORS configurations
Inspecting client-side JavaScript
Documenting security findings
Developing remediation recommendations
Understanding the vulnerability assessment lifecycle

Author:

Faiza Tauheed
Cybersecurity Student | Aspiring SOC Analyst
