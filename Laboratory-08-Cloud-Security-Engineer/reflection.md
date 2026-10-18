# Mission Reflection

A host-based firewall protects the server directly from within, so it continues filtering traffic even if attackers have already bypassed external network defenses. Every connection is checked right at the machine — acting as a final security layer that cannot be bypassed just by reaching the same network.

Carefully managing open ports directly shrinks the attack surface because every listening port is a potential entry point. Services you do not run should remain closed; each port left exposed gives attackers another target to scan and probe, so keeping only essential ports open drastically reduces risk.

Publicly exposing a database port like 3306 is extremely dangerous because databases store sensitive information such as credentials, personal details, and business records. Automated scanning tools constantly hunt for these open ports to launch brute-force or injection attacks, and exposure often leads to data theft, permanent loss, or full system takeover.

Completing this mission changed my view on how rapidly an unprotected system can be targeted — even a short window of exposure carries real risk. I also saw how small procedural errors, like activating the firewall too early, can instantly cut off your own access, showing that security demands both the right tools and careful, step-by-step planning.

Now with eight missions complete, my portfolio shows a clear learning path — from cloud basics through deployment, operations, and now security — demonstrating I can handle full workflows and document them professionally. This growing record will be valuable as I pursue future opportunities in technology.
