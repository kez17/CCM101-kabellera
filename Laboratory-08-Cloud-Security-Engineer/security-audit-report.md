# Security Audit Report

## Principle of Least Privilege (PoLP)
This means assigning users and accounts only the minimum permissions needed to complete their duties — no extra rights beyond what is strictly necessary. In cloud environments, this limits potential harm: if an account gets compromised, the attacker can only perform a narrow set of actions and cannot access or damage unrelated resources.

## Attack Surface
For a virtual machine, this is the total collection of all possible entry points  such as open ports, running services, active accounts, and exposed applications  that an attacker could target. Reducing this surface by closing unused ports and stopping unnecessary services makes the server harder to attack because fewer gateways remain open.

## Default Deny Policy
This security stance blocks all incoming traffic automatically unless explicitly permitted, instead of trying to identify and block every malicious source individually. It is much safer because it stops unknown threats automatically, and you only approve traffic you trust leaving no accidental openings for new or unforeseen attacks.
