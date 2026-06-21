# AuthScope

**AuthScope** is a Burp Suite extension for detecting **Broken Access Control** vulnerabilities through intelligent request mutation, replay, and response analysis.

The goal of AuthScope is to assist Application Security engineers and penetration testers in identifying vulnerabilities such as:

* BOLA (Broken Object Level Authorization)
* IDOR (Insecure Direct Object Reference)
* Horizontal privilege escalation
* Vertical privilege escalation
* Authorization bypasses

---

## Motivation

Broken Access Control remains one of the most critical classes of vulnerabilities in modern web applications and APIs. While traditional scanners excel at finding injection flaws and misconfigurations, authorization vulnerabilities often require manual testing.

AuthScope aims to reduce that manual effort by providing tooling for request mutation, replay, and response comparison.

---

## Planned Features

### Request Mutation

* Parameter mutation
* Object ID mutation
* UUID and numeric identifier manipulation

### Replay Engine

* Automatic request replay
* Request pair generation
* Baseline and mutated request comparison

### Response Analysis

* Status code comparison
* Content length analysis
* Response similarity detection
* JSON structure comparison

### Authorization Testing

* BOLA detection
* IDOR detection
* Horizontal privilege escalation checks
* Vertical privilege escalation checks

### JWT Context Analysis

* User identifier extraction
* Role analysis
* Tenant-aware testing

---

## Tech Stack

* Python
* Jython
* Burp Extender API

---

## Status

🚧 Under active development.

---

## Disclaimer

AuthScope is intended for authorized security testing and research purposes only.
